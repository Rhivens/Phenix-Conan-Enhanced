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

- test impossible initialement faute de joueur disponible ;
- historique d'hébergement solide ;
- connexion Free 8 Gb/s stable ;
- sessions multi/coop déjà montées jusqu'à 7 joueurs sur Windrose ;
- objectif Conan : 3 à 4 joueurs ;
- les tests de mods sont ensuite réalisés directement en mode Coop / host local.

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
- fichier `.pak` confirmé ;
- mod visible dans le menu Mods directement en jeu ;
- mod activé depuis le menu Mods en jeu ;
- minimap fonctionnelle ingame.

Décision :

- Simple Minimap est validé comme premier mod Interface & QoL ;
- pour la suite, le menu Mods en jeu devient la référence principale de vérification.

## Étape 10.2 - Interface & QoL : Stacksize Plus

Statut : **validée**.

Mod : **Stacksize Plus v2.0.0-enhanced**.

Résumé :

- abonnement Steam Workshop effectué ;
- mod activé depuis le menu Mods en jeu ;
- test réalisé en host local solo ;
- configuration testée via un objet avec inventaire / menu radial ;
- fonctionnement validé ingame.

Décision :

- Stacksize Plus est validé ;
- réglage conseillé au départ : `x5`.

## Étape 10.3 - Interface & QoL : mini-lot Lore & Loot Highlight + Twin-Bar

Statut : **validée**.

Mods :

- **Lore & Loot Highlight v1.0.0 by Xevyr** ;
- **Twin-Bar v5.0.4 by Xevyr**.

Résumé :

- mods activés depuis le menu Mods en jeu ;
- Lore & Loot Highlight validé ingame ;
- Twin-Bar validé ingame après prise en main / réglage ;
- aucun problème bloquant signalé.

Décision :

- les deux mods sont validés ;
- les tests par mini-lots sont acceptés pour les petits mods QoL simples.

## Étape 10.4 - Interface & QoL : Simple Modlist

Statut : **validée**.

Mod : **Simple Modlist v5.0.1 by Xevyr**.

Résumé :

- mod activé depuis le menu Mods en jeu ;
- fonctionnement validé ingame.

Décision :

- Simple Modlist est validé comme outil d'aide au diagnostic et à la vérification de modlist.

## Étape 10.5 - Pack Fashionist + Better Thralls

Statut : **validée**.

Mods :

- **Fashionist v5.0.2-enhanced** ;
- **Better Thralls v3.0.0-enhanced**.

Résumé :

- mods activés depuis le menu Mods en jeu ;
- Fashionist validé ingame ;
- Better Thralls validé ingame ;
- aucun problème bloquant signalé.

Décision :

- Fashionist est validé ;
- Better Thralls est validé, à surveiller en usage prolongé.

## Étape 10.6 - Pack QoL avancé

Statut : **validée**.

Mods :

- **Inventory Compactor v5.0.1 by Xevyr** ;
- **Unlock Plus v2.0.1-enhanced** ;
- **Follower Remote v5.0.3 by Xevyr** ;
- **Xevyr's Hearthstone v5.0.0**.

Résumé :

- les quatre mods sont activés et validés ingame ;
- aucun problème bloquant signalé.

Décision :

- pack QoL avancé validé ;
- Unlock Plus et les mods followers restent à surveiller en multijoueur prolongé.

## Étape 10.7 - Contenu adulte privé : Primal Instinct

Statut : **validée**.

Mod : **Primal Instinct**.

Résumé :

- Workshop ID officiel retenu : `3723050568` ;
- mod activé depuis le menu Mods en jeu ;
- fonctionnement validé ingame après prise en main ;
- aucun problème bloquant signalé.

Décision :

- Primal Instinct est validé pour la partie privée entre adultes ;
- les futurs mods de ce type doivent rester testés avec prudence.

## Étape 10.8 - Pack visuel / déco / building léger

Statut : **partiellement validée**.

Mods validés :

