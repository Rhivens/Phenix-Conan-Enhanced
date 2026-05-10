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
- leur ordre de chargement ;
- leur méthode d'accès aux réglages.

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

| Ordre | Mod | Source | Lien | ID / Référence | Catégorie | Statut | Configuration / réglages | Notes |
|---:|---|---|---|---|---|---|---|---|
| 1 | Simple Minimap (by Xevyr) v5.1.1 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719513784) | `3719513784` | Interface & QoL | Validé | À vérifier en jeu dans les options du mod / paramètres disponibles. | Visible dans le menu Mods en jeu, pas forcément dans le launcher Funcom. |
| 2 | Stacksize Plus v2.0.0-enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720915336) | `3720915336` | Interface & QoL / Inventaire | Validé | Menu radial sur un objet avec inventaire, par exemple coffre ou station de craft. Réglage conseillé : `x5`. | Ne se règle pas depuis le panneau administrateur classique. |
| 3 | Lore & Loot Highlight v1.0.0 by Xevyr | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718655125) | `3718655125` | Interface & QoL / Repérage visuel | Validé | Console : `dc LLHSettings`. | Mise en évidence d'objets interactifs, lore et loot. |
| 4 | Twin-Bar v5.0.4 by Xevyr | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719621216) | `3719621216` | Interface & QoL / Hotbar | Validé | Raccourcis clavier / paramètres de touches. Bascule via les raccourcis du mod. | Barre rapide avec emplacements secondaires. Fonctionnement validé en jeu. |
| 5 | Simple Modlist v5.0.1 by Xevyr | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719546290) | `3719546290` | Interface & QoL / Information modlist | Validé | Consultation depuis le menu en jeu / écran Échap selon l'interface du mod. | Permet de consulter plus facilement la liste des mods actifs. |
| 6 | Fashionist v5.0.2-enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720921242) | `3720921242` | Cosmétique / Armures / Apparence | Validé | Interface propre au mod / options Fashionist en jeu. | Gestion de l'apparence des armures, armes et options visuelles du personnage. |
| 7 | Better Thralls v3.0.0-enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720904511) | `3720904511` | Gameplay / Thralls / Compagnons | Validé | Interface / options propres au mod en jeu. | Mod plus sensible : éviter d'ajouter immédiatement d'autres mods lourds sur les followers. |

## modlist.txt de référence

À ce stade, le fichier `modlist.txt` devra refléter l'ordre officiel ci-dessus.

La forme exacte du fichier sera documentée lorsque la liste commencera à se stabiliser.

## Notes importantes

### Liens directs

La colonne **Lien** doit être utilisée par les joueurs pour s'abonner aux bons mods.

Cette méthode limite les erreurs de recherche Steam Workshop, notamment les confusions entre versions Legacy, anciennes versions UE4 et versions Enhanced / UE5.

### Configuration des mods

Conan Exiles Enhanced / UE5 ne dispose pas actuellement d'une interface centrale comparable au MCM de Skyrim pour regrouper tous les réglages des mods.

Chaque mod peut utiliser une méthode différente :

- options en jeu ;
- menu radial ;
- commande console ;
- raccourcis clavier ;
- paramètres propres au mod.

La colonne **Configuration / réglages** sert donc de référence rapide pour savoir où chercher les options de chaque mod.

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

Document mis à jour avec les sept premiers mods validés.
