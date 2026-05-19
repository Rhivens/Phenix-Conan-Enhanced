# 12 - Modlist de référence et load order

## Objectif

Ce document sert de référence officielle pour le load order du modpack **Conan Exiles Enhanced / UE5**.

Tous les joueurs doivent utiliser les mêmes mods, dans le même ordre, sans mod personnel supplémentaire.

## État actuel de la référence

La référence complète contient désormais **43 mods listés**.

Après la mise à jour Conan Enhanced, plusieurs mods ont dû être retirés temporairement. **SH - Decorations v1.0.1 (Enhanced)** a depuis été mis à jour, testé et réintégré. **Primal Instincts Enhanced** a également été mis à jour, testé et réintégré. **SH - Building Kit (1.0.2)** a aussi été ajouté et validé.

Résumé actuel :

- **41 mods chargeables / fonctionnels** dans la base post-update actuelle ;
- **2 mods en attente de mise à jour post-update** ;
- **Navi's Revived Leveling Enhanced** est retiré et remplacé par **Level 120 Progression Mod** ;
- **Al-Merayah Reborn** est ajouté et validé ;
- **SH - Decorations** est réintégré après mise à jour ;
- **Primal Instincts Enhanced** est réintégré après mise à jour ;
- **SH - Building Kit** est ajouté et validé.

## Load order officiel actuel

| Ordre | Mod | Workshop ID | Fichier .pak | Catégorie | Statut | Notes |
|---:|---|---:|---|---|---|---|
| 1 | Simple Minimap | `3719513784` | `Simple_Minimap.pak` | Interface & QoL | Validé | Mod Xevyr. |
| 2 | Stacksize Plus | `3720915336` | `StacksizePlus.pak` | Inventaire / confort | Validé | Réglage conseillé au départ : x5. |
| 3 | Lore & Loot Highlight | `3718655125` | `LLHighlight.pak` | Interface & QoL | Validé | Commande : `dc LLHSettings`. |
| 4 | Twin-Bar | `3719621216` | `TwinBar.pak` | Interface / hotbar | Validé | Barre rapide secondaire. |
| 5 | Simple Modlist | `3719546290` | `SimpleModlist.pak` | Information modlist | Validé | Utile pour vérifier les mods actifs. |
| 6 | Fashionist | `3720921242` | `StylistPlus.pak` | Apparence | Validé | Gestion cosmétique. |
| 7 | Better Thralls | `3720904511` | `BetterThralls.pak` | Thralls / compagnons | Validé | À surveiller en usage prolongé. |
| 8 | [Enhanced] EAA - Lv50 Thralls | `3725707777` | `EAA_ThrallLevelIncrease.pak` | Thralls / pets / progression | Validé | Cap niveau 50 confirmé avec `LevelFollowerUpTo 21` puis `LevelFollowerUpTo 50`. |
| 9 | Inventory Compactor | `3718614759` | `Inventory_compactor.pak` | Inventaire | Validé | Compactage et rangement. |
| 10 | Unlock Plus | `3720948133` | `UnlockableContainers.pak` | Stockage / QoL | Validé | Compatible avec Organizer Sorting Chest à ce stade. |
| 11 | Follower Remote | `3718523921` | `Thrall_Commander.pak` | Thralls / compagnons | Validé | Commande : `dc frsettings`. |
| 12 | Xevyr's Hearthstone | `3719642461` | `Xev_HearthStone.pak` | Mobilité | Validé | Pierre de retour liée au lit. |
| 13 | Primal Instincts Enhanced | `3723050568` | `PrimalInstincts.pak` | Contenu adulte privé | Réintégré / validé | Ancien crash post-update corrigé par mise à jour. Menu actif et scènes fonctionnelles. |
| 14 | Panda's Bloody Mess | `3723576515` | `PandasBloodyMess.pak` | Ambiance visuelle | Validé | Ambiance gore. |
| 15 | More Clan Emblems Enhanced | `3723546665` | `MoreClanEmblemsEnhanced.pak` | Clan / emblèmes | Validé | Personnalisation de clan. |
| 16 | SH - Decorations v1.0.1 Enhanced | `3723606644` | `SH_Decorations.pak` | Décoration | Réintégré / validé | Ancien crash post-update corrigé par la mise à jour v1.0.1. Testé et validé. |
| 17 | Topfreedom Enhanced | `3722359128` | `Topfreedom.pak` | Apparence | Validé | Mod cosmétique. |
| 18 | Tanny's WDV Tattoos und Narben - Enhanced | `3723007453` | `WdV_Tattoo_und_Narben.pak` | Tatouages / cicatrices | En attente MAJ post-update | Crash avant menu après update : `ObjectSerializationError` / `Bad name index` sur `WDV_BP_PL_Brazier_of_Pain`. |
| 19 | Sacred Lust armor set | `3721257555` | `LustGoddessArmor.pak` | Armure / cosmétique | Validé | Armure testée. |
| 20 | Derketo Acolyte Replacer | `3720479864` | `DerketoAcolyteReplacer.pak` | Armure / cosmétique | Validé | Test isolé validé. |
| 21 | CNC - Enhanced | `3720730572` | `CNC.pak` | Contenu léger | Validé | Intro toujours passable. |
| 22 | HyperBoreanReforged | `3722409363` | `HyperBoreanReforged.pak` | Contenu / équipement | Validé | Placement validé entre CNC et Armor Scraps. |
| 23 | Craftable Armor Scraps - Enhanced | `3723318494` | `ArmorScrap.pak` | Craft / ressources | Validé | Craft / ressources. |
| 24 | TDI_LegendaryRepair | `3723127994` | `TDI_LegendaryRepair.pak` | Craft / réparation | Validé | Réparation légendaire. |
| 25 | Organizer Sorting Chest | `3723101055` | `SortingBox.pak` | Stockage / tri | Validé | Fonctionne avec Unlock Plus. |
| 26 | Automatic Fish Trap | `3720452046` | `automatic_fish_trap_enhanced.pak` | Ressources | Validé | Automatisation légère. |
| 27 | Player Ignores Follower Collision | `3720753923` | `EnhancedPlayerIgnoresFollowerCollision.pak` | Followers / Coop | Validé | Confort coop. |
| 28 | Enhanced Gliders | `3720667122` | `AdvancedGliders.pak` | Mobilité | Validé | Planeurs. |
| 29 | DrK Spiders to Scorpions | `3720692529` | `DrK_SpidersToScorpions_CEE.pak` | Créatures | Validé | Aucun CTD ni freeze. |
| 30 | LegitReligious | `3720748663` | `LegitReligious_Enhanced.pak` | Religion | En attente MAJ post-update | Crash avant menu après update, identifié par isolation. Erreur liée à `/Game/Dev/AlmostEmpty` / `Ultra_Dynamic_Sky_BP`. |
| 31 | Diverse Barkeeps | `3722887659` | `DiverseBarkeepers.pak` | PNJ / ambiance | Validé | Ambiance PNJ. |
| 32 | Craftable Legendaries | `3721054666` | `CraftableLegendaries.pak` | Craft / progression | Validé | À surveiller côté équilibrage. |
| 33 | Sorcery Tweaks Enhanced | `3723524908` | `SorceryTweaksEnhanced.pak` | Sorcellerie | Validé | Sorcellerie. |
| 34 | Dark Decention Cooking and Brewing | `3721764383` | `DarkDecentionCookingandBrewing.pak` | Cuisine / brassage | Validé | Cuisine / brassage. |
| 35 | Level 120 Progression Mod | `3722211036` | `Level120Progression.pak` | Progression / leveling | Validé | Remplace Navi's Revived Leveling Enhanced. Progression utile jusqu'au niveau 120 ; après 120, le PJ continue de monter mais sans points d'attributs ni de savoir. |
| 36 | SH - Building Kit Enhanced | `3728528172` | `SH_BuildingKit.pak` | Building | Validé | Ajouté avec SH - Decorations v1.0.1. Testé et validé. |
| 37 | Ancient Civilization - Enhanced | `3721996090` | `Asghaard_Ancient_Civilization.pak` | Building | Validé | Building. |
| 38 | Desert Town | `3721019326` | `Asghaard_Desert_Town.pak` | Building | Validé | Building. |
| 39 | Wicked Webs of Zamora UE5 | `3723048378` | `WickedWebsofZamora.pak` | Building | Validé | Éléments de construction testés. |
| 40 | Al-Merayah Reborn by Xevyr | `3718036277` | `AlMerayah_Reborn.pak` | Gameplay système / contenu monde | Validé | Testé et validé après update. Placement conseillé : avant The Purge mod. |
| 41 | The Purge mod by Xevyr | `3719604490` | `Retro_Purge.pak` | Gameplay système | Validé | Test fonctionnel contrôlé validé. |
| 42 | Complete Thrall Fashion vE-1.3.5 | `3725384942` | `CompleteFashion.pak` | Apparence / Thralls / Armures | Validé | Placé avant Aquilonian Females Enhanced. |
| 43 | Aquilonian Females Enhanced | `3721124998` | `AquilonianFemales_UE5.pak` | Apparence / body féminin | Validé | Test nouvelle partie concluant, pas de clipping observé sur plusieurs tenues. |

