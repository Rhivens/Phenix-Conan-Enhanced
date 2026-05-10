# 05 - Mods Interface & QoL

## Objectif

Documenter les mods liés à l'interface, au confort de jeu et à la qualité de vie.

## Statut

**En cours.**

Mods Interface & QoL actuellement validés :

1. **Simple Minimap (by Xevyr) v5.1.1**.
2. **Stacksize Plus v2.0.0-enhanced**.
3. **Lore & Loot Highlight v1.0.0 by Xevyr**.
4. **Twin-Bar v5.0.4 by Xevyr**.
5. **Simple Modlist v5.0.1 by Xevyr**.
6. **Inventory Compactor v5.0.1 by Xevyr**.
7. **Unlock Plus v2.0.1-enhanced**.

## Critères de sélection

Les mods de cette catégorie devront :

- être compatibles Conan Exiles Enhanced / UE5 ;
- améliorer le confort sans alourdir inutilement le jeu ;
- éviter les conflits avec les systèmes principaux ;
- être testés rapidement en solo puis, si possible, en host local.

## Mods candidats

À compléter.

## Mods validés

### Simple Minimap (by Xevyr) v5.1.1

- Catégorie : Interface & QoL.
- Source : Steam Workshop.
- Workshop ID : `3719513784`.
- Type : minimap légère et autonome.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Le fichier `.pak` est bien présent dans le dossier Workshop Steam :

```text
C:\JEUX\STEAM\steamapps\workshop\content\440900\3719513784
```

- Le mod n'apparaissait pas dans l'onglet Mods du launcher Funcom.
- Le mod apparaissait correctement dans le menu Mods directement en jeu.
- Le mod a été activé depuis le menu Mods en jeu.
- La minimap fonctionne correctement ingame.

#### Conclusion

**Simple Minimap est validé comme premier mod du bloc Interface & QoL.**

Note importante : pour Conan Exiles Enhanced / UE5, le launcher Funcom peut ne pas afficher certains mods Workshop alors qu'ils apparaissent correctement dans le menu Mods du jeu. Pour la suite du projet, le menu Mods en jeu devient la référence principale de vérification.

---

### Stacksize Plus v2.0.0-enhanced

- Catégorie : Interface & QoL / confort inventaire.
- Source : Steam Workshop.
- Workshop ID : `3720915336`.
- Type : augmentation configurable de la taille des piles d'objets.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo.
- Configuration testée via un objet avec inventaire / menu radial.
- Utilisation du panneau administrateur acceptée pour accélérer les tests.
- Le mod fonctionne correctement ingame.

#### Note de configuration

Le réglage de Stacksize Plus ne se fait pas depuis le panneau administrateur classique.

Méthode retenue :

1. passer administrateur si nécessaire ;
2. poser un objet avec inventaire, par exemple un coffre ou une station de craft ;
3. ouvrir le menu radial sur cet objet ;
4. accéder aux réglages du mod ;
5. définir un multiplicateur raisonnable.

Réglage conseillé pour le modpack :

```text
x5 au départ
```

Ce réglage apporte du confort sans transformer les joueurs en semi-remorques hyboriens.

#### Conclusion

**Stacksize Plus est validé comme second mod du bloc Interface & QoL.**

---

### Lore & Loot Highlight v1.0.0 by Xevyr

- Catégorie : Interface & QoL / repérage visuel.
- Source : Steam Workshop.
- Workshop ID : `3718655125`.
- Type : mise en évidence d'objets interactifs, lore et loot.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo dans un mini-lot QoL avec Twin-Bar.
- Fonctionnement validé ingame.

#### Conclusion

**Lore & Loot Highlight est validé comme troisième mod du bloc Interface & QoL.**

---

### Twin-Bar v5.0.4 by Xevyr

