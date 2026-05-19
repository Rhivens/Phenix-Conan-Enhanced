# 15 - Addendum modlist : Level 120 et Al-Merayah

## Objectif

Documenter les deux changements validés après la phase de maintenance post-update Conan Enhanced.

Cet addendum complète temporairement `docs/12_modlist_reference.md`.

## Changements validés

### Remplacement de Navi's Revived Leveling Enhanced

**Navi's Revived Leveling Enhanced** est retiré de la modlist active.

Raison : le mod provoquait un crash au lancement avant le menu après la mise à jour Conan Enhanced.

Il est remplacé par :

- **Level 120 Progression Mod (Max Knowledge and Attribute Points)**
- Workshop ID : `3722211036`
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3722211036
- Catégorie : progression / leveling
- Statut : **validé**

### Résultat du test Level 120

Le mod est validé à 100 % pour le modpack.

Comportement constaté :

- progression utile jusqu'au niveau 120 ;
- le personnage peut continuer à gagner des niveaux après 120 ;
- après le niveau 120, il ne reçoit plus de points d'attributs ;
- après le niveau 120, il ne reçoit plus de points de savoir.

Ce comportement est accepté pour le modpack, car il évite une distribution infinie de points.

Placement conseillé : exactement à l'ancien emplacement de `NRLe.pak`, entre :

```text
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721764383/DarkDecentionCookingandBrewing.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3722211036/[nom_du_pak_Level120_a_confirmer].pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3721996090/Asghaard_Ancient_Civilization.pak
```

Le nom exact du `.pak` devra être confirmé depuis le prochain `modlist.txt` réel.

## Ajout validé : Al-Merayah Reborn

Ajout de :

- **Al-Merayah Reborn (by Xevyr) v5.0.2**
- Workshop ID : `3718036277`
- Lien : https://steamcommunity.com/sharedfiles/filedetails/?id=3718036277
- Catégorie : gameplay système / contenu monde
- Statut : **validé**

### Résultat du test Al-Merayah

Le mod a été testé après la mise à jour Conan Enhanced.

Résultat :

- lancement OK ;
- test ingame OK ;
- déplacement / téléportation vers la zone concernée OK ;
- fonctionnement jugé nickel.

Placement conseillé : avant **The Purge mod by Xevyr**, dans la zone gameplay système / contenu monde.

```text
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3723048378/WickedWebsofZamora.pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3718036277/[nom_du_pak_AlMerayah_a_confirmer].pak
*C:\JEUX\STEAM\steamapps\workshop\content\440900\3719604490/Retro_Purge.pak
```

Le nom exact du `.pak` devra être confirmé depuis le prochain `modlist.txt` réel.

## État de référence après ces changements

La référence complète passe à **42 mods listés** :

- 41 anciens emplacements ;
- `NRLe.pak` remplacé par **Level 120 Progression Mod** ;
- ajout de **Al-Merayah Reborn** avant **The Purge mod**.

Les 4 mods suivants restent dans la référence mais sont en attente de mise à jour avant réintégration dans le `modlist.txt` actif :

- `PrimalInstincts.pak` ;
- `SH_Decorations.pak` ;
- `WdV_Tattoo_und_Narben.pak` ;
- `LegitReligious_Enhanced.pak`.

## Statut

Addendum validé. À intégrer ensuite directement dans `docs/12_modlist_reference.md` lorsque les noms exacts des nouveaux `.pak` auront été confirmés par un nouveau `modlist.txt` réel.
