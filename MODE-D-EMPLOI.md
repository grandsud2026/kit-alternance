# Modifier le site Kit Alternance

Le site se compose de trois choses :

- `index.html` : la mise en page (couleurs, menu, logo). **Vous n'avez pas besoin d'y toucher.**
- le dossier `contenu` : **tout le texte du site**, une page = un fichier `.md`.
- le dossier `fichiers` : les documents à télécharger (modèles de CV, de lettre, tableau de prospection, guide du financement).

## Changer un texte

1. Ouvrez le fichier de la page dans le dossier `contenu` (par exemple `offres.md` pour les postes des partenaires) avec un éditeur de texte simple : Bloc-notes, TextEdit, ou directement dans l'éditeur en ligne de l'hébergeur.
2. Modifiez le texte comme dans un mail.
3. Enregistrez. Le site affiche la nouvelle version.

| Ce que vous écrivez | Ce que le site affiche |
|---|---|
| `# Titre` | Le grand titre de la page (un seul par page) |
| `## Partie` | Un titre de partie, souligné en corail |
| `### Sous-partie` | Un sous-titre corail |
| `- élément` | Une liste à puces |
| `1. étape` | Une liste numérotée |
| `**texte**` | Du texte en **gras** |
| `[texte du lien](https://adresse.fr)` | Un lien vers un autre site |
| `[texte](#offres)` | Un lien vers une page du kit (nom du fichier sans `.md`) |
| `[Télécharger…](fichiers/nom.pdf)` | Un bouton de téléchargement |
| `> texte` | Un encadré corail (contacts, conseils importants) |
| `- [ ] tâche` | Une case à cocher (mémorisée sur le téléphone de l'étudiant) |
| `---` | Une ligne de séparation |

## Mettre à jour les offres des partenaires

Ouvrez `contenu/offres.md`. Chaque ligne du tableau est une offre, les colonnes sont séparées par `|`.

- **Ajouter une offre** : copiez une ligne existante, collez-la en dessous et changez le texte.
- **Retirer une offre** : supprimez la ligne.
- **Couleur de l'état** : écrivez `Ouvert aux candidatures` (vert), `Candidatures en cours d'examen` (bleu) ou `Pourvu` (gris).

## Ajouter ou remplacer un document à télécharger

Déposez le fichier dans le dossier `fichiers` **avec exactement le même nom** que dans le lien. Noms attendus aujourd'hui :

- `modele-cv.pdf`
- `modele-lettre-motivation.pdf`
- `tableau-prospection-alternance.xlsx`
- `financement-alternant.pdf`

Tant qu'un fichier manque, son bouton s'affiche en pointillés avec la mention « bientôt disponible ».

## Ajouter une page

1. Créez un nouveau fichier dans `contenu`, par exemple `entretien.md`, qui commence par `# Titre de la page`.
2. Ajoutez une ligne dans `contenu/menu.md` : `- [Titre dans le menu](entretien)`.

## Si quelque chose ne s'affiche plus

Le plus souvent, un nom de fichier dans `menu.md` ne correspond pas au fichier du dossier `contenu`, ou un fichier a été enregistré en `.txt` au lieu de `.md`. Vous pouvez aussi demander à Claude de faire la modification à votre place.
