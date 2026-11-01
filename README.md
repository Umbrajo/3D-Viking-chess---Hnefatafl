# Hnefatafl 3D · Le siège du roi

**User — premier auteur, idée et direction du projet.**

Ce projet me tenait à cœur depuis le lycée. L’apparition de [Traversal](https://www.traversalgame.com/) m’a rappelé ce projet que j’avais imaginé à l’époque et m’a décidé à le réaliser avec l’aide de l’IA.

**Usage de ChatGPT :** assistance à la conception de cette adaptation, à la génération du code, à sa mise en forme et à la préparation de sa publication. ChatGPT n’est pas un auteur humain.

## Le jeu

Une adaptation expérimentale du Hnefatafl sur un cube de **7 × 7 × 7 cases** : un roi, 24 défenseurs, 54 attaquants et douze sorties. Jouez en solo contre l’ordinateur ou à deux sur le même écran. Les règles complètes de cette variante sont accessibles dans le jeu.

**Prononciation indicative :** « hné-va-tavl », transcription approximative du vieux norrois **[ˈhne.vɑˌtɑvl]**. Les usages modernes varient.

Pour découvrir le jeu traditionnel sur un plateau à deux dimensions : [règles du Hnefatafl par Masters Traditional Games](https://www.mastersofgames.com/rules/hnefatafl-rules.htm), un site humain spécialisé dans les jeux traditionnels (en anglais). Les règles historiques ne nous sont pas parvenues intégralement ; les variantes actuelles reposent sur des reconstructions. Cette adaptation cubique ne prétend pas reproduire les règles historiques.

## Lancer le site

Aucune dépendance ni compilation. Ouvrir `index.html` dans un navigateur moderne, ou démarrer un serveur statique depuis la racine :

```sh
python3 -m http.server 8000
```

Le code du jeu provient de l’archive `Hnefatafl_3D_sauvegarde_2026-11-01.zip` fournie par User. La présentation, les crédits et les métadonnées ont été ajoutés pour cette publication.

## Publication sur GitHub Pages

Le fichier `index.html` et `.nojekyll` sont placés à la racine pour une publication statique directe. Dans **Settings → Pages**, sélectionner **Deploy from a branch**, puis **main / (root)** et enregistrer. L’activation requiert les droits d’administration du dépôt et une offre GitHub compatible avec sa visibilité.

Adresse attendue après activation et déploiement réussi :
https://umbrajo.github.io/3D-Viking-chess---Hnefatafl/

Cette adresse n’est pas une confirmation que le site est déjà publié.
