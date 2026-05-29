# Addendum - Modlist de référence à 59 mods

## Étape validée : lot QoL / armures / building sans Shimas

Statut : **validé**.

Contexte : Fabien a testé un lot de 7 mods candidats pour le modpack **Conan Exiles Enhanced / UE5**.

Résultat final :

- **5 mods retenus et validés** ;
- **1 mod fonctionnel mais non retenu** ;
- **1 mod rejeté / différé pour crash au chargement**.

## Mods retenus et validés

### Auto Resource Markers v1.0.1

- Workshop ID : `3732246591` ;
- fichier `.pak` : `AutoResourceMarkers.pak` ;
- catégorie : Interface / QoL / repérage ressources ;
- placement validé : après **Lore & Loot Highlight** et avant **Twin-Bar**.

Placement :

```text
3 - Lore & Loot Highlight / LLHighlight.pak
4 - Auto Resource Markers v1.0.1 / AutoResourceMarkers.pak
5 - Twin-Bar / TwinBar.pak
```

### BetterTorch 1.0.3

- Workshop ID : `3733531323` ;
- fichier `.pak` constaté dans la modlist terrain : `AliskoUI.pak` ;
- catégorie : QoL / lumière / confort ;
- placement validé : après **Faster Elevator** et avant **Primal Instincts Enhanced**.

Placement :

```text
15 - Faster Elevator / FasterElevator.pak
16 - BetterTorch 1.0.3 / AliskoUI.pak
17 - Primal Instincts Enhanced / PrimalInstincts.pak
```

Note : le nom du fichier `.pak` ne correspond pas au nom visible du mod Workshop. La référence terrain officielle reste donc le couple `3733531323 / AliskoUI.pak`.

### SkimpyArmors(2026)-Enhanced-Bbversion

- Workshop ID : `3733079879` ;
- fichier `.pak` : `Skimpy_a2026.pak` ;
- catégorie : Apparence / armures ;
- placement validé : après **Loincloth visible and craftable** et avant **MSCasaDesFlores - Weapons & Armors [ Enhanced ]**.

Placement :

```text
26 - Loincloth visible and craftable / Loincloth.pak
27 - SkimpyArmors(2026)-Enhanced-Bbversion / Skimpy_a2026.pak
28 - MSCasaDesFlores - Weapons & Armors [ Enhanced ] / MSCasaDesFlores_Weapons_Enhanced.pak
```

### MSCasaDesFlores - Weapons & Armors [ Enhanced ]

- Workshop ID : `3734522624` ;
- fichier `.pak` : `MSCasaDesFlores_Weapons_Enhanced.pak` ;
- catégorie : Armes / armures / apparence ;
- placement validé : après **SkimpyArmors(2026)-Enhanced-Bbversion** et avant **CNC - Enhanced**.

Placement :

```text
27 - SkimpyArmors(2026)-Enhanced-Bbversion / Skimpy_a2026.pak
28 - MSCasaDesFlores - Weapons & Armors [ Enhanced ] / MSCasaDesFlores_Weapons_Enhanced.pak
29 - CNC - Enhanced / CNC.pak
```

### Stygian Ruins

- Workshop ID : `3729583604` ;
- fichier `.pak` : `Stygian_Pieces.pak` ;
- catégorie : Building pieces / architecture ;
- placement validé : sous **Wicked Webs of Zamora UE5** et avant **Al-Merayah Reborn by Xevyr**.

Placement :

```text
50 - Wicked Webs of Zamora UE5 / WickedWebsofZamora.pak
51 - Stygian Ruins / Stygian_Pieces.pak
52 - Al-Merayah Reborn by Xevyr / AlMerayah_Reborn.pak
```

## Mod fonctionnel mais non retenu

### RR - Ripped & Revealed: Coarse Set

- Workshop ID : `3732939416` ;
- statut : **non retenu** ;
- raison : le mod fonctionne, mais son intérêt est jugé trop limité car il ne modifie qu'une seule tenue du début.

Décision : ne pas intégrer au modpack officiel.

## Mod rejeté / différé

### (Enhanced) Shimas Compendium 1.1.76

- Workshop ID : `3730112715` ;
- statut : **rejeté / différé** ;
- raison : crash du jeu au chargement d'une partie en cours ;
- test de contrôle : après retrait de Shimas, le jeu fonctionne correctement.

Décision : ne pas intégrer au modpack coop local à ce stade.

## Statut officiel après validation

La base active passe de **54 mods validés** à **59 mods validés**.

```text
Base CONAN Enhanced / UE5 : 59 mods validés
Mods ajoutés : 5
Mods non retenus : 1
Mods rejetés / différés : 1
Crash après retrait de Shimas : aucun signalé
Freeze après retrait de Shimas : aucun signalé
Statut : validé par Fabien
```

## Extrait de la modlist terrain validée

```text
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718655125/LLHighlight.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3732246591/AutoResourceMarkers.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719621216/TwinBar.pak

*C:\JEUX\STEAM\steamapps\workshop\content\440900\3729885653/FasterElevator.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3733531323/AliskoUI.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723050568/PrimalInstincts.pak

*C:\JEUX\STEAM\steamapps\workshop\content\440900\3722359128/Topfreedom.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3730004282/Loincloth.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3733079879/Skimpy_a2026.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3734522624/MSCasaDesFlores_Weapons_Enhanced.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3720730572/CNC.pak

*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723048378/WickedWebsofZamora.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3729583604/Stygian_Pieces.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718036277/AlMerayah_Reborn.pak
```
