# Lexi

Le vocabulaire des séquences, pour les élèves : chercher un mot, l'apprendre, puis se tester.
© Lucas Le Coadou - Professeur d'espagnol dans l'académie de Montpellier

## Ce que voient les élèves

- **Séquences** : une carte par séquence publiée, avec la progression de l'élève (mots acquis).
- **Recherche** : la barre de recherche fouille tout le vocabulaire de toutes les séquences, en espagnol comme en français.
- Dans chaque séquence :
  - **Apprendre** : la liste par catégorie, avec la prononciation, et la possibilité de cacher l'espagnol ou le français pour s'auto-interroger.
  - **Cartes** : des cartes mémoire à retourner. « À revoir » remet la carte dans le paquet, « Je sais » la range dans les mots acquis.
  - **Me tester** : choix multiple ou réponse écrite (avec clavier d'accents), dans un sens ou dans l'autre. Correction immédiate, puis « Refaire mes erreurs ».
- **Défi** : un test qui mélange plusieurs séquences, pour réviser avant une évaluation.

La progression est enregistrée dans le navigateur de l'élève : aucun compte, aucune donnée envoyée.

## Mise en ligne (une seule fois)

1. Crée un dépôt **public** sur GitHub, nommé `lexi`.
2. Dépose dedans tout le contenu de ce dossier : `index.html`, `data.json` et le fichier `.nojekyll`.
3. Dans le dépôt, va dans **Settings > Pages**. Choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis enregistre.
4. Au bout d'une minute environ, le site est en ligne à l'adresse `https://<ton-pseudo>.github.io/lexi/`.

## Créer ta clé d'accès enseignant (une seule fois)

1. Sur GitHub, va dans **Settings > Developer settings > Personal access tokens > Fine-grained tokens**, puis clique sur **Generate new token**.
2. Dans **Repository access**, choisis **Only select repositories**, puis le dépôt `lexi`.
3. Dans **Permissions > Repository permissions**, règle **Contents** sur **Read and write**.
4. Choisis une date d'expiration (par exemple la fin de l'année scolaire), puis génère la clé.
5. Copie la clé et range-la dans ton gestionnaire de mots de passe. GitHub ne te la remontrera plus.

Tu peux aussi modifier ta clé existante (celle de Conju ou de Focus) pour y ajouter le dépôt `lexi` : une seule clé suffit alors pour les trois sites.

## Au quotidien

1. Ouvre le site et clique sur **Espace enseignant** en bas de la page.
2. Colle ta clé. Coche « Rester connecté » seulement sur ton ordinateur personnel.
3. Clique sur **Nouvelle séquence**, ou sur le crayon d'une séquence existante.
4. Colle tout le vocabulaire d'un coup, vérifie l'aperçu à droite, puis **Enregistrer**.
5. Les élèves voient les changements une à deux minutes plus tard.

### Faire apparaître le vocabulaire au fil de l'année

Chaque séquence peut être **visible** ou en **brouillon**. Prépare tes séquences à l'avance en brouillon : toi seul les vois (avec l'étiquette « Brouillon »). Le jour où tu commences la séquence en classe, passe-la en « Visible par les élèves ».

### Écrire le vocabulaire

Une ligne par mot :

```
## Los aparatos
el móvil / el celular = le téléphone portable | Siempre llevo el móvil.
el ordenador = l'ordinateur

## Los verbos
chatear = discuter en ligne
compartir = partager
```

- `espagnol = français` : le mot et sa traduction (`;` fonctionne aussi à la place de `=`).
- `| exemple` : une phrase d'exemple facultative, affichée sous le mot.
- `## Titre` : ouvre une catégorie (Noms, Verbes, Expressions…).
- `/` : plusieurs réponses acceptées dans le test (`el móvil / el celular`).
- `( )` : une précision facultative, la réponse est acceptée avec ou sans (`l'abonné (le follower)`).

**Depuis un tableur (Excel, Google Sheets, Pronote…)** : sélectionne les colonnes *espagnol*, *français*, et si tu veux *exemple* puis *catégorie*, copie, et colle directement dans la zone de vocabulaire. Les colonnes sont reconnues automatiquement.

Les boutons **Trier A → Z** et **Retirer les doublons** rangent la liste avant d'enregistrer.

### La correction des tests

- Réponse exacte : juste.
- Accent oublié ou article oublié (`movil`, `ordenador` pour `el ordenador`) : « Presque », compté faux mais signalé en orange.
- Vers le français, les accents ne sont pas sanctionnés.

## Donner un lien direct aux élèves

Chaque séquence a sa propre adresse, par exemple :
- `…/lexi/#/s/los-jovenes-y-las-redes` (la liste à apprendre)
- `…/lexi/#/s/los-jovenes-y-las-redes/cartes` (les cartes mémoire)
- `…/lexi/#/s/los-jovenes-y-las-redes/test` (directement le test)
- `…/lexi/#/defi` (le défi qui mélange les séquences)

## En cas de problème

Si ta clé est perdue ou a fuité, supprime-la sur GitHub (dans la même page que pour la créer) et crée-en une nouvelle. L'ancienne cesse immédiatement de fonctionner.