- **Panda's Bloody Mess** ;
- **More Clan Emblems Enhanced** ;
- **SH - Decorations v1.0.0 (Enhanced)**.

Mod rejeté :

- **Lisas Building Stone Age**.

Résumé :

- les trois premiers mods sont validés ;
- Lisas Building Stone Age a ensuite été affiché comme corrompu avec erreur de parsing ;
- après retrait, la base redevient stable.

Décision :

- Lisas Building Stone Age est rejeté définitivement ;
- Pickup+, Less Building Placement Restrictions et LBPR Additional Features restent différés car non visibles via filtre Enhanced au moment de la recherche.

## Étape 10.9 - Pack apparence / cosmétique

Statut : **validée**.

Mods :

- **Topfreedom Enhanced** ;
- **Tanny's WDV Tattoos und Narben - Enhanced** ;
- **Sacred Lust armor set**.

Résumé :

- test réalisé directement en mode Coop ;
- les trois mods sont validés ingame ;
- aucun problème bloquant signalé.

Décision :

- pack cosmétique validé ;
- Katis_Tattoos et Face It Enhanced restent rejetés / différés à cause de dépendances non retenues pour la coop.

## Étape 10.10 - Pack craft / réparation / stockage

Statut : **validée**.

Mods :

- **Craftable Armor Scraps - Enhanced** ;
- **TDI_LegendaryRepair [Enhanced]** ;
- **Organizer Sorting Chest v1.0.0** ;
- **Automatic Fish Trap v1.0.3**.

Résumé :

- test réalisé directement en mode Coop ;
- les quatre mods sont validés ;
- Organizer Sorting Chest fonctionne correctement avec Unlock Plus.

Décision :

- pack craft / réparation / stockage validé.

## Étape 10.10b - Revalidation de la base après reset modlist

Statut : **validée**.

Résumé :

- après l'erreur sur Lisas Building Stone Age, Conan a réinitialisé la modlist ;
- Fabien a reconstruit la modlist active sans Lisas Building Stone Age ;
- test effectué jusqu'au mod 22 ;
- tout est OK jusqu'au mod 22.

Décision :

- poursuivre la construction du modpack depuis cette base saine.

## Étape 10.11 - Pack gameplay léger / confort coop

Statut : **validée**.

Mods :

- **[Enhanced] Player Ignores Follower Collision** ;
- **Enhanced Gliders** ;
- **LegitReligious [Enhanced]** ;
- **Diverse Barkeeps**.

Résumé :

- test réalisé directement en mode Coop ;
- jeu stable ;
- aucune erreur signalée ;
- pack validé.

Décision :

- pack gameplay léger validé ;
- la base active passe à **26 mods validés**.

## Étape 10.12 - Pack craft / sorcellerie / cuisine

Statut : **validée**.

Mods :

- **[Enhanced] Craftable Legendaries** ;
- **Sorcery Tweaks Enhanced** ;
- **[Enhanced] Dark Decention Cooking and Brewing**.

Résumé :

- test réalisé directement en mode Coop ;
- jeu stable et fluide ;
- aucune erreur signalée ;
- pack validé.

Décision :

- pack craft / sorcellerie / cuisine validé ;
- la base active passe à **29 mods validés**.

## Étape 10.13 - Pack building / décoration avancée

Statut : **validée initialement, corrigée ensuite par l'étape 10.15**.

Mods initialement testés :

- **Ancient Civilization - Enhanced** ;
- **Desert Town** ;
- **Enhanced Builder 2026.5.9**.

Résumé :

- test réalisé directement en mode Coop ;
- jeu stable ;
- aucune erreur signalée ;
- pièces de construction testées et OK ;
- pack initialement validé.

Anomalie :

- l'intro du jeu ne pouvait plus être passée au clic souris.

Correction ultérieure :

- voir l'étape 10.15 pour le retrait de **Enhanced Builder 2026.5.9**.

## Étape 10.14 - Test isolé : The Compendium of Crawling Chaos Enhanced Edition

Statut : **échec — rejeté / différé**.

