# 100 jours de développement JavaScript

## Jour 1 : Introduction à JavaScript et à l'écosystème de développement web

Bienvenue au premier jour de notre bootcamp de 100 jours de développeur web JavaScript ! Aujourd'hui, nous allons couvrir les bases de JavaScript et de l'écosystème de développement web. Nous commencerons par configurer un environnement de développement, puis nous passerons à la compréhension du rôle de JavaScript dans le développement web. Enfin, nous couvrirons la syntaxe de base et les types de données en JavaScript.

### Mise en place de l'environnement de développement

Avant de pouvoir coder en JavaScript, nous devons configurer un environnement de développement. Cela inclut l'installation d'un éditeur de texte et d'un navigateur web. Un éditeur de texte est un programme qui nous permet d'écrire et de modifier du code. Certaines options populaires incluent Sublime Text, Atom et Visual Studio Code. Un navigateur web est un programme qui nous permet de visualiser et d'interagir avec des pages web. Certaines options populaires incluent Google Chrome, Mozilla Firefox et Safari.

Une fois que vous avez un éditeur de texte et un navigateur web installés, vous êtes prêt à commencer à coder en JavaScript !

Pour configurer votre environnement de développement, vous devez installer un éditeur de texte et un navigateur web. Dans cette leçon, nous utiliserons Visual Studio Code (VS Code) en tant qu'éditeur de texte et Google Chrome en tant que navigateur web.

Suivez ces étapes pour installer et configurer VS Code :

1.  Allez sur le site web de VS Code : https://code.visualstudio.com/
2.  Cliquez sur le bouton "Télécharger" pour votre système d'exploitation (Windows, macOS ou Linux).
3.  Une fois le téléchargement terminé, ouvrez le fichier téléchargé et suivez les instructions pour installer VS Code.
4.  Une fois l'installation terminée, ouvrez VS Code en double-cliquant sur l'icône sur votre bureau ou dans votre menu démarrer.

Suivez ces étapes pour installer et configurer Google Chrome :

1.  Allez sur le site web de Google Chrome : https://www.google.com/chrome/
2.  Cliquez sur le bouton "Télécharger Chrome".
3.  Une fois le téléchargement terminé, ouvrez le fichier téléchargé et suivez les instructions pour installer Google Chrome.
4.  Une fois l'installation terminée, ouvrez Google Chrome en double-cliquant sur l'icône sur votre bureau ou dans votre menu de démarrage.

Vous êtes maintenant prêt à commencer à coder en JavaScript !

Pour créer un nouveau fichier dans VS Code, cliquez sur le menu "Fichier" puis sélectionnez "Nouveau fichier". Vous pouvez ensuite taper votre code dans l'éditeur et enregistrer le fichier en cliquant sur le menu "Fichier" et en sélectionnant "Enregistrer". Pour afficher les résultats de votre code, ouvrez le fichier enregistré dans Google Chrome en le faisant glisser et en le déposant dans la fenêtre du navigateur. Ne vous inquiétez pas si vous ne trouvez pas votre chemin tout de suite. Vous vous familiariserez avec les choses au fur et à mesure de la progression du programme.

### Comprendre le rôle de JavaScript dans le développement web

JavaScript est un langage de programmation principalement utilisé pour la création d'applications web interactives. Il est souvent utilisé conjointement avec HTML et CSS pour créer des pages web dynamiques et interactives.

JavaScript est généralement exécuté dans le navigateur web de l'utilisateur, ce qui signifie qu'il peut être utilisé pour créer des éléments interactifs sur une page web tels que des menus déroulants, des fenêtres contextuelles et des formulaires réactifs. Il est également utilisé pour ajouter des fonctionnalités aux pages web, telles que la possibilité de valider les entrées de formulaire, de créer des animations et d'envoyer et de recevoir des données d'un serveur.

En tant que langage de programmation, JavaScript permet aux développeurs de créer des sites web et des applications web interactives et dynamiques. C'est un outil essentiel pour le développement front-end, car il permet aux développeurs de créer des éléments interactifs et réactifs sur une page web.

JavaScript est également utilisé pour le développement back-end, en utilisant des technologies telles que Node.js. Cela permet aux développeurs d'utiliser JavaScript pour créer des applications côté serveur et des API (Interfaces de Programmation d'Applications), qui peuvent être accessibles par des applications côté client telles que des applications web et mobiles.

JavaScript a une grande et active communauté de développeurs, avec de nombreuses bibliothèques et frameworks disponibles pour aider les développeurs à créer des applications web de manière plus efficace. Certaines bibliothèques et frameworks populaires comprennent React, Angular et Vue.js.

En plus de son utilisation dans le développement web, JavaScript peut également être utilisé pour créer des applications de bureau et mobiles en utilisant des technologies telles que Electron et Cordova.

Dans l'ensemble, JavaScript joue un rôle crucial dans le développement des applications web et mobiles modernes et est une compétence essentielle à maîtriser pour tout développeur web.

### Syntaxe de base et types de données en JavaScript:

Maintenant que nous avons une compréhension de base du rôle de JavaScript dans le développement web, examinons la syntaxe de base et les types de données du langage.

JavaScript utilise une syntaxe de style C, ce qui signifie qu'il utilise des accolades pour encadrer des blocs de code et des points-virgules pour marquer la fin d'une instruction.

JavaScript a plusieurs types de données, notamment les chaînes de caractères, les nombres, les booléens et les objets.

