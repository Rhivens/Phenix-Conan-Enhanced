# 11 - Installation joueurs

## Objectif

Ce document explique comment installer le modpack Conan Exiles Enhanced / UE5 côté joueur.

Il est destiné aux amis qui veulent rejoindre la partie sans devoir gérer toute la partie technique du projet.

Objectifs :

- installer les bons mods ;
- respecter le bon ordre de chargement ;
- éviter les erreurs de connexion ;
- pouvoir rejoindre la partie hébergée par Fabien.

## Important avant de commencer

Le modpack est prévu pour **Conan Exiles Enhanced / UE5**.

Chaque joueur devra avoir :

- Conan Exiles installé via Steam ;
- le jeu lancé au moins une fois sans mod ;
- les mêmes mods que l'hôte ;
- le même ordre de chargement des mods.

Si les mods ne sont pas identiques, ou pas dans le même ordre, la connexion à la partie peut échouer.

## Source des mods

La modlist actuelle utilise uniquement des mods du **Steam Workshop**.

Aucun téléchargement externe n'est nécessaire pour la version actuelle du modpack.

Une collection Steam Workshop officielle permet de s'abonner plus facilement aux mods :

➡️ **[Collection Steam Workshop - Phénix Conan Enhanced](https://steamcommunity.com/sharedfiles/filedetails/?id=3726259113)**

Les joueurs doivent donc :

- s'abonner aux mods via la collection Steam Workshop officielle ;
- vérifier ensuite que les mods correspondent bien à la modlist de référence ;
- ne pas ajouter de mod personnel ;
- ne pas installer d'ancien fichier `.pak` provenant d'une autre modlist ;
- ne pas modifier l'ordre de chargement.

## Étape 1 - Lancer Conan Exiles Enhanced une première fois

Avant d'installer les mods, lancer le jeu une première fois sans mod.

But :

- vérifier que le jeu démarre correctement ;
- laisser le jeu créer ses dossiers de configuration ;
- éviter de confondre un problème vanilla avec un problème de mod.

Une fois le menu principal atteint, quitter le jeu.

## Étape 2 - S'abonner aux mods Steam Workshop listés

Tous les mods de la version actuelle du modpack sont pris depuis le Steam Workshop.

### Méthode recommandée : collection Steam Workshop

Ouvrir la collection officielle :

➡️ **[Collection Steam Workshop - Phénix Conan Enhanced](https://steamcommunity.com/sharedfiles/filedetails/?id=3726259113)**

Puis s'abonner aux mods de la collection.

### Vérification manuelle

La liste officielle des mods, avec les liens Steam Workshop et l'ordre de chargement, se trouve ici :

```text
docs/12_modlist_reference.md
```

Lien direct dans le dépôt : [12 - Modlist de référence et load order](12_modlist_reference.md)

Pour chaque mod Workshop si une vérification manuelle est nécessaire :

1. ouvrir le lien Steam Workshop fourni dans la liste du modpack ;
2. cliquer sur **S'abonner** ;
3. laisser Steam télécharger le mod ;
4. attendre que tous les téléchargements soient terminés.

Ne pas lancer la partie tant que Steam télécharge encore des mods.

## Étape 3 - Activer les mods dans le menu Mods du jeu

Pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop.

La méthode de référence est donc le menu Mods directement en jeu.

Procédure :

1. lancer Conan Exiles Enhanced ;
2. ouvrir le menu **Mods** depuis le jeu ;
3. vérifier que les mods abonnés apparaissent bien ;
4. activer les mods nécessaires ;
5. respecter l'ordre officiel indiqué dans `docs/12_modlist_reference.md` ;
6. redémarrer le jeu si Conan le demande.

## Étape 4 - Vérifier ou remplacer le fichier modlist.txt

Conan utilise un fichier appelé `modlist.txt` pour savoir quels mods charger et dans quel ordre.

Ce fichier se trouve normalement ici :

```text
<SteamLibrary>\steamapps\common\Conan Exiles\ConanSandbox\Mods\modlist.txt
```

La documentation du modpack fournit une version de référence du fichier `modlist.txt` via le load order officiel.

Chaque joueur devra vérifier que son fichier correspond bien à la version indiquée.

Attention :

- l'ordre des lignes est important ;
- ne pas ajouter de mods personnels ;
- ne pas supprimer de ligne ;
- ne pas modifier le fichier au hasard.

## Étape 5 - Relancer le jeu

Une fois les mods installés et le fichier `modlist.txt` vérifié :

1. relancer Conan Exiles Enhanced ;
2. laisser le jeu charger les mods ;
3. vérifier qu'aucun message d'erreur bloquant n'apparaît ;
4. arriver au menu principal.

Si le jeu demande un redémarrage après activation des mods, accepter et relancer.

## Étape 6 - Rejoindre la partie

Quand tout est prêt :

1. lancer Conan Exiles Enhanced ;
2. aller dans le menu multijoueur ou coop selon la méthode utilisée ;
3. rejoindre la partie hébergée par Fabien ;
4. signaler immédiatement toute erreur de connexion ou tout message de mod manquant.

## En cas de problème

Vérifier dans cet ordre :

1. Steam a-t-il fini de télécharger tous les mods ?
2. Le joueur est-il bien abonné à tous les mods Workshop listés ?
3. Les mods apparaissent-ils bien dans le menu Mods du jeu ?
4. Le fichier `modlist.txt` correspond-il à la version de référence ?
5. L'ordre des mods est-il identique ?
6. Le jeu a-t-il été relancé après installation / activation des mods ?
7. Aucun ancien mod personnel ne traîne-t-il dans le dossier `ConanSandbox\Mods` ?

## Règle simple pour les joueurs

- Utiliser la collection Steam Workshop officielle.
- Ne pas ajouter de mods personnels.
- Ne pas modifier l'ordre de chargement.
- Ne pas renommer les fichiers.
- Ne pas supprimer de ligne dans `modlist.txt`.
- En cas de doute, demander avant de modifier quelque chose.

## Statut

Document mis à jour avec le lien actuel de la collection Steam Workshop officielle.
