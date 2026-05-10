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
11. NSFW / contenu adulte

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
| 8 | Inventory Compactor v5.0.1 by Xevyr | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718614759) | `3718614759` | Interface & QoL / Inventaire | Validé | Bouton d'inventaire et menu radial sur conteneurs / stations. | Compactage d'inventaire, restack et rangement des espaces vides. |
| 9 | Unlock Plus v2.0.1-enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720948133) | `3720948133` | Interface & QoL / Stockage | Validé | Menu accessible depuis l'inventaire du personnage / options propres au mod. | Mod structurant pour stockage et transferts, à surveiller en multijoueur. |
| 10 | Follower Remote v5.0.3 by Xevyr | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3718523921) | `3718523921` | Gameplay / Thralls / Compagnons | Validé | Console : `dc frsettings` ou interface de réglages Xevyr disponible. | Gestion à distance du comportement des followers et thralls. |
| 11 | Xevyr's Hearthstone v5.0.0 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3719642461) | `3719642461` | Gameplay léger / Mobilité | Validé | Cooldown admin : `dc hscooldown x`. | Pierre de retour liée au lit, confort coop à surveiller selon l'équilibre souhaité. |
| 12 | Primal Instinct | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723050568) | `3723050568` | NSFW / Contenu adulte | Validé | Fonctionnement et accès aux options identifiés après prise en main en jeu. | Premier mod NSFW validé. Nudité totale activée par défaut dans le cadre du modpack. |
| 13 | Panda's Bloody Mess | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723576515) | `3723576515` | Visuel / Ambiance gore | Validé | Pas de réglage spécifique identifié pour le moment. | Validé dans le pack 10.8. |
| 14 | More Clan Emblems Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723546665) | `3723546665` | Clan / Emblèmes / Personnalisation | Validé | Via les options de clan / emblèmes du jeu. | Validé dans le pack 10.8. |
| 15 | SH - Decorations v1.0.0 (Enhanced) | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723606644) | `3723606644` | Décoration / Placeables | Validé | Objets déco craftables / spawnables selon le mod. | Objets déco testés ingame. |
| 16 | Topfreedom Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722359128) | `3722359128` | Cosmétique / NSFW léger / Apparence | Validé | Effet cosmétique lié à l'apparence / nudité selon les réglages du jeu et du mod. | Validé en mode Coop dans le pack 10.9. |
| 17 | Tanny's WDV Tattoos und Narben - Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723007453) | `3723007453` | Cosmétique / Tatouages / Cicatrices | Validé | Tatouages / cicatrices accessibles en jeu selon l'interface du mod. | Validé en mode Coop dans le pack 10.9. |
| 18 | Sacred Lust armor set | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721257555) | `3721257555` | Armure / Cosmétique / NSFW léger | Validé | Armure craftable / spawnable selon le mod ; compatibilité Fashionist à surveiller. | Validé en mode Coop dans le pack 10.9. |
| 19 | Craftable Armor Scraps - Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723318494) | `3723318494` | Craft / Ressources | Validé | Recettes / craft accessibles selon le mod. | Validé en mode Coop dans le pack 10.10. |
| 20 | TDI_LegendaryRepair [Enhanced] | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723127994) | `3723127994` | Craft / Réparation | Validé | Recette ou méthode de réparation légendaire propre au mod. | Validé en mode Coop dans le pack 10.10. |
| 21 | Organizer Sorting Chest v1.0.0 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723101055) | `3723101055` | Interface & QoL / Stockage / Tri | Validé | Coffre de tri / fonctionnement propre au mod. | Fonctionne nickel avec Unlock Plus déjà présent. |
| 22 | Automatic Fish Trap v1.0.3 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720452046) | `3720452046` | Gameplay léger / Ressources | Validé | Piège à poisson automatique selon le fonctionnement du mod. | Validé en mode Coop dans le pack 10.10. |
| 23 | [Enhanced] Player Ignores Follower Collision | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720753923) | `3720753923` | Gameplay léger / Followers / Coop | Validé | Pas de réglage spécifique identifié pour le moment. | Validé en mode Coop dans le pack 10.11. |
| 24 | Enhanced Gliders | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720667122) | `3720667122` | Gameplay léger / Mobilité | Validé | Planeurs / options selon le fonctionnement du mod. | Validé en mode Coop dans le pack 10.11. |
| 25 | LegitReligious [Enhanced] | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720748663) | `3720748663` | Gameplay léger / Religion | Validé | Effets / recettes / religions selon le mod. | Stable en test Coop, à surveiller en usage prolongé. |
| 26 | Diverse Barkeeps | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3722887659) | `3722887659` | Ambiance NPC / Barkeeps | Validé | Fonctionnement passif / variations NPC selon le mod. | Validé en mode Coop dans le pack 10.11. |
| 27 | [Enhanced] Craftable Legendaries | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721054666) | `3721054666` | Craft / Progression / Équipement légendaire | Validé | Recettes / craft légendaire selon le mod. | Stable et fluide en test Coop, à surveiller côté équilibrage. |
| 28 | Sorcery Tweaks Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723524908) | `3723524908` | Sorcellerie / Gameplay léger | Validé | Ajustements sorcellerie selon le mod. | Validé en mode Coop dans le pack 10.12. |
| 29 | [Enhanced] Dark Decention Cooking and Brewing | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721764383) | `3721764383` | Cuisine / Brassage / Recettes | Validé | Recettes cuisine / brassage selon le mod. | Stable et fluide en test Coop, aucune erreur. |
| 30 | Ancient Civilization - Enhanced | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721996090) | `3721996090` | Building / Décoration avancée | Validé | Pièces / objets de construction selon le mod. | Validé en mode Coop dans le pack 10.13. |
| 31 | Desert Town | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3721019326) | `3721019326` | Building / Décoration avancée | Validé | Pièces / objets de construction selon le mod. | Validé en mode Coop dans le pack 10.13. |
| 32 | Enhanced Builder 2026.5.9 | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3720763208) | `3720763208` | Building / Construction avancée | Validé | Sets de construction via le système de build / marteau. | Validé en mode Coop ; intro non passable au clic souris, anomalie mineure non bloquante. |