- Catégorie : Interface & QoL / barre de raccourcis.
- Source : Steam Workshop.
- Workshop ID : `3719621216`.
- Type : extension de la barre de raccourcis avec emplacements secondaires.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo dans un mini-lot QoL avec Lore & Loot Highlight.
- Fonctionnement validé ingame.

#### Note d'utilisation

Twin-Bar se manipule via ses raccourcis de bascule pour accéder aux emplacements secondaires de la barre rapide.

Le mod fonctionne correctement après réglage / prise en main en jeu.

#### Conclusion

**Twin-Bar est validé comme quatrième mod du bloc Interface & QoL.**

---

### Simple Modlist v5.0.1 by Xevyr

- Catégorie : Interface & QoL / information modlist.
- Source : Steam Workshop.
- Workshop ID : `3719546290`.
- Type : affichage et consultation de la liste des mods actifs en jeu.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo.
- Fonctionnement validé ingame.

#### Intérêt pour le modpack

Simple Modlist permet de consulter plus facilement la liste des mods chargés en jeu.

Ce mod est utile pour :

- vérifier rapidement la modlist active ;
- aider les joueurs à contrôler leur installation ;
- faciliter les diagnostics en cas d'erreur de modlist.

#### Conclusion

**Simple Modlist est validé comme cinquième mod du bloc Interface & QoL.**

---

### Inventory Compactor v5.0.1 by Xevyr

- Catégorie : Interface & QoL / inventaire.
- Source : Steam Workshop.
- Workshop ID : `3718614759`.
- Type : compactage d'inventaire, restack et rangement des espaces vides.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo dans le pack QoL avancé 10.6.
- Fonctionnement validé ingame.

#### Conclusion

**Inventory Compactor est validé comme sixième mod du bloc Interface & QoL.**

---

### Unlock Plus v2.0.1-enhanced

- Catégorie : Interface & QoL / inventaire / stockage.
- Source : Steam Workshop.
- Workshop ID : `3720948133`.
- Type : gestion avancée des ressources, transferts, stockage et options d'inventaire.
- Statut : **validé en jeu**.

#### Résultat du test

- Abonnement Steam Workshop effectué.
- Mod activé depuis le menu Mods en jeu.
- Test réalisé en host local solo dans le pack QoL avancé 10.6.
- Fonctionnement validé ingame.

#### Note de prudence

Unlock Plus est plus structurant que les petits mods d'interface, car il touche aux flux de ressources et de stockage.

Il est validé, mais devra être surveillé lors des futurs tests multijoueur.

#### Conclusion

**Unlock Plus est validé comme septième mod du bloc Interface & QoL.**

## Mods rejetés ou différés

À compléter.

## Notes de test

### Règle découverte pendant le test Simple Minimap

Le launcher Funcom n'est pas toujours fiable pour vérifier la présence des mods Workshop.

Méthode retenue :

1. vérifier l'abonnement Steam Workshop ;
2. vérifier si le fichier `.pak` existe dans le dossier Workshop ;
3. lancer le jeu ;
4. ouvrir le menu Mods depuis le jeu ;
5. activer le mod depuis ce menu ;
6. redémarrer si le jeu le demande ;
7. tester en host local solo.

Cette règle devra être prise en compte dans la procédure d'installation joueurs.

### Règle de test

Pour les tests du modpack, l'utilisation du panneau administrateur est autorisée afin d'accélérer la validation des fonctionnalités.

Le but est de tester la stabilité et le fonctionnement des mods, pas de jouer normalement pendant la phase de construction du modpack.

### Règle de mini-lots

Pour les mods simples d'interface ou de QoL, il est possible de tester plusieurs mods en même temps, par mini-lots raisonnables.

Règle retenue :

```text
Interface & QoL simple : 2 à 4 mods maximum par test
Building / décoration : 2 à 3 mods maximum par test
Gameplay / thralls / followers : 1 à 2 mods maximum par test
Frameworks ou mods lourds : 1 mod à la fois
```