Les chaînes de caractères sont utilisées pour représenter du texte et sont entourées de guillemets simples ou doubles. Par exemple:

```Javascript
let name = "Charlie";
let message = 'Hello, world!';
```

Les nombres peuvent être des entiers ou des valeurs à virgule flottante. Par exemple:

```Javascript
let age = 35;
let temperature = 72.5
let pi = 3.14159;
```

Les booléens représentent les valeurs true ou false. Par exemple:

```Javascript
let isValid = true;
let isOld = false;
let isExpired = false;
```

Les objets sont des collections de paires clé-valeur et sont utilisés pour stocker des données complexes. Par exemple:

```Javascript
let personne = {
  nom: "John",
  age: 35,
  isMale: true
};
```

Examinons de plus près à quoi ressemble la programmation en JavaScript.

Voici un exemple de fonction simple en JavaScript:

```Javascript
function saluer(name) {
  console.log("Bonjour, " + name + "! Enchanté de vous rencontrer !");
}

saluer("Paula"); // Sortie: "Bonjour, Paula! Enchanté de vous rencontrer !"
```

Dans cet exemple, la fonction saluer prend en paramètre un seul nom et affiche un message de salutation dans la console. La fonction est ensuite appelée avec l'argument "Paula", ce qui entraîne la sortie "Bonjour, Paula! Enchanté de vous rencontrer !".

Voici quelques exemples de travail avec des chaînes de caractères en JavaScript:

```Javascript
let firstName = "Mickey";
let lastName = "Mouse";

console.log(firstName + " " + lastName); // Sortie: "Mickey Mouse"

console.log(firstName.length); // Sortie: 6

console.log(lastName.toUpperCase()); // Sortie: "MOUSE"

console.log(firstName.startsWith("M")); // Sortie: true

let welcome = "Bienvenue dans la formation de 100 jours de développement JavaScript."
let welcomeNote = "Bonjour, M." + firstName + " " + lastName.toUpperCase() + "! " + welcome

console.log (welcomeNote); 
//Sortie: Bonjour, M. Mickey MOUSE! Bienvenue dans la formation de 100 jours de développement JavaScript.
```

Dans cet exemple, nous déclarons d'abord deux variables, `firstName` et `lastName`, et leur attribuons des valeurs de chaîne de caractères. Nous utilisons ensuite la concaténation de chaînes pour combiner les deux variables et afficher le résultat dans la console. Nous utilisons également la propriété `length` pour obtenir la longueur de la chaîne `firstName`, la méthode `toUpperCase` pour convertir la chaîne en majuscules, et la méthode `startsWith` pour vérifier si la chaîne commence par une lettre particulière.

De plus, nous déclarons deux variables, `welcome` et `welcomeNote`. Nous attribuons une valeur de chaîne représentant un message de bienvenue à la première, puis nous créons un message de bienvenue complet avec la lettre en utilisant la concaténation de chaînes pour combiner les trois variables déclarées précédemment. En fin de compte, nous affichons le résultat dans la console.

Voici quelques exemples de travail avec des nombres en JavaScript :

```JavaScript
let x = 5;
let y = 2.5;

console.log(x + y); // Sortie: 7.5

console.log(x - y); // Sortie: 2.5

console.log(x * y); // Sortie: 12.5

console.log(x / y); // Sortie: 2

let pi  = 3.14159;
let r = y;
let surfaceCercle = pi * r * r;

console.log(surfaceCercle); //19.6349375
```

Dans cet exemple, nous déclarons deux variables, `x` et `y`, et leur attribuons des valeurs numériques. Nous utilisons ensuite des opérateurs arithmétiques pour effectuer des calculs de base avec ces variables et enregistrons les résultats dans la console. De plus, nous déclarons trois nouvelles variables, `pi`, `r` et `surfaceCercle`. Nous attribuons à `r` la valeur de `y` et attribuons à `surfaceCercle` la formule permettant de trouver l'aire d'un cercle en utilisant des opérateurs arithmétiques pour effectuer des calculs de base avec les variables `pi` et `r`. Nous enregistrons ensuite le résultat final dans la console.

Voici quelques exemples de travail avec des objets en JavaScript :

```Javascript
let personne = {
  prenom: "Mickey",
  nom: "Mouse",
  age: 35,
  isMale: true
};

console.log(personne.prenom); // Sortie : "Mickey"

console.log(personne["nom"]); // Sortie : "Mouse"

personne.age = 36;

console.log(personne.age); // Sortie : 36

delete personne.isMale;

console.log(personne.isMale); // Sortie: undefined
```

Dans cet exemple, nous déclarons une variable `personne` et lui attribuons une valeur objet avec quatre propriétés : `prenom`, `nom`, `age`, et `isMale`. Nous accédons aux propriétés de l'objet en utilisant la notation de point (par exemple, `personne.prenom`) ou la notation de crochets (par exemple, `personne["nom"]`). Nous pouvons également modifier les propriétés de l'objet en leur attribuant de nouvelles valeurs (par exemple, `personne.âge = 36`) ou les supprimer en utilisant l'opérateur delete (par exemple, `delete personne.isMale`).

Cela conclut notre introduction à JavaScript et à l'écosystème de développement web. Dans la prochaine leçon, nous plongerons plus profondément dans le langage et commencerons à apprendre ses concepts fondamentaux tels que les variables et les structures de contrôle.

> N'oubliez pas de jouer avec les exemples de code fournis pour mieux comprendre ces concepts.