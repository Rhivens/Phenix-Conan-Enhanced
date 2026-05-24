# 12 - Modlist de référence et load order

## Objectif

Ce document sert de référence officielle pour le load order du modpack **Conan Exiles Enhanced / UE5**.

Tous les joueurs doivent utiliser les mêmes mods, dans le même ordre, sans mod personnel supplémentaire.

## État actuel de la référence

La référence complète contient désormais **53 mods listés et chargeables**.

La dernière série de tests ingame a validé :

- ajout de **Nat's Trees Enhanced** ;
- ajout de **High Heels System 3.2.8** ;
- ajout de **Devious Desires Enhanced** ;
- remplacement / mise à jour pratique de **Adonia Salon** vers le Workshop ID `3731613388` et le fichier `AdoniaSalon.pak` ;
- confirmation d'une base active complète et fonctionnelle après test gameplay : aucun crash, aucun freeze.

Résumé actuel :

- **53 mods chargeables / fonctionnels** dans la base active ;
- **0 mod en attente de mise à jour post-update** ;
- **Navi's Revived Leveling Enhanced** est retiré et remplacé par **Level 120 Progression Mod** ;
- **Aquilonian Females Enhanced** est retiré et remplacé par **Grims Wonderbody Reupload Enhanced**.

## Load order officiel actuel

