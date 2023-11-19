Question 1:

Combien y a-t-il d'éléments <p> présents dans la page HTML ? Imprime-le résultat dans la console.

```js 
    let pElements = document.querySelectorAll('p');
    console.log(pElements.length);
```

Question 2 :
Quel est le contenu texte de l'élément portant l'id coucou ? Imprime-le dans la console.

```js 
    let element = document.getElementById('coucou');
    console.log(element.textContent);
```
Question 3 :
Quelle est l'URL vers laquelle pointe le 3ème élément <a> de la page HTML ? Imprime-la dans la console.
```js
    let aElements = document.querySelectorAll('a');
    console.log(aElements[2].href);
```
Question 4 : 
Combien d'éléments portent la classe compte-moi ? Imprime le résultat dans la console.
```js
    let elements = document.querySelectorAll('.compte-moi'); //Le point . avant compte-moi indique qu'il s'agit d'une classe. C'est la même       syntaxe que celle utilisée dans les feuilles de style CSS pour sélectionner des éléments par classe.
    console.log(elements.length);
```
Question 5 :
Combien d'éléments portent la classe compte-moi ? Imprime le résultat dans la console.
```js
    let liElements = document.querySelectorAll('li.compte-moi');
    console.log(liElements.length);
```
Question 6 :
Combien d'éléments <li> et situés dans une liste ordonnée portent la classe compte-moi ? Imprime le résultat dans la console.
```js
    let liolElements = document.querySelectorAll('ol > li.compte-moi');
    console.log(liolElements.length);
```
Question 7 :
Petit jeu de piste à résoudre si possible sans regarder le fichier HTML…

La page contient un seul élément <div>. Celui-ci contient 2 éléments "unordered list" ou <ul>. Dans le second <ul>, le premier élément de la liste (tag <li>) est caché visuellement de l'utilisateur mais toi, tu peux en récupérer le contenu. Affiche-le dans la console.
```js
    
```