Mod : **The Compendium of Crawling Chaos Enhanced Edition**.

Résumé :

- mod testé seul après la base stable de 32 mods ;
- freeze complet du PC observé ;
- clavier inopérant ;
- `CTRL + ALT + SUPPR` sans réponse ;
- redémarrage forcé via bouton physique nécessaire ;
- retour à la stabilité après désabonnement.

Décision :

- mod non retenu pour le modpack Coop local à ce stade.

## Étape 10.15 - Retrait de Enhanced Builder 2026.5.9

Statut : **validée — mod retiré / différé**.

Mod concerné : **Enhanced Builder 2026.5.9**.

Résumé :

- mod identifié comme responsable de l'intro non passable au clic souris ;
- décision prise : retirer le mod pour conserver une expérience joueur propre.

Action corrective :

- Enhanced Builder 2026.5.9 est retiré du load order actif ;
- Ancient Civilization - Enhanced et Desert Town restent validés ;
- la base officielle redescend à **31 mods actifs validés**.

Décision :

- Enhanced Builder 2026.5.9 est déplacé dans les mods rejetés / différés après test.

## Étape 10.16 - Test isolé : Derketo Acolyte Replacer

Statut : **validée**.

Résumé :

- mod ajouté après retrait de Enhanced Builder ;
- lancement OK ;
- chargement Coop / host local OK ;
- test ingame validé ;
- aucune erreur, aucun freeze, aucun comportement bloquant.

Décision :

- Derketo Acolyte Replacer est validé ;
- la base active passe à **32 mods actifs validés**.

## Étape 10.17 - Test isolé : CNC - Enhanced

Statut : **validée**.

Résumé :

- intro toujours passable au clic souris ;
- lancement du jeu OK ;
- chargement en jeu OK ;
- test ingame validé ;
- aucune erreur, aucun freeze, aucun comportement bloquant.

Décision :

- CNC - Enhanced est validé ;
- la base active passe à **33 mods actifs validés**.

## Étape 10.18 - Test isolé : DrK Spiders to Scorpions

Statut : **validée**.

Résumé :

- mod ajouté après la base stable de 33 mods ;
- test ingame validé ;
- aucun CTD ;
- aucun freeze.

Décision :

- DrK Spiders to Scorpions est validé ;
- la base active passe à **34 mods actifs validés**.

## Étape 10.19 - Test isolé : HyperBoreanReforged

Statut : **validée**.

Résumé :

- mod ajouté après la base stable de 34 mods ;
- test ingame positif ;
- aucun crash ;
- aucun freeze ;
- inventaire OK ;
- craft OK ;
- interface OK ;
- aucun comportement bloquant observé.

Décision :

- HyperBoreanReforged est validé comme mod de contenu / équipement / ambiance ;
- placement officiel : entre CNC - Enhanced et Craftable Armor Scraps - Enhanced ;
- la base active passe à **35 mods actifs validés**.

## Étape 10.20 - Test isolé : The Purge mod by Xevyr

Statut : **validation partielle — intégration OK**.

Résumé :

- mod ajouté après la base stable de 35 mods ;
- aucun message corrupted ;
- aucune dépendance manquante ;
- aucun CTD ;
- aucun freeze ;
- inventaire OK ;
- interface OK ;
- intégration technique validée.

Décision :

- The Purge mod est accepté provisoirement dans le load order ;
- test fonctionnel dédié requis avant validation complète.

## Étape 10.20b - Test fonctionnel contrôlé : The Purge mod

Statut : **validée**.

Résumé :

- test fonctionnel réalisé sur une mini-base sacrifiable ;
- console ouverte après bascule temporaire du clavier Windows en Anglais / QWERTY ;
- touche physique `²` utilisée pour ouvrir la console ;
- commande `dc purgeconfig` fonctionnelle ;
- panneau Purge Settings ouvert avec succès ;
- commande `dc purgelist` fonctionnelle ;
- commande `dc startpurge [index]` fonctionnelle après sélection d'un index de purge valide ;
- ennemis spawnés correctement ;
- cris de guerre et comportement d'attaque observés ;
- aucun CTD signalé ;
- aucun freeze signalé.