| Ordre | Mod | Lien Steam Workshop | Workshop ID | Fichier .pak | Catégorie | Statut | Notes |
|---:|---|---|---:|---|---|---|---|
| 1 | Simple Minimap | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719513784) | `3719513784` | `Simple_Minimap.pak` | Interface & QoL | Validé | Mod Xevyr. |
| 2 | Stacksize Plus | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720915336) | `3720915336` | `StacksizePlus.pak` | Inventaire / confort | Validé | Réglage conseillé au départ : x5. |
| 3 | Lore & Loot Highlight | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718655125) | `3718655125` | `LLHighlight.pak` | Interface & QoL | Validé | Commande : `dc LLHSettings`. |
| 4 | Twin-Bar | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719621216) | `3719621216` | `TwinBar.pak` | Interface / hotbar | Validé | Barre rapide secondaire. |
| 5 | Simple Modlist | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719546290) | `3719546290` | `SimpleModlist.pak` | Information modlist | Validé | Utile pour vérifier les mods actifs. |
| 6 | Greater Camera Distance Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729620808) | `3729620808` | `3rdCamDist.pak` | Caméra / QoL combat | Validé | Version Enhanced correcte. Bon QoL caméra en combat. Placé sous Simple Modlist. |
| 7 | Fashionist | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720921242) | `3720921242` | `StylistPlus.pak` | Apparence | Validé | Gestion cosmétique. |
| 8 | Better Thralls | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720904511) | `3720904511` | `BetterThralls.pak` | Thralls / compagnons | Validé | À surveiller en usage prolongé. |
| 9 | [Enhanced] EAA - Lv50 Thralls | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3725707777) | `3725707777` | `EAA_ThrallLevelIncrease.pak` | Thralls / pets / progression | Validé | Cap niveau 50 confirmé avec `LevelFollowerUpTo 21` puis `LevelFollowerUpTo 50`. |
| 10 | Inventory Compactor | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718614759) | `3718614759` | `Inventory_compactor.pak` | Inventaire | Validé | Compactage et rangement. |
| 11 | Unlock Plus | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720948133) | `3720948133` | `UnlockableContainers.pak` | Stockage / QoL | Validé | Compatible avec Organizer Sorting Chest à ce stade. |
| 12 | Follower Remote | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718523921) | `3718523921` | `Thrall_Commander.pak` | Thralls / compagnons | Validé | Commande : `dc frsettings`. |
| 13 | Xevyr's Hearthstone | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719642461) | `3719642461` | `Xev_HearthStone.pak` | Mobilité | Validé | Pierre de retour liée au lit. |
| 14 | [Enhanced] Faster Elevator v1.0.2 | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729885653) | `3729885653` | `FasterElevator.pak` | Mobilité / QoL base | Validé | Ajouté après Xevyr's Hearthstone. Test ingame validé. |
| 15 | Primal Instincts Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723050568) | `3723050568` | `PrimalInstincts.pak` | Contenu adulte privé | Réintégré / validé | Ancien crash post-update corrigé par mise à jour. Menu actif et scènes fonctionnelles. |
| 16 | Panda's Bloody Mess | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723576515) | `3723576515` | `PandasBloodyMess.pak` | Ambiance visuelle | Validé | Ambiance gore. |
| 17 | Nat's Trees Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3731460271) | `3731460271` | `nats_trees_e.pak` | Environnement / végétation | Validé | Placé après Panda's Bloody Mess. Test gameplay validé : aucun crash, aucun freeze. |
| 18 | More Clan Emblems Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723546665) | `3723546665` | `MoreClanEmblemsEnhanced.pak` | Clan / emblèmes | Validé | Personnalisation de clan. |
| 19 | SH - Decorations v1.0.1 Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723606644) | `3723606644` | `SH_Decorations.pak` | Décoration | Réintégré / validé | Ancien crash post-update corrigé par la mise à jour v1.0.1. Testé et validé. |
| 20 | Tanny's WDV Tattoos und Narben - Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723007453) | `3723007453` | `WdV_Tattoo_und_Narben.pak` | Tatouages / cicatrices | Réintégré / validé | Test ingame OK : aucun crash, aucun freeze, fonctionnement confirmé. |
| 21 | Sacred Lust armor set | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721257555) | `3721257555` | `LustGoddessArmor.pak` | Armure / cosmétique | Validé | Armure testée. |
| 22 | Derketo Acolyte Replacer | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720479864) | `3720479864` | `DerketoAcolyteReplacer.pak` | Armure / cosmétique | Validé | Test isolé validé. |
| 23 | Topfreedom Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722359128) | `3722359128` | `Topfreedom.pak` | Apparence | Validé | Mod cosmétique. Placé dans le bloc apparence avant le contenu léger. |
| 24 | CNC - Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720730572) | `3720730572` | `CNC.pak` | Contenu léger | Validé | Intro toujours passable. |
| 25 | HyperBoreanReforged | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722409363) | `3722409363` | `HyperBoreanReforged.pak` | Contenu / équipement | Validé | Placement validé entre CNC et Armor Scraps. |
| 26 | Craftable Armor Scraps - Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723318494) | `3723318494` | `ArmorScrap.pak` | Craft / ressources | Validé | Craft / ressources. |
| 27 | TDI_LegendaryRepair | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723127994) | `3723127994` | `TDI_LegendaryRepair.pak` | Craft / réparation | Validé | Réparation légendaire. |
| 28 | Organizer Sorting Chest | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723101055) | `3723101055` | `SortingBox.pak` | Stockage / tri | Validé | Fonctionne avec Unlock Plus. |
| 29 | Automatic Fish Trap | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720452046) | `3720452046` | `automatic_fish_trap_enhanced.pak` | Ressources | Validé | Automatisation légère. |
| 30 | Player Ignores Follower Collision | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720753923) | `3720753923` | `EnhancedPlayerIgnoresFollowerCollision.pak` | Followers / Coop | Validé | Confort coop. |
| 31 | Enhanced Gliders | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720667122) | `3720667122` | `AdvancedGliders.pak` | Mobilité | Validé | Planeurs. |
| 32 | Archers Are ARCHERS (1.0.1) - Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729895885) | `3729895885` | `Archers_Are_ARCHERS_E.pak` | Combat / gameplay léger | Validé | Placé après Enhanced Gliders et avant DrK Spiders to Scorpions. Test ingame validé. |
| 33 | DrK Spiders to Scorpions | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720692529) | `3720692529` | `DrK_SpidersToScorpions_CEE.pak` | Créatures | Validé | Aucun CTD ni freeze. |
| 34 | LegitReligious | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720748663) | `3720748663` | `LegitReligious_Enhanced.pak` | Religion | Réintégré / validé | Mise à jour Workshop testée et validée. Ancien crash post-update non reproduit. |
| 35 | Diverse Barkeeps | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722887659) | `3722887659` | `DiverseBarkeepers.pak` | PNJ / ambiance | Validé | Ambiance PNJ. |
| 36 | Craftable Legendaries | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721054666) | `3721054666` | `CraftableLegendaries.pak` | Craft / progression | Validé | À surveiller côté équilibrage. |
| 37 | Sorcery Tweaks Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723524908) | `3723524908` | `SorceryTweaksEnhanced.pak` | Sorcellerie | Validé | Sorcellerie. |
| 38 | Dark Decention Cooking and Brewing | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721764383) | `3721764383` | `DarkDecentionCookingandBrewing.pak` | Cuisine / brassage | Validé | Cuisine / brassage. |
| 39 | Level 120 Progression Mod | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722211036) | `3722211036` | `Level120Progression.pak` | Progression / leveling | Validé | Remplace Navi's Revived Leveling Enhanced. Progression utile jusqu'au niveau 120 ; après 120, le PJ continue de monter mais sans points d'attributs ni de savoir. |
| 40 | Exile Architect: Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729398837) | `3729398837` | `RopeLines.pak` | Building léger | Validé | Testé ingame seul puis avec la modlist complète. Fonctionne nickel. |
| 41 | Ancient Architecture | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729634795) | `3729634795` | `Ancient_Architecture.pak` | Building / architecture | Validé | Ajouté, testé et validé. |
| 42 | SH - Building Kit Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3728528172) | `3728528172` | `SH_BuildingKit.pak` | Building | Validé | Ajouté avec SH - Decorations v1.0.1. Testé et validé. |
| 43 | Ancient Civilization - Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721996090) | `3721996090` | `Asghaard_Ancient_Civilization.pak` | Building | Validé | Building. |
| 44 | Desert Town | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721019326) | `3721019326` | `Asghaard_Desert_Town.pak` | Building | Validé | Building. |
| 45 | Wicked Webs of Zamora UE5 | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723048378) | `3723048378` | `WickedWebsofZamora.pak` | Building | Validé | Éléments de construction testés. |
| 46 | Al-Merayah Reborn by Xevyr | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718036277) | `3718036277` | `AlMerayah_Reborn.pak` | Gameplay système / contenu monde | Validé | Testé et validé après update. Placement conseillé : avant The Purge mod. |
| 47 | The Purge mod by Xevyr | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719604490) | `3719604490` | `Retro_Purge.pak` | Gameplay système | Validé | Test fonctionnel contrôlé validé. |
| 48 | Complete Thrall Fashion vE-1.3.5 | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3725384942) | `3725384942` | `CompleteFashion.pak` | Apparence / Thralls / Armures | Validé | Placé avant les mods d'apparence finale. |
| 49 | Adonia Salon | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3731613388) | `3731613388` | `AdoniaSalon.pak` | Apparence / coiffures | Validé | Version actuellement utilisée dans la modlist terrain validée. Remplace l'ancien fichier `AdoniaHairs.pak`. |
| 50 | MSCasaDesFlores - Nails Station [ Enhanced ] | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723318347) | `3723318347` | `MSCasaDesFlores_Nails_Enhanced.pak` | Apparence / cosmétique | Validé | Placé après Adonia Salon et avant High Heels / Devious / Grims Wonderbody. Test ingame validé. |
| 51 | High Heels System 3.2.8 | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3731474693) | `3731474693` | `HighHeels.pak` | Apparence / système cosmétique | Validé | Placé avant Devious Desires et Grims Wonderbody. Test gameplay validé : aucun crash, aucun freeze. |
| 52 | Devious Desires Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3731681816) | `3731681816` | `Devious_Desires.pak` | Gameplay adulte privé / système | Validé | Placé très bas, après High Heels et avant Grims Wonderbody. Test gameplay validé : aucun crash, aucun freeze. |
| 53 | Grims Wonderbody Reupload Enhanced | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3729384808) | `3729384808` | `WonderBody_Enhanced.pak` | Apparence / body féminin | Validé | Remplace Aquilonian Females Enhanced. Conservé en dernier mod d'apparence/body. |

