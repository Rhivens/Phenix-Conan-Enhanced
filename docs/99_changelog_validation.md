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

## Étape 10.3 - Interface & QoL : mini-lot Lore & Loot Highlight + Twin-Bar

Statut : **validée**.

Mods :

- **Lore & Loot Highlight v1.0.0 by Xevyr** ;
- **Twin-Bar v5.0.4 by Xevyr**.

Résumé :

- abonnements Steam Workshop effectués ;
- mods activés depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- Lore & Loot Highlight validé ingame ;
- Twin-Bar validé ingame après prise en main / réglage ;
- aucun problème bloquant signalé.

Décision :

- Lore & Loot Highlight est validé comme troisième mod Interface & QoL ;
- Twin-Bar est validé comme quatrième mod Interface & QoL ;
- les tests par mini-lots sont acceptés pour les petits mods QoL simples.

## Étape 10.4 - Interface & QoL : Simple Modlist

Statut : **validée**.

Mod : **Simple Modlist v5.0.1 by Xevyr**.

Résumé :

- abonnement Steam Workshop effectué ;
- mod activé depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- fonctionnement validé ingame.

Décision :

- Simple Modlist est validé comme cinquième mod Interface & QoL ;
- ce mod est utile pour consulter plus facilement la liste des mods actifs en jeu ;
- il aidera les joueurs à vérifier leur installation et facilitera les diagnostics en cas d'erreur de modlist.

## Étape 10.5 - Pack Fashionist + Better Thralls

Statut : **validée**.

Mods :

- **Fashionist v5.0.2-enhanced** ;
- **Better Thralls v3.0.0-enhanced**.

Résumé :

- abonnements Steam Workshop effectués ;
- mods activés depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- Fashionist validé ingame ;
- Better Thralls validé ingame ;
- aucun problème bloquant signalé.

Décision :

- Fashionist est validé comme premier mod du bloc Cosmétiques, Armures & Vêtements ;
- Better Thralls est validé comme premier mod du bloc Gameplay, Thralls & Animaux ;
- Better Thralls touche à des systèmes plus sensibles, donc éviter d'ajouter immédiatement d'autres mods lourds sur les followers tant que la stabilité n'est pas mieux éprouvée.

## Étape 10.6 - Pack QoL avancé

Statut : **validée**.

Mods :

- **Inventory Compactor v5.0.1 by Xevyr** ;
- **Unlock Plus v2.0.1-enhanced** ;
- **Follower Remote v5.0.3 by Xevyr** ;
- **Xevyr's Hearthstone v5.0.0**.

Résumé :

- abonnements Steam Workshop effectués ;
- mods activés depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- Inventory Compactor validé ingame ;
- Unlock Plus validé ingame ;
- Follower Remote validé ingame ;
- Xevyr's Hearthstone validé ingame ;
- aucun problème bloquant signalé.

Décision :

- Inventory Compactor et Unlock Plus complètent le bloc Interface & QoL / inventaire / stockage ;
- Follower Remote complète le bloc Gameplay, Thralls & Animaux ;
- Xevyr's Hearthstone est validé comme mod de confort gameplay / mobilité ;
- Unlock Plus et les mods followers devront être surveillés lors des futurs tests multijoueur.

## Étape 10.7 - NSFW : Primal Instinct

Statut : **validée**.

Mod : **Primal Instinct**.

Résumé :

- bon lien Workshop confirmé par Fabien ;
- Workshop ID officiel retenu : `3723050568` ;
- abonnement Steam Workshop effectué ;
- mod activé depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- fonctionnement validé ingame après prise en main du mod ;
- aucun problème bloquant signalé.

Décision :

- Primal Instinct est validé comme premier mod NSFW du modpack ;
- la nudité totale reste activée par défaut dans le cadre du modpack ;
- le mod demande une prise en main spécifique et ne se présente pas comme un simple menu de réglages classique ;
- les futurs mods NSFW devront être testés avec prudence, idéalement un par un ou en très petit lot.

## Étape 10.8 - Pack visuel / déco / building léger

Statut : **validée**.

Mods :

- **Panda's Bloody Mess** ;
- **More Clan Emblems Enhanced** ;
- **SH - Decorations v1.0.0 (Enhanced)** ;
- **Lisas Building Stone Age**.

Résumé :

- abonnements Steam Workshop effectués ;
- mods activés depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- effets visuels / emblèmes / décorations / builds testés ;
- test OK ;
- builds OK ;
- aucun problème bloquant signalé.

Décision :

- Panda's Bloody Mess est validé comme mod visuel / ambiance gore ;
- More Clan Emblems Enhanced est validé comme mod de personnalisation de clan ;
- SH - Decorations est validé comme mod de décoration ;
- Lisas Building Stone Age est validé comme mod de building / construction ;
- Pickup+, Less Building Placement Restrictions et LBPR Additional Features restent différés car non visibles via le filtre Workshop Enhanced au moment de la recherche.

## Étape 10.9 - Pack apparence / cosmétique / NSFW léger

Statut : **validée**.

Mods :

- **Topfreedom Enhanced** ;
- **Tanny's WDV Tattoos und Narben - Enhanced** ;
- **Sacred Lust armor set**.

Résumé :

- abonnements Steam Workshop effectués ;
- mods activés depuis le menu Mods en jeu ;
- test réalisé directement en mode Coop ;
- Topfreedom Enhanced validé ingame ;
- Tanny's WDV Tattoos und Narben - Enhanced validé ingame ;
- Sacred Lust armor set validé ingame ;
- aucun problème bloquant signalé.

Décision :

- Topfreedom Enhanced est validé comme mod cosmétique / NSFW léger ;
- Tanny's WDV Tattoos und Narben - Enhanced est validé comme mod de tatouages / cicatrices ;
- Sacred Lust armor set est validé comme mod d'armure / cosmétique / NSFW léger ;
- Katis_Tattoos est rejeté / différé à cause de sa dépendance Tot Custom, non retenue pour l'objectif coop ;
- [Enhanced] Face It est rejeté / différé à cause de sa dépendance Tot Sudo, non retenue pour conserver une base coop propre ;
- les tests effectués directement en mode Coop deviennent la référence de validation principale du projet.
