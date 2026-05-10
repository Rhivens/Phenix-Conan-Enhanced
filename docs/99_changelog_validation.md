# 99 - Changelog de validation

## Étape 1 - Base propre préparée

Statut : **validée**.

Résumé :

- anciens abonnements Workshop Conan Exiles supprimés ;
- base vanilla UE5 propre préparée ;
- ReShade non réinstallé ;
- ancien fichier Better Graphics UE4 non repris tel quel.

## Étape 2 - Analyse de l'ancienne modlist UE4

Statut : **validée**.

Résumé :

- ancienne modlist UE4 analysée ;
- philosophie générale jugée utile ;
- reprise directe refusée ;
- reconstruction propre décidée pour Enhanced / UE5.

## Étape 3 - Test de base vanilla UE5

Statut : **validée**.

Résumé :

- jeu lancé correctement ;
- base propre fonctionnelle.

## Étape 4 - Réglages graphiques testés

Statut : **validée**.

Résumé :

- Ultra ;
- DLSS Qualité ;
- Frame Generation activée ;
- Nvidia Reflex activé ;
- Lumen Ultra ;
- gamma ajusté à 1.8.

## Étape 5 - Test visuel en jeu

Statut : **validée**.

Résumé :

- jeu fluide ;
- netteté correcte ;
- ombres satisfaisantes ;
- végétation au loin correcte ;
- ReShade non nécessaire pour le moment.

## Étape 6 - Test performances

Statut : **validée**.

Résumé :

- 90 FPS capés volontairement ;
- aucun ralentissement ;
- aucun stutter ;
- températures normales.

## Étape 7 - Test host local solo

Statut : **validée**.

Résumé :

- environ 30 minutes en host local solo ;
- aucun problème constaté.

## Étape 8 - Test multijoueur réel

Statut : **différée, non bloquante**.

Résumé :

- test impossible actuellement faute de joueur disponible ;
- historique d'hébergement solide ;
- connexion Free 8 Gb/s stable ;
- sessions multi/coop déjà montées jusqu'à 7 joueurs sur Windrose ;
- objectif Conan : 3 à 4 joueurs ;
- test à refaire avant validation finale du modpack.

## Étape 9 - Architecture du modpack

Statut : **validée**.

Résumé :

- structure documentaire et catégories de mods validées ;
- dépôt GitHub créé ;
- documentation initiale mise en place.

## Étape 10.1 - Interface & QoL : Simple Minimap

Statut : **validée**.

Mod : **Simple Minimap (by Xevyr) v5.1.1**.

Résumé :

- abonnement Steam Workshop effectué ;
- fichier `.pak` confirmé dans le dossier Workshop `440900/3719513784` ;
- mod non visible dans l'onglet Mods du launcher Funcom ;
- mod visible dans le menu Mods directement en jeu ;
- mod activé depuis le menu Mods en jeu ;
- minimap fonctionnelle ingame.

Décision :

- Simple Minimap est validé comme premier mod Interface & QoL ;
- pour la suite, le menu Mods en jeu devient la référence principale de vérification, car le launcher Funcom peut ne pas afficher certains mods Workshop.

## Étape 10.2 - Interface & QoL : Stacksize Plus

Statut : **validée**.

Mod : **Stacksize Plus v2.0.0-enhanced**.

Résumé :

- abonnement Steam Workshop effectué ;
- mod activé depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- panneau administrateur utilisé pour accélérer le test ;
- configuration testée via un objet avec inventaire / menu radial ;
- fonctionnement validé ingame.

Décision :

- Stacksize Plus est validé comme second mod Interface & QoL ;
- réglage conseillé au départ : `x5` ;
- le réglage ne se fait pas depuis le panneau administrateur classique, mais via le menu radial d'un objet avec inventaire.