## Mods rejetés définitivement

| Mod | Source | Lien | ID / Référence | Ancien ordre | Statut | Raison |
|---|---|---|---|---:|---|---|
| Lisas Building Stone Age | Steam Workshop | [Ouvrir](https://steamcommunity.com/sharedfiles/filedetails/?id=3723560519) | `3723560519` | 16 | Rejeté | Mod affiché comme `<corrupted - Lisas_Building_Stone_Age.pak>`, erreur `failed to parse mod info`, version bêta instable récemment mise à jour. |

## Mods rejetés / différés après test

| Mod | Source | Lien | ID / Référence | Ancien ordre | Statut | Raison |
|---|---|---|---|---:|---|---|
| The Compendium of Crawling Chaos Enhanced Edition | Steam Workshop | À compléter | À compléter | 29 provisoire | Rejeté / différé | Test isolé après la base stable de 32 mods : freeze complet du PC, clavier inopérant, `CTRL + ALT + SUPPR` sans réponse, reset physique nécessaire. Retrait confirmé, retour stabilité OK. |

## modlist.txt de référence

À ce stade, le fichier `modlist.txt` devra refléter l'ordre officiel ci-dessus.

La base actuelle validée contient **32 mods actifs**.

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

### Compatibilité coop

Les tests de Fabien sont effectués directement en **mode Coop**, ce qui est plus représentatif de l'utilisation réelle prévue pour le modpack.

Les mods nécessitant des dépendances non compatibles coop sont rejetés ou différés.

### Contenu NSFW

Le modpack est destiné à une partie privée entre adultes.

La nudité totale est activée par défaut, et les mods NSFW doivent être installés et testés avec prudence.

Les joueurs doivent être informés du contenu adulte avant installation.

### Anomalies mineures non bloquantes

Après validation du pack 10.13, l'intro du jeu ne peut plus être passée au clic souris.

Cette anomalie est considérée comme non bloquante à ce stade :

- le jeu reste stable ;
- aucune erreur n'est signalée ;
- le gameplay n'est pas compromis ;
- les pièces de construction testées fonctionnent correctement.

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
8. tester en mode Coop / host local.

### Installation joueurs

Les joueurs devront se référer au fichier suivant :

```text
docs/11_installation_joueurs.md
```

## Statut

Document mis à jour avec les trente-deux mods actifs actuellement validés, et les rejets/différés connus après test.
