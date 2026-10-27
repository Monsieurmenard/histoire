# Les jeux d'histoire de M. Ménard

Jeux éducatifs en HTML pour les cours d'histoire (secondaire 2 et 4).

Site : https://monsieurmenard.github.io/histoire/

## Contenu

- `index.html` : page d'accueil, avec une section par niveau (Secondaire 2, Secondaire 4)
- `ciel-des-humanistes/` : Le Ciel des humanistes (sec. 2, chapitre 1, Renaissance et humanisme)
- `six-vies/` : Six vies, 1840-1896 (sec. 4, chapitre 1), **version bêta protégée par mot de passe** (carte « Accès réservé » sur la page d'accueil). Lien direct : https://monsieurmenard.github.io/histoire/six-vies/

- *La Carte repeinte : le scribe de Tlatelolco* (sec. 2, chapitre 2, colonialisme européen) : **teaser seulement** sur la page d'accueil (carte « Bientôt · novembre 2026 », sans lien). Le jeu n'est pas encore dans le dépôt.

## Jeux protégés par mot de passe

Le fichier `six-vies/index.html` est **chiffré** : il ne contient que du texte illisible tant qu'on n'entre pas le mot de passe.

⚠️ Pour corriger Six vies, **ne remplace jamais** ce fichier par la version normale du jeu : elle deviendrait lisible par tout le monde, et l'historique de GitHub la garderait même après suppression. Demande plutôt à Claude de rechiffrer la nouvelle version.

## Liens directs par niveau

Pour envoyer un lien à un groupe (Teams, courriel) qui arrive directement à sa section :

- Secondaire 2 : https://monsieurmenard.github.io/histoire/#sec2
- Secondaire 4 : https://monsieurmenard.github.io/histoire/#sec4

## Ajouter un jeu

1. Crée un dossier au nom du jeu (sans accents ni espaces, ex. `revolution-industrielle/`) et mets-y le jeu sous le nom `index.html`.
2. Dans `index.html` (la page d'accueil), ajoute un bloc dans la liste `JEUX`. Le champ `niveau` (`"Secondaire 2"` ou `"Secondaire 4"`) décide dans quelle section le jeu apparaît. Pour un nouveau niveau, ajoute-le dans la liste `NIVEAUX`.
3. Enregistre (« Commit changes »). Le site se met à jour en une ou deux minutes.

## Corriger un jeu

Remplace le fichier `index.html` du dossier du jeu. Les élèves auront la nouvelle version au même lien.
