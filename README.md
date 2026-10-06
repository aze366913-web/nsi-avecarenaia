# nsi-avecarenaia

## Projet HTML / CSS — « Les Volcans »

Site web réalisé à partir des consignes du fichier `projet.pdf` :

> Créer un site web d'au moins 3 pages codées en HTML-CSS comprenant : une liste,
> un tableau, un lien externe par un bouton, une image, des liens entre les pages,
> deux polices de caractère, un fichier CSS séparé ; au moins l'une des pages sera
> responsive.

### Les pages

| Fichier | Rôle | Feuille de style |
| --- | --- | --- |
| `index.html` | Page d'accueil : présentation, chiffres clés, les 4 types d'éruptions | `style_page1.css` |
| `types.html` | Les 4 types de volcans : hawaïen, strombolien, vulcanien, peléen | `style_types.css` |
| `records.html` | Les records des volcans (tableau) et le volcanisme en France | `style_records.css` |

Dossier `images/` : photographies utilisées dans les pages.

Le contenu provient du fichier de notes `brouillon.txt` (classification des éruptions
des Éditions Larousse et dossier [Observaterre.fr](https://observaterre.fr/risques-telluriques-en-france/risque-volcanique/types-de-volcans-et-origines/)).

### Consignes respectées

- **3 pages** : `index.html`, `types.html`, `records.html`
- **Liste** : sommaire, fiches d'éruptions (listes de puces), liste « À retenir »
- **Tableau** : tableau des records sur `records.html` (12 records)
- **Lien externe par un bouton** : bouton vers Observaterre.fr sur `types.html` et `records.html`
- **Image** : 5 photographies dans le dossier `images/`
- **Liens entre les pages** : menu de navigation, pagination, liens du pied de page, liens d'ancrage
- **Deux polices** : *Bebas Neue* (titres) et *Lato* (textes)
- **Fichier CSS séparé** : une feuille de style propre à chaque page HTML
- **Responsive** : les trois pages possèdent des media queries (le tableau des records
  se transforme en fiches sur téléphone)

### Aperçu

Ouvrir `index.html` dans un navigateur, ou lancer un serveur local :

```bash
python3 -m http.server 8000
```
