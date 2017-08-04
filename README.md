# CSS by Timothé M.

Un dépôt github qui regroupe différent fichier css de ressource que j'ai besoin pour divers projets.

- [x] Color Material Design
   - [x] Color Palette
- [x] Color MDB
   - [x] Color Palette en rgba
   - [x] Hover effects
   
## Aide pour les couleurs

Pour voir un rendu des couleurs, veuillez regarder les images dans le dossier `img/`

## Aide pour les effets de hover

1. Créer un bloc avec la class `.view`
2. Ajouter ensuite la class relative à l'effet que vous voulez utiliser (exemple: `.overlay` ou `.hm-zoom`)
3. Choississez maintenant la couleur et l'intensité de votre effets
4. Définissez votre image. Si vous désirez que votre image soit responsive, n'oubliez pas d'ajouter la class `.img-fluid`
5. Ajouter la class `.mask` pour créer l'overlay
6. Si vous voulez ajouté du texte, vous devez utilisé la class `.flex-center` pour centrer celui-ci, et `.white-text` pour que votre texte est un plus grand contraste et soit plus visible.

---

Si vous voulez utilisé un effet de zoom, veuillez suivre les instruction suivante et ajouter la class `.hm-zoom`

Pour utilisé un effet shadow, vous devez ajouté la class `.hoverable`