# 12 - Modlist de référence et load order

## Objectif

Ce document sert de référence officielle pour le load order du modpack **Conan Exiles Enhanced / UE5**.

Tous les joueurs doivent utiliser les mêmes mods, dans le même ordre, sans mod personnel supplémentaire.

## État actuel de la référence

La référence complète contient désormais **45 mods listés**.

La nouvelle série de tests ingame a validé plusieurs changements :

- **Tanny's WDV Tattoos und Narben - Enhanced** est réintégré et validé ;
- **Exile Architect: Enhanced** est ajouté et validé ;
- **Adonia Salon** est ajouté et validé ;
- **Grims Wonderbody Reupload Enhanced** est ajouté et validé ;
- **Aquilonian Females Enhanced** est retiré, remplacé par **Wonderbody Enhanced** ;
- **LegitReligious** reste le seul mod encore en attente de mise à jour post-update.

Résumé actuel :

- **44 mods chargeables / fonctionnels** dans la base active ;
- **1 mod en attente de mise à jour post-update** ;
- **Navi's Revived Leveling Enhanced** est retiré et remplacé par **Level 120 Progression Mod** ;
- **Aquilonian Females Enhanced** est retiré et remplacé par **Grims Wonderbody Reupload Enhanced**.

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
| 18 | Tanny's WDV Tattoos und Narben - Enhanced | `3723007453` | `WdV_Tattoo_und_Narben.pak` | Tatouages / cicatrices | Réintégré / validé | Test ingame OK : aucun crash, aucun freeze, fonctionnement confirmé. |
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
| 30 | LegitReligious | `3720748663` | `LegitReligious_Enhanced.pak` | Religion | En attente MAJ post-update | Non chargé dans la base active. Ne bloque pas le modpack pour jouer. |
| 31 | Diverse Barkeeps | `3722887659` | `DiverseBarkeepers.pak` | PNJ / ambiance | Validé | Ambiance PNJ. |
| 32 | Craftable Legendaries | `3721054666` | `CraftableLegendaries.pak` | Craft / progression | Validé | À surveiller côté équilibrage. |
| 33 | Sorcery Tweaks Enhanced | `3723524908` | `SorceryTweaksEnhanced.pak` | Sorcellerie | Validé | Sorcellerie. |
| 34 | Dark Decention Cooking and Brewing | `3721764383` | `DarkDecentionCookingandBrewing.pak` | Cuisine / brassage | Validé | Cuisine / brassage. |
| 35 | Level 120 Progression Mod | `3722211036` | `Level120Progression.pak` | Progression / leveling | Validé | Remplace Navi's Revived Leveling Enhanced. Progression utile jusqu'au niveau 120 ; après 120, le PJ continue de monter mais sans points d'attributs ni de savoir. |
| 36 | Exile Architect: Enhanced | `3729398837` | `RopeLines.pak` | Building léger | Validé | Testé ingame seul puis avec la modlist complète. Fonctionne nickel. |
| 37 | SH - Building Kit Enhanced | `3728528172` | `SH_BuildingKit.pak` | Building | Validé | Ajouté avec SH - Decorations v1.0.1. Testé et validé. |
| 38 | Ancient Civilization - Enhanced | `3721996090` | `Asghaard_Ancient_Civilization.pak` | Building | Validé | Building. |
| 39 | Desert Town | `3721019326` | `Asghaard_Desert_Town.pak` | Building | Validé | Building. |
| 40 | Wicked Webs of Zamora UE5 | `3723048378` | `WickedWebsofZamora.pak` | Building | Validé | Éléments de construction testés. |
| 41 | Al-Merayah Reborn by Xevyr | `3718036277` | `AlMerayah_Reborn.pak` | Gameplay système / contenu monde | Validé | Testé et validé après update. Placement conseillé : avant The Purge mod. |
| 42 | The Purge mod by Xevyr | `3719604490` | `Retro_Purge.pak` | Gameplay système | Validé | Test fonctionnel contrôlé validé. |
| 43 | Complete Thrall Fashion vE-1.3.5 | `3725384942` | `CompleteFashion.pak` | Apparence / Thralls / Armures | Validé | Placé avant les mods d'apparence finale. |
| 44 | Adonia Salon | `3729456480` | `AdoniaHairs.pak` | Apparence / coiffures | Validé | Ajouté et testé ingame. |
| 45 | Grims Wonderbody Reupload Enhanced | `3729384808` | `WonderBody_Enhanced.pak` | Apparence / body féminin | Validé | Remplace Aquilonian Females Enhanced. Testé ingame seul puis avec la modlist complète. |

