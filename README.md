# Les jeux d'histoire de M. Ménard

Jeux éducatifs en HTML pour les cours d'histoire (secondaire 2 et 4).

Site : https://monsieurmenard.github.io/histoire/

> Ce site est celui **de mes élèves**. La vitrine publique, pour partager hors de l'école, est https://monsieurmenard.github.io/histoireenjeu/ (dépôt `histoireenjeu`), avec seulement Le Ciel des humanistes et le teaser de La Carte repeinte.

## Contenu

- `index.html` : page d'accueil qui liste les jeux
- `ciel-des-humanistes/` : Le Ciel des humanistes (sec. 2, chapitre 1, Renaissance et humanisme)
- `six-vies/` : Six vies, 1840-1896 (sec. 4, chapitre 1), **version bêta protégée par mot de passe** (carte « Accès réservé » sur la page d'accueil). Lien direct : https://monsieurmenard.github.io/histoire/six-vies/

- *La Carte repeinte : le scribe de Tlatelolco* (sec. 2, chapitre 2, colonialisme européen) : **teaser seulement** sur la page d'accueil (carte « Bientôt · novembre 2026 », sans lien). Le jeu n'est pas encore dans le dépôt.

## Jeux protégés par mot de passe

Le fichier `six-vies/index.html` est **chiffré** : il ne contient que du texte illisible tant qu'on n'entre pas le mot de passe.

⚠️ Pour corriger Six vies, **ne remplace jamais** ce fichier par la version normale du jeu : elle deviendrait lisible par tout le monde, et l'historique de GitHub la garderait même après suppression. Demande plutôt à Claude de rechiffrer la nouvelle version.

## Ajouter un jeu

1. Crée un dossier au nom du jeu (sans accents ni espaces, ex. `revolution-industrielle/`) et mets-y le jeu sous le nom `index.html`.
2. Dans `index.html` (la page d'accueil), ajoute un bloc dans la liste `JEUX`.
3. Enregistre (« Commit changes »). Le site se met à jour en une ou deux minutes.

## Corriger un jeu

Remplace le fichier `index.html` du dossier du jeu. Les élèves auront la nouvelle version au même lien.

**Le Ciel des humanistes** est aussi sur le site public : son fichier est identique dans les deux dépôts (le jeu détecte le site public, y cache le code de bêta-testeur et retire le nom de l'école du certificat). Après une correction, remplace-le **dans les deux dépôts**.
