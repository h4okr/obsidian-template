## But du plugin
Ajouter des tuiles facilitant la lisibilité en admonestant le lecteur.
## Comment l’utiliser
```ad-info
Commencer par tapper ` ```ad-`
```
### Options
Il est possible d’ajouter les options suivantes :
```ad-example
title: Un exemple 
icon: key
\`\`\`ad-example
title: Un exemple 
icon: key
\`\`\`
```
ou de modifier la couleur : 
```ad-error
color: 100,250,160
\`\`\`
color: 100,250,160
\`\`\`
```
et d’initialement minimiser le conteneur :
```ad-question
title: un mystère
collapse: true
\`\`\`ad-question
title: un mystère 
collapse: true
\`\`\`
```

## Imbriquer les conteneurs

On peut imbriquer les conteneurs d’admonitions comme on imbriquerait des conteneurs de code avec : 
* en ajoutant une \` supplémentaire pour les conteneurs de plus haut niveau,
* en utilisant la déclaration alternative de conteneur de code `~~~`.

Par exemple,
`````
````ad-info

```ad-note
title:  Une note imbriquée
~~~sql
not null
~~~

````
`````
donne : 
````ad-info

```ad-note
title:  Une note imbriquée
~~~sql
not null
~~~

````

## Admonitions natives à [[Obsidian]] (*callouts*)

#TODO 
## Autres infos
* style personnalisable avec du __css__,
* compatible avec _Mermaid_,

## Documentation officielle
<iframe src="https://plugins.javalent.com/admonitions" width="100%" height="700px"></iframe>