## Mods temporairement en attente de mise à jour post-update

Aucun mod actuellement en attente.

Tous les mods cassés par la mise à jour Conan Enhanced ont été soit réintégrés après mise à jour, soit remplacés par une alternative validée.

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
| Greater Camera Distance UE4 | Remplacé / retiré | Mauvaise version UE4 remplacée par Greater Camera Distance Enhanced, Workshop ID `3729620808`. |
| [Enhanced] More T4 Thralls Plus - v1.0.0 | Rejeté | Crash Unreal / UE-ConanSandbox à l'arrivée ingame. Test de contrôle sans le mod : retour à la stabilité. |
| Katis_Tattoos | Rejeté / différé | Dépendance Tot Custom non retenue pour l'objectif coop. |
| Face It Enhanced | Rejeté / différé | Dépendance Tot Sudo non retenue pour conserver une base coop propre. |
| Pickup+, LBPR et LBPR Additional Features | Différés | Non visibles via filtre Enhanced au moment de la recherche. |

## Notes importantes

### Nat's Trees Enhanced

**Nat's Trees Enhanced** est ajouté comme mod d'environnement / végétation.

Placement validé : après **Panda's Bloody Mess** et avant **More Clan Emblems Enhanced**.

### High Heels System

**High Heels System 3.2.8** est ajouté comme système cosmétique d'apparence.