Décision :

- The Purge mod passe de validation partielle à validation complète ;
- la base active passe à **36 mods actifs validés**.

## Étape 10.21 - Test isolé : Navi's Revived Leveling Enhanced

Statut : **validée**.

Résumé :

- mod de progression / leveling Enhanced ;
- extension du niveau maximum au-delà du niveau vanilla 60 ;
- test réalisé par paliers jusqu'au niveau 80 ;
- progression fonctionnelle ;
- aucun message corrupted ;
- aucune dépendance manquante ;
- aucun CTD ;
- aucun freeze ;
- inventaire OK ;
- interface OK ;
- fiche personnage / progression OK.

Décision :

- Navi's Revived Leveling Enhanced est retenu comme mod de progression / leveling ;
- les autres mods de leveling plus extrêmes ou moins lisibles sont écartés ;
- la base active passe à **37 mods actifs validés**.

## Étape 10.22 - Test isolé : Wicked Webs of Zamora UE5

Statut : **validée**.

Résumé :

- mod de construction / building ajouté après la base stable de 37 mods ;
- test ingame validé ;
- éléments de construction testés ;
- aucun message corrupted signalé ;
- aucune dépendance manquante signalée ;
- aucun CTD ;
- aucun freeze ;
- inventaire OK ;
- interface OK ;
- système de construction OK ;
- aucun comportement bloquant observé.

Décision :

- Wicked Webs of Zamora UE5 est validé comme mod de construction / building ;
- la base active passe à **38 mods actifs validés**.

## Étape 10.23 - Clôture provisoire de la phase d'installation des mods

Statut : **validée, puis rouverte pour ajouts cosmétiques ciblés aux étapes 10.24 et 10.25**.

Résumé :

- tous les mods raisonnables de la liste initiale ont été testés, retenus, rejetés ou remplacés ;
- le fichier `modlist.txt` réel fourni par Fabien devient la référence terrain ;
- le load order officiel est recalé sur ce fichier ;
- base finale à ce moment : **38 mods actifs validés**.

Décision :

- fin provisoire de la phase d'installation de mods ;
- phase rouverte ensuite pour ajout de Aquilonian Females Enhanced puis Complete Thrall Fashion.

## Étape 10.24 - Test isolé : Aquilonian Females Enhanced

Statut : **validée**.

Résumé :

- mod testé dans une nouvelle partie test ;
- Workshop ID : `3721124998` ;
- fichier `.pak` : `AquilonianFemales_UE5.pak` ;
- test sur plusieurs tenues ingame ;
- aucun clipping observé ;
- ajustement des tenues jugé excellent ;
- amélioration visuelle du body très concluante ;
- aucun CTD signalé ;
- aucun freeze signalé ;
- aucun comportement bloquant observé.

Décision :

- Aquilonian Females Enhanced est validé comme mod d'apparence / body féminin ;
- le mod est désormais placé en position **40**, après Complete Thrall Fashion ;
- la base active passe initialement à **39 mods actifs validés**, puis à **40** après l'étape 10.25.

## Étape 10.25 - Test isolé : Complete Thrall Fashion vE-1.3.5

Statut : **validée**.

Résumé :

- mod testé après la base stable de 39 mods ;
- Workshop ID : `3725384942` ;
- mod de personnalisation / apparence des thralls ;
- test ingame validé ;
- fonctionnement jugé correct ;
- aucun CTD signalé ;
- aucun freeze signalé ;
- aucun comportement bloquant observé.

Décision :

- Complete Thrall Fashion vE-1.3.5 est validé comme mod d'apparence / fashion pour thralls ;
- le mod est placé en position **39**, avant **Aquilonian Females Enhanced** ;
- Aquilonian Females Enhanced passe en position **40** ;
- la base active passe à **40 mods actifs validés**.
