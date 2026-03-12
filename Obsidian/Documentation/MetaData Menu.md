## Généralités

### Sur les classes de notes
Les classes sont toutes définies dans le dossier `Obsidian/Type`.
>[!hint]  Utiliser les <u>*tags*</u> pour les classes !
> * les <u>*tags*</u> permettent de meilleurs requêtes avec [[DataView]],
> * les <u>*tags*</u> sont naturellement dans un mode de liste,
> * les <u>*tags*</u> devraient toujours être présents sur une note.

Il faut bien se rappeler que les notes peuvent tout à fait cumuler les classes. 
>[!caution] Les classes d’un même dossier sont mutuellement exclusives
> Une même note ne devrait pas avoir les deux classes `Plan/action` et `Plan/projet`. 
> Néanmoins, elle pourrait en théorie avoir les classes `Plan/tâche` et `Zettelkasten/spécification` simultanément.
## Définition de champs

### Champ relationnel vers d’autres note `File` ou `Files`
Dans la partie requête, on ne faire appel qu’à `dv.pages` et à toutes méthodes chaînées de filtres pour récupérer des pages que l’on veut afficher. Par exemple
```js
dv.pages('"Obsidian/Énumération/Littéraux"').where(x => x.énumération === "Bénéfice")
```
Pour le calcul des libellé affiché, la page est donnée comme paramètre sous le nom de `page`, et on a accès aux propriétés : 
```js
`${page.file.name} (${page.valeur})`
```
Au contraire, pour la méthode de classement des résultats, on n’a plus accès qu’au fichier (`TFile`), ce qui est franchement problématique. Fort heureusement, on peut quand même gruger et faire appel à [[Dataview]] en passant par `this`, par exemple :
```js
this.app.plugins.plugins.dataview.api.page(a.path).valeur - this.app.plugins.plugins.dataview.api.page(b.path).valeur 
```
### Les *Lookups*
```ad-warning
Dès lors qu’un *lookup* plante, tous les *lookups* plantent.
```
De plus, les méthodes d’affichage personnalisées doivent prendre en compte les paramètres null.

## Documentation officielle
<iframe src="https://mdelobelle.github.io/metadatamenu/" width="100%" height="800px"></iframe>