## Mods temporairement en attente de mise à jour post-update

Ces mods restent dans la référence officielle, mais ils ne doivent pas être chargés dans le `modlist.txt` actif tant qu'ils n'ont pas été corrigés et retestés :

| Mod | Fichier .pak | Raison |
|---|---|---|
| Tanny's WDV Tattoos und Narben - Enhanced | `WdV_Tattoo_und_Narben.pak` | Crash avant menu après update. |
| LegitReligious | `LegitReligious_Enhanced.pak` | Crash avant menu après update. |

## Mods rejetés / retirés / remplacés / différés

| Mod | Statut | Raison |
|---|---|---|
| Lisas Building Stone Age | Rejeté | Mod affiché comme corrompu / erreur de parsing. |
| Enhanced Builder 2026.5.9 | Retiré / différé | Identifié comme responsable du blocage de l'intro au clic souris. |
| The Compendium of Crawling Chaos Enhanced Edition | Rejeté / différé | Freeze complet du PC lors du test isolé. Retrait confirmé, stabilité retrouvée. |
| Chem's Pinnacle Levelling | Écarté / remplacé | Navi's Revived Leveling Enhanced répondait mieux au besoin de progression configurable à ce moment-là. |
| Navi's Revived Leveling Enhanced | Remplacé / retiré | Cassé après mise à jour Conan Enhanced ; remplacé par Level 120 Progression Mod. |
| [Enhanced] More T4 Thralls Plus - v1.0.0 | Rejeté | Crash Unreal / UE-ConanSandbox à l'arrivée ingame. Test de contrôle sans le mod : retour à la stabilité. |
| Katis_Tattoos | Rejeté / différé | Dépendance Tot Custom non retenue pour l'objectif coop. |
| Face It Enhanced | Rejeté / différé | Dépendance Tot Sudo non retenue pour conserver une base coop propre. |
| Pickup+, LBPR et LBPR Additional Features | Différés | Non visibles via filtre Enhanced au moment de la recherche. |

## Notes importantes

### Primal Instincts Enhanced

**Primal Instincts Enhanced** est réintégré après mise à jour et validé.

Test post-update :

- menu actif ;
- scènes fonctionnelles ;
- ancien crash `W_SpectatorCleanScreen` non reproduit.

### SH - Decorations / SH - Building Kit

**SH - Decorations v1.0.1 (Enhanced)** est réintégré après mise à jour et validé.

**SH - Building Kit (1.0.2)** est ajouté et validé. Il est placé juste après **Level 120 Progression Mod** et avant les gros mods de building Asghaard.

### Level 120 Progression Mod

**Level 120 Progression Mod** remplace **Navi's Revived Leveling Enhanced**.

Comportement validé :

- progression utile jusqu'au niveau 120 ;
- après le niveau 120, le personnage peut continuer à gagner des niveaux ;
- après le niveau 120, il ne reçoit plus de points d'attributs ni de points de savoir.

Ce comportement est accepté pour le modpack.

### Al-Merayah Reborn

**Al-Merayah Reborn by Xevyr** est validé et placé avant **The Purge mod by Xevyr**.

### Compatibilité coop

Les tests de Fabien sont effectués directement en **mode Coop / host local**, ce qui est plus représentatif de l'utilisation réelle prévue pour le modpack.

### Menu Mods en jeu

Pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop.

Méthode de vérification retenue : abonnement Workshop, présence du `.pak`, activation dans le menu Mods en jeu, respect du load order, redémarrage si demandé, puis test en Coop / host local.

## Statut

Document mis à jour avec les **43 mods listés dans la référence complète**, dont **41 actuellement chargeables** et **2 en attente de mise à jour post-update**.
