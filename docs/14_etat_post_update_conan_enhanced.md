# 14 - État post-update Conan Enhanced

## Objectif

Documenter l'état temporaire du modpack après une mise à jour Conan Exiles Enhanced ayant cassé plusieurs mods au lancement.

Ce document sert de référence courte pour reprendre le diagnostic, protéger la sauvegarde en cours et savoir quels mods attendre avant retour à la modlist complète.

## Constat initial

Après mise à jour du jeu Conan Exiles Enhanced, le jeu crashait avant d'atteindre le menu principal avec une erreur de type :

```text
Unhandled Exception: EXCEPTION_ACCESS_VIOLATION writing address
VCRUNTIME140
ConanSandbox_Win64_Shipping
```

Le test de neutralisation du fichier `modlist.txt` a permis de confirmer que le jeu démarrait correctement sans mods.

Conclusion : le jeu vanilla n'était pas cassé ; le problème venait d'un ou plusieurs mods chargés au démarrage.

## Méthode de diagnostic utilisée

- Sauvegarde / neutralisation temporaire du `modlist.txt`.
- Test du lancement sans mods.
- Reconstruction progressive de la modlist par blocs.
- Identification des mods fautifs à partir des messages `ObjectSerializationError` et des tests d'isolation.
- Retrait temporaire des lignes concernées du `modlist.txt` actif.

Important : Conan ne semble pas accepter de commentaire fiable dans `modlist.txt`. Retirer le `*` au début d'une ligne ne suffit pas. Pour désactiver un mod, il faut retirer complètement la ligne du fichier actif.

## État actuel provisoire

- Modlist officielle avant update : **41 mods actifs validés**.
- Mods temporairement retirés après update : **5**.
- Modlist provisoire fonctionnelle : **36 mods actifs**.

Cette modlist provisoire doit être utilisée avec prudence sur la partie en cours.

## Mods temporairement cassés après update

| Mod | Workshop ID | Fichier .pak | Statut | Raison / erreur |
|---|---:|---|---|---|
| Primal Instinct | `3723050568` | `PrimalInstincts.pak` | Retiré temporairement | `ObjectSerializationError` / `Bad name index` sur `W_SpectatorCleanScreen`. |
| SH - Decorations | `3723606644` | `SH_Decorations.pak` | Retiré temporairement | `ObjectSerializationError` / `Bad export index` sur `BP_PL_Deco_Ground`. |
| Tanny's WDV Tattoos und Narben - Enhanced | `3723007453` | `WdV_Tattoo_und_Narben.pak` | Retiré temporairement | `ObjectSerializationError` / `Bad name index` sur `WDV_BP_PL_Brazier_of_Pain`. |
| LegitReligious Enhanced | `3720748663` | `LegitReligious_Enhanced.pak` | Retiré temporairement | Crash avant menu, identifié par isolation ; erreur liée à `/Game/Dev/AlmostEmpty` / `Ultra_Dynamic_Sky_BP`. |
| Navi's Revived Leveling Enhanced | `3722559607` | `NRLe.pak` | Retiré temporairement | Crash au lancement avant menu, identifié par isolation. |

## Modlist provisoire active à 36 mods

Les emplacements des mods retirés peuvent rester visibles sous forme de lignes vides dans la copie locale de travail, mais le `modlist.txt` actif ne doit contenir que les lignes de mods réellement chargées.

```text
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719513784/Simple_Minimap.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720915336/StacksizePlus.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718655125/LLHighlight.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719621216/TwinBar.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719546290/SimpleModlist.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720921242/StylistPlus.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720904511/BetterThralls.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3725707777/EAA_ThrallLevelIncrease.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718614759/Inventory_compactor.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720948133/UnlockableContainers.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718523921/Thrall_Commander.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719642461/Xev_HearthStone.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723576515/PandasBloodyMess.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723546665/MoreClanEmblemsEnhanced.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3722359128/Topfreedom.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721257555/LustGoddessArmor.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720479864/DerketoAcolyteReplacer.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720730572/CNC.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3722409363/HyperBoreanReforged.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723318494/ArmorScrap.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723127994/TDI_LegendaryRepair.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723101055/SortingBox.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720452046/automatic_fish_trap_enhanced.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720753923/EnhancedPlayerIgnoresFollowerCollision.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720667122/AdvancedGliders.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720692529/DrK_SpidersToScorpions_CEE.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3722887659/DiverseBarkeepers.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721054666/CraftableLegendaries.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723524908/SorceryTweaksEnhanced.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721764383/DarkDecentionCookingandBrewing.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721996090/Asghaard_Ancient_Civilization.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721019326/Asghaard_Desert_Town.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723048378/WickedWebsofZamora.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719604490/Retro_Purge.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3725384942/CompleteFashion.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721124998/AquilonianFemales_UE5.pak
```

## Consignes de sécurité pour la partie en cours

Avant de charger la vraie partie coop :

1. Sauvegarder le dossier de sauvegarde Conan.
2. Lancer le jeu avec la modlist provisoire à 36 mods.
3. Charger la partie sans sauvegarder immédiatement.
4. Vérifier le personnage, les niveaux, les thralls, les bâtiments et les objets posés.
5. Quitter sans sauvegarder en cas d'anomalie importante.

Le retrait temporaire de `NRLe.pak` est le point le plus sensible, car il touche à la progression / leveling.

Le retrait de mods de décoration ou d'apparence peut provoquer la disparition d'objets posés, mais il est moins critique qu'un blocage complet au lancement.

## Retour à la modlist complète

Les 5 mods retirés ne doivent être réintégrés qu'après mise à jour Workshop et test isolé :

- relancer le jeu avec un seul mod réintroduit à la fois ;
- vérifier l'arrivée au menu ;
- vérifier une nouvelle partie test ;
- seulement ensuite tester la vraie sauvegarde sans sauvegarde immédiate.

## Remplacement envisagé

`NRLe.pak` pourra éventuellement être remplacé par un autre mod de progression plus rapidement mis à jour, mais uniquement après test isolé.

Candidat à surveiller / tester plus tard :

- **Level 120 Progression Mod (Max Knowledge and Attribute Points)**
- Workshop ID : `3722211036`

## Statut

Le modpack n'est pas abandonné. Il est en **mode maintenance post-update**, avec une base provisoire fonctionnelle à **36 mods actifs**.
