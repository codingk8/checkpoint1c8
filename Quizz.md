## Qu'est ce qu’un navigateur ?

```
Un navigateur est un logiciel qui permet de lire des sites web.
Son rôle est d'interprêter le code des pages et de le restituer sous forme visuelle.
Il existe plusieurs navigateurs et chacun interprète le code d'une façon qui peut être légèrement différente,
C'est pour cette raison qu'il faut veiller à tester un site web sur plusieurs navigateurs avant de la mettre en ligne.
```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
HTML, CSS et JavaSCript sont des langages qui permettent de créer des sites Internet.
En HTML5 on écrit la structure et le contenu des pages (titres, sections, paragraphes...), en CSS3 on écrit les éléments de mise en forme visuelle des pages (couleurs, gras, souligné...) et en JS on écrit des éléments d'animation des pages.

```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Un élément HTML est une des composante que l'on utilise pour construire une page HTML.
La plupart des éléments HTML sont des balises.
Un attribut est une des caractéristiques d'un élément HTML.
Un élément HTML peut avoir plusieurs attributs.


```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Dans une page HTML, un Id est unique et ne peut être utilisé qu'une seule fois.
A l'inverse, une même Class peut être attibuée à différents éléments.
Les Id et les Class servent de "marqueurs" pour le CSS.

```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```
C'est le nom de la certification officielle du langage JavaScript (c'est la première idée qui me vient et je ne suis même pas bien sûre de comprendre ce que j'ai écrit mais ça sonne bien)


```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
Pour les rendre plus lisibles pour se faciliter le travail et faciliter la relecture par d'autres devs



```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
Le Margin permet de faire varier la distance entre la bordure d'un élément et les éléments qui sont autour de lui.
Le Padding permet de faire varier la distance entre un élément et sa propre bordure. Si on augmente le padding, il aura l'air plus "joufflu".


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
Je ne comprends pas la question. Je ne vois pas ce que c'est un positionnement CSS.



```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
Dans un langage de programmation donné, une variable est un élément qu'on déclare et qu'on définit pour pouvoir
le manipuler ensuite, dans une fonction par exemple.


```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
Je ne sais pas ce que c'est un type JavaScript.
OK, merci pour le tips.
Les premiers types JS qui me viennent à l'esprit sont les chaînes de caractères et les nombres.
Après ça je cale.

```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
En JS c'est un élément qui permet de définir une condition



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```
Sais pas et en plus ça ne me dit rien :-/



```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
C'est une demande du navigateur vers le serveur, ou bien aussi entre deux serveurs.



```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```
GET pour récupérer de la donnée
POST pour envoyer de la donnée


```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```
Me souviens plus mais ça me dit quelque chose.



```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
Le code 404 : page non trouvée
Le code 300 : redirection
Le code 200 : la requête a fonctionné


```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Le Scrum master s'assure que les bonnes pratiques du Scrum éventuellement adaptées pour le projet sont respectées.
Le Product owner est le représentant du "client" du projet.


```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
Git init pour démarrer la gestion de version dans un répertoire
Git add pour ajouter des éléments dans la staging area
Git status pour voir quels éléments sont ou pas dans la Staging area
Git commit pour créer une nouvelle version à prendre en compte


```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;

        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```
Le résultat est 5.
const sentence est la variable de départ
const words sépare les mots de const sentence
for (...) crée u compteur qui permet de compter les mots qui ont été identifiés dans const words
Return count nous donne le nombre total de mots, soit 5

(Pour info, je ne suis pas très sûre de ce que j'écris)

```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```
const = 'vendredi';
function ('vendredi', 'e') {
    console.log(/e/.exec(const));
};

(Là non plus je ne suis pas trop sûre, j'ai l'impression de mélanger des choses)
```


