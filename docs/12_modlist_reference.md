# 12 - Modlist de référence et load order

## Objectif

Ce document sert de référence officielle pour la liste des mods du modpack Conan Exiles Enhanced / UE5.

Il doit permettre à Fabien et aux joueurs de vérifier :

- les mods utilisés ;
- leur source ;
- leur lien direct ;
- leur Workshop ID ;
- leur catégorie ;
- leur statut ;
- leur ordre de chargement.

## Règle générale

Tous les joueurs devront utiliser :

- les mêmes mods ;
- les mêmes versions autant que possible ;
- le même ordre de chargement ;
- aucun mod personnel supplémentaire.

Un écart dans la liste ou l'ordre des mods peut empêcher de rejoindre la partie.

## Logique générale du load order

Ordre de principe retenu pour le modpack :

1. Frameworks / librairies / dépendances
2. Interface & QoL
3. Stack / inventaire / confort système
4. Building / construction
5. Décoration / placeables
6. Gameplay léger
7. Thralls / compagnons / animaux
8. Cosmétiques / armures / vêtements
9. Ambiance visuelle / météo / lumière
10. Administration / host local

Cette logique pourra être ajustée selon les recommandations propres à certains mods.

## Load order officiel actuel

| Ordre | Mod | Source | Lien | ID / Référence | Catégorie | Statut | Notes |
|---:|---|---|---|---|---|---|---|
| 1 | Simple Minimap (by Xevyr) v5.1.1 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719513784) | `3719513784` | Interface & QoL | Validé | Visible dans le menu Mods en jeu, pas forcément dans le launcher Funcom. |
| 2 | Stacksize Plus v2.0.0-enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720915336) | `3720915336` | Interface & QoL / Inventaire | Validé | Réglage via menu radial d'un objet avec inventaire. Réglage conseillé : x5. |

## modlist.txt de référence

À ce stade, le fichier `modlist.txt` devra refléter l'ordre officiel ci-dessus.

La forme exacte du fichier sera documentée lorsque la liste commencera à se stabiliser.

## Notes importantes

### Liens directs

La colonne **Lien** doit être utilisée par les joueurs pour s'abonner aux bons mods.

Cette méthode limite les erreurs de recherche Steam Workshop, notamment les confusions entre versions Legacy, anciennes versions UE4 et versions Enhanced / UE5.

### Menu Mods en jeu

Pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop.

Méthode de vérification retenue :

1. vérifier l'abonnement Steam Workshop ;
2. vérifier que le fichier `.pak` existe dans le dossier Workshop Steam ;
3. lancer le jeu ;
4. ouvrir le menu Mods depuis le jeu ;
5. activer les mods depuis ce menu ;
6. respecter le load order officiel ;
7. redémarrer si le jeu le demande ;
8. tester en host local solo.

### Installation joueurs

Les joueurs devront se référer au fichier suivant :

```text
docs/11_installation_joueurs.md
```

## Statut

Document initial créé avec les deux premiers mods validés.