## Mods temporairement en attente de mise à jour post-update

Ce mod reste dans la référence officielle, mais il ne doit pas être chargé dans le `modlist.txt` actif tant qu'il n'a pas été corrigé et retesté :

| Mod | Fichier .pak | Raison |
|---|---|---|
| LegitReligious | `LegitReligious_Enhanced.pak` | Pas encore mis à jour. Ancien crash avant menu après update. |

## Mods rejetés / retirés / remplacés / différés

| Mod | Statut | Raison |
|---|---|---|
| Lisas Building Stone Age | Rejeté | Mod affiché comme corrompu / erreur de parsing. |
| Enhanced Builder 2026.5.9 | Retiré / différé | Identifié comme responsable du blocage de l'intro au clic souris. |
| The Compendium of Crawling Chaos Enhanced Edition | Rejeté / différé | Freeze complet du PC lors du test isolé. Retrait confirmé, stabilité retrouvée. |
| Chem's Pinnacle Levelling | Écarté / remplacé | Navi's Revived Leveling Enhanced répondait mieux au besoin de progression configurable à ce moment-là. |
| Navi's Revived Leveling Enhanced | Remplacé / retiré | Cassé après mise à jour Conan Enhanced ; remplacé par Level 120 Progression Mod. |
| Aquilonian Females Enhanced | Remplacé / retiré | Remplacé par Grims Wonderbody Reupload Enhanced. |
| LetMeCrawl | Testé mais non retenu | Fonctionne correctement, mais ne correspond pas au feeling souhaité pour le modpack. |
| [Enhanced] More T4 Thralls Plus - v1.0.0 | Rejeté | Crash Unreal / UE-ConanSandbox à l'arrivée ingame. Test de contrôle sans le mod : retour à la stabilité. |
| Katis_Tattoos | Rejeté / différé | Dépendance Tot Custom non retenue pour l'objectif coop. |
| Face It Enhanced | Rejeté / différé | Dépendance Tot Sudo non retenue pour conserver une base coop propre. |
| Pickup+, LBPR et LBPR Additional Features | Différés | Non visibles via filtre Enhanced au moment de la recherche. |

## Notes importantes

### Série de tests ingame récente

Fabien a modifié le modpack, ajouté et supprimé plusieurs mods, puis les a testés ingame un par un et tous ensemble.

Résultat : le modpack fonctionne nickel avec la base active actuelle.

### Grims Wonderbody Reupload Enhanced

**Grims Wonderbody Reupload Enhanced** remplace **Aquilonian Females Enhanced** comme mod d'apparence / body féminin.

### Adonia Salon

**Adonia Salon** est ajouté comme mod d'apparence / coiffures.

### Exile Architect: Enhanced

**Exile Architect: Enhanced** est ajouté comme mod de construction léger.

Son fichier `.pak` réel est `RopeLines.pak`.

### LegitReligious

**LegitReligious** reste en stand-by, mais son absence ne bloque pas le modpack pour jouer.

### Level 120 Progression Mod

**Level 120 Progression Mod** remplace **Navi's Revived Leveling Enhanced**.

Comportement validé :

- progression utile jusqu'au niveau 120 ;
- après le niveau 120, le personnage peut continuer à gagner des niveaux ;
- après le niveau 120, il ne reçoit plus de points d'attributs ni de points de savoir.

Ce comportement est accepté pour le modpack.

### Compatibilité coop

Les tests de Fabien sont effectués directement en **mode Coop / host local**, ce qui est plus représentatif de l'utilisation réelle prévue pour le modpack.

### Menu Mods en jeu

Pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop.

Méthode de vérification retenue : abonnement Workshop, présence du `.pak`, activation dans le menu Mods en jeu, respect du load order, redémarrage si demandé, puis test en Coop / host local.

## Statut

Document mis à jour avec les **45 mods listés dans la référence complète**, dont **44 actuellement chargeables** et **1 en attente de mise à jour post-update**.