Placement validé : après **MSCasaDesFlores - Nails Station [ Enhanced ]** et avant **Devious Desires Enhanced**.

### Devious Desires Enhanced

**Devious Desires Enhanced** est ajouté comme mod de gameplay adulte privé / système.

Placement validé : après **High Heels System 3.2.8** et avant **Grims Wonderbody Reupload Enhanced**.

Ce mod reste à surveiller en usage prolongé, car il intervient plus profondément sur le gameplay adulte, les interactions et les personnages que les simples mods cosmétiques.

### Adonia Salon

**Adonia Salon** est désormais référencé avec le Workshop ID `3731613388` et le fichier `.pak` `AdoniaSalon.pak`, conformément à la modlist terrain validée.

L'ancienne référence `3729456480 / AdoniaHairs.pak` est remplacée dans le load order officiel.

### Faster Elevator

**[Enhanced] Faster Elevator v1.0.2** est ajouté comme mod de mobilité / confort de base.

Placement validé : après **Xevyr's Hearthstone** et avant **Primal Instincts Enhanced**.

### Archers Are ARCHERS

**Archers Are ARCHERS (1.0.1) - Enhanced** est ajouté comme mod de combat / gameplay léger.

Placement validé : après **Enhanced Gliders** et avant **DrK Spiders to Scorpions**.

### MSCasaDesFlores - Nails Station

**MSCasaDesFlores - Nails Station [ Enhanced ]** est ajouté comme mod d'apparence / cosmétique.

Placement validé : après **Adonia Salon** et avant **High Heels System / Devious Desires / Grims Wonderbody**.

### Greater Camera Distance Enhanced

**Greater Camera Distance Enhanced** est ajouté comme QoL caméra / confort combat.

Placement validé : sous **Simple Modlist**, dans le bloc Interface & QoL.

La version UE4 précédemment testée a été remplacée par la bonne version Enhanced.

### Ancient Architecture

**Ancient Architecture** est ajouté comme mod de building / architecture.

Placement validé : après **Exile Architect: Enhanced** et avant **SH - Building Kit Enhanced**.

### LegitReligious

**LegitReligious [Enhanced]** est réintégré après mise à jour Workshop.

Ancien crash post-update non reproduit après test.

### Grims Wonderbody Reupload Enhanced

**Grims Wonderbody Reupload Enhanced** remplace **Aquilonian Females Enhanced** comme mod d'apparence / body féminin.

### Exile Architect: Enhanced

**Exile Architect: Enhanced** est ajouté comme mod de construction léger.

Son fichier `.pak` réel est `RopeLines.pak`.

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

Document mis à jour avec les **53 mods listés et chargeables**.
