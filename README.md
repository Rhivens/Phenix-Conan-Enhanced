# CONAN Enhanced UE5 Modpack

Documentation de construction progressive d'un modpack pour **Conan Exiles Enhanced / UE5**.

## Objectif

Construire un modpack propre, stable et cohérent pour une utilisation en **host local privé**, principalement pour un groupe de **3 à 4 joueurs**.

Le projet repart d'une base vanilla UE5 propre, sans reprise brute de l'ancienne modlist UE4.

## Philosophie du modpack

- stabilité avant quantité de mods ;
- progression étape par étape ;
- tests réguliers avant ajout de nouveaux blocs ;
- confort de jeu, qualité de vie et interface améliorée ;
- construction et décoration enrichies ;
- gameplay légèrement amélioré, sans transformer le jeu en usine à gaz ;
- compatibilité Conan Exiles Enhanced / UE5 prioritaire.

## Contexte matériel

- PC hôte principal : i9, 64 Go RAM, RTX 4070 12 Go ;
- résolution utilisée : 1920x1080 ;
- connexion Internet : Free 8 Gb/s stable ;
- historique d'hébergement : parties coop/multi régulières, jusqu'à 7 joueurs sur Windrose ;
- objectif Conan : 3 à 4 joueurs.

## État actuel

- base vanilla UE5 propre : validée ;
- anciens abonnements Workshop supprimés ;
- ancienne modlist UE4 analysée, mais non reprise telle quelle ;
- ancien fichier Better Graphics UE4 analysé, mais non réutilisé ;
- ReShade non réinstallé pour l'instant ;
- réglages graphiques UE5 testés en Ultra avec DLSS Qualité, Frame Generation et Nvidia Reflex ;
- gamma ajusté à 1.8 ;
- performances validées à 90 FPS capés ;
- host local solo validé ;
- test multijoueur réel Conan UE5 différé, mais non bloquant.

## Suivre l'avancement du projet

➡️ **[Lire le changelog / résumé de validation](docs/99_changelog_validation.md)**

C'est le meilleur point d'entrée pour suivre l'évolution du modpack : dernières étapes validées, modules terminés ou en cours, décisions importantes, état de stabilité et prochaine reprise.

## Liens utiles

- **[Guide d'installation joueurs](docs/11_installation_joueurs.md)**
- **[Modlist de référence et load order](docs/12_modlist_reference.md)**
- **[Résumé de l'état actuel](docs/00_resume_etat_actuel.md)**
- **[Procédure principale / architecture du modpack](docs/04_architecture_modpack.md)**
- **[Préparation de la base vanilla](docs/01_preparation_base_vanilla.md)**
- **[Tests graphiques et performances](docs/02_tests_graphiques_performances.md)**
- **[Tests host local et multijoueur](docs/03_tests_host_local_multijoueur.md)**
- **[Décisions différées et points à revoir](docs/90_decisions_differees.md)**
- **[Mods à surveiller](notes/mods_a_surveiller.md)**
- **[Analyse de l'ancienne modlist UE4](notes/ancienne_modlist_ue4_analyse.md)**

## Structure documentaire

Les fichiers principaux sont dans `docs/`.

Les notes d'analyse, anciennes références et éléments à surveiller sont dans `notes/`.

## Règle de travail

Chaque ajout de mod ou bloc de mods devra être documenté, testé et validé avant de passer à la suite.

Le barbare peut manier la hache, mais le moddeur, lui, garde un changelog.
