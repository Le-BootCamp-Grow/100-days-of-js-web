# 100 jours de développement JavaScript

## Jour 2 : Variables et structures de contrôle

Déclarer et affecter des variables en JavaScript nous permet de stocker des données en mémoire afin de pouvoir les utiliser dans notre code. Il existe plusieurs façons de déclarer des variables en JavaScript, que nous couvrirons dans cette section.

### Déclaration de variables

En JavaScript, nous pouvons utiliser le mot-clé var pour déclarer une variable. Par exemple :

```Javascript
var maVariable;
```

Nous pouvons également affecter une valeur à la variable en même temps que nous la déclarons :

```Javascript
var maVariable = 'bonjour';
var monAge = 19;
```

En plus de `var`, il existe deux autres façons de déclarer des variables en JavaScript : `let` et `const`. La différence entre `let` et `var` est que `let` est limité à un bloc de code, ce qui signifie qu'il n'est accessible que dans le bloc de code dans lequel il est défini. `const` est similaire à `let`, mais la valeur d'une variable `const` ne peut pas être réaffectée.

Voici un exemple utilisant `let` :

```Javascript
let maVariable = 'bonjour';
let digit = 1234;
let coefficient = 'c';
```

Et voici un exemple utilisant `const` :

```Javascript
const maVariable = 'hello';
const VALEUR_MAX = 9999;
```

Il est généralement une bonne idée d'utiliser const chaque fois que cela est possible, et d'utiliser `let` uniquement lorsque vous avez besoin de réassigner une valeur à une variable.

### Affectation de variables

Une fois que nous avons déclaré une variable, nous pouvons lui attribuer une nouvelle valeur à l'aide de l'opérateur d'affectation `=`. Par exemple :

```Javascript
let maVariable = 'Hello';
maVariable = 'Hello world';
```

Dans cet exemple, nous attribuons d'abord la valeur 'Hello' à la variable `maVariable`. Ensuite, nous réassignons la valeur 'Hello world' à `maVariable`.

Nous pouvons également utiliser les variables pour stocker le résultat d'une expression. Par exemple :

```Javascript
let x = 5;
let y = 6;
let z = x + y;
let carréDeZ = z * z;
```

Dans cet exemple, `z` sera attribué la valeur 11 (5 + 6), et `carréDeZ` sera attribué la valeur 121 (11 * 11).

### Nommer des variables

Il est important de choisir des noms de variables descriptifs et significatifs. Cela rendra votre code plus facile à lire et à comprendre. Il y a quelques règles à suivre pour nommer les variables en JavaScript :

- Les noms de variables ne peuvent contenir que des lettres, des chiffres et des traits de soulignement. Ils ne peuvent pas commencer par un chiffre.
- Les noms de variables sont sensibles à la casse.
- Les noms de variables ne peuvent pas être identiques à un mot-clé JavaScript.

Voici quelques exemples de noms de variables valides :

```Javascript
let maVariable;
let ma_variable;
let maVariable123;
```

Et voici quelques exemples de noms de variables non valides :

```Javascript
let 123maVariable; // ne peut pas commencer par un chiffre
let ma-variable; // ne peut pas contenir de tirets
let while; // ne peut pas être un mot-clé JavaScript
```


Maintenant que nous avons couvert la déclaration et l'affectation de variables en JavaScript, passons à la débogage de structures de contrôle.

### Débogage de structures de contrôle

Les structures de contrôle sont des blocs de code qui nous permettent de contrôler l'exécution de notre programme. Elles nous permettent d'exécuter des sections de code différentes en fonction de certaines conditions, ou de répéter une section de code plusieurs fois.

Les trois structures de contrôle les plus courantes en JavaScript sont les instructions `if-else`, les boucles `for` et les boucles `while`.

### Instructions `if-else`

Les instructions `if-else` nous permettent d'exécuter des sections de code différentes en fonction de si une certaine condition est vraie ou fausse.

Voici un exemple d'instruction `if-else` :

```Javascript
let x = 5;

if (x > 10) {
  console.log('x est supérieur à 10');
} else {
  console.log('x n\'est pas supérieur à 10');
}
```

Dans cet exemple, la condition `x > 10` est vérifiée. Si elle est vraie, le code du premier bloc (`console.log('x est supérieur à 10')`) sera exécuté. Si elle est fausse, le code du second bloc (`console.log('x n'est pas supérieur à 10')`) sera exécuté à la place.

Nous pouvons également inclure des clauses `else if` supplémentaires pour vérifier plusieurs conditions :

```Javascript
let x = 5;

if (x > 10) {
  console.log('x est supérieur à 10');
} else if (x < 5) {
  console.log('x est inférieur à 5');
} else {
  console.log('x est entre 5 et 10');
}
```

Dans cet exemple, la condition `x > 10` est vérifiée en premier. Si elle est vraie, le premier bloc de code est exécuté. Si elle est fausse, la condition `x < 5` est vérifiée. Si cela est vrai, le second bloc de code est exécuté. Si les deux conditions sont fausses, le code dans le bloc else final est exécuté.

### Boucles `for`
Les boucles `for` nous permettent de répéter un bloc de code un nombre spécifique de fois. Elles ont la structure suivante:

```Javascript
for (initialisation; condition; incrémentation) {
  // code à exécuter
}
```

La déclaration d'initialisation est exécutée avant le début de la boucle. Elle est généralement utilisée pour déclarer et initialiser une variable compteur. La condition est vérifiée avant chaque itération de la boucle. Si la condition est vraie, le code dans la boucle est exécuté. Si la condition est fausse, la boucle est arrêtée. La déclaration d'incrémentation est exécutée après chaque itération de la boucle. Elle est généralement utilisée pour mettre à jour la variable compteur.

Voici un exemple de boucle `for` qui compte de 1 à 10:

```Javascript
for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```

Dans cet exemple, la variable `i` est initialisée à 1. La condition `i <= 10` est vérifiée avant chaque itération de la boucle. Si elle est vraie, le code dans la boucle est exécuté (`console.log(i)`). Après chaque itération, `i` est incrémenté de 1. Cela continue jusqu'à ce que `i` soit supérieur à 10, auquel point la boucle est arrêtée.

### Boucles `while`

Les boucles while sont similaires aux boucles for, mais elles n'ont pas un nombre fixe d'itérations. Elles ont la structure suivante :

```Javascript
while (condition) {
  // code à exécuter
}
```

La condition est vérifiée avant chaque itération de la boucle. Si la condition est vraie, le code de la boucle est exécuté. Si la condition est fausse, la boucle est arrêtée.

Il est important de s'assurer que la condition deviendra finalement fausse, sinon la boucle s'exécutera indéfiniment (ce qui est connu sous le nom de boucle infinie).

Voici un exemple de boucle `while` qui compte de 1 à 10 :

```Javascript
let i = 1;

while (i <= 10) {
  console.log(i);
  i++;
}
```

Dans cet exemple, la variable `i` est initialisée à 1. La condition `i <= 10` est vérifiée avant chaque itération de la boucle. Si elle est vraie, le code de la boucle est exécuté (`console.log(i)`) et `i` est incrémenté de 1. Cela continue jusqu'à ce que `i` soit supérieur à 10, à ce moment la boucle est arrêtée.

### Techniques de débogage en JavaScript

Le débogage est le processus d'identification et de correction des erreurs dans votre code. JavaScript offre un certain nombre d'outils et de techniques pour vous aider à déboguer votre code.

`console.log()`

Une des techniques de débogage les plus basiques et utiles est d'utiliser la fonction `console.log()` pour imprimer les valeurs des variables et des expressions. Cela vous permet de voir ce qui se passe à différents points de votre code et peut vous aider à identifier où les erreurs se produisent.

Par exemple :

```Javascript
let x = 50;
let y = 100;
let z = x + y;

console.log(z); // imprime 15
```

### La console JavaScript

La console JavaScript est une interface en ligne de commande fournie par la plupart des navigateurs web modernes. Elle vous permet d'exécuter du code JavaScript et de voir le résultat en temps réel.

Pour ouvrir la console JavaScript dans la plupart des navigateurs, vous pouvez utiliser le raccourci clavier `Ctrl + Maj + J` (sous Windows) ou `Cmd + Option + J` (sous macOS).

Dans la console, vous pouvez entrer du code JavaScript et appuyer sur Entrée pour l'exécuter. Vous pouvez également utiliser la fonction `console.log()` pour imprimer les valeurs des variables et des expressions.

### Outils de débogage

La plupart des navigateurs web modernes proposent également des outils de débogage intégrés qui vous permettent d'inspecter l'HTML et le JavaScript d'une page web et de définir des points d'arrêt dans votre code. Ces outils peuvent être accédés via la console de développeur du navigateur.

Pour ouvrir la console de développeur dans la plupart des navigateurs, vous pouvez utiliser le raccourci clavier `Ctrl + Maj + I` (sous Windows) ou `Cmd + Option + I` (sous macOS).

Ces outils vous permettent d'inspecter l'HTML et le JavaScript d'une page web, de visualiser les valeurs des variables et des expressions, et de définir des points d'arrêt dans votre code. Lorsqu'un point d'arrêt est atteint, l'exécution de votre code est en pause, ce qui vous permet d'examiner l'état de vos variables et de voir ce qui se passe à ce stade de votre code.

### Stratégies de débogage

Lorsque vous déboguez votre code, il est important d'aborder le problème de manière systématique et soigneuse. Voici quelques stratégies qui peuvent vous aider :

- Commencez par identifier le message d'erreur. Cela peut vous donner une idée de ce qui ne va pas.
- Utilisez des instructions console.log() pour imprimer les valeurs des variables et des expressions à différents points de votre code
- Utilisez les outils de débogage fournis par votre navigateur pour inspecter l'HTML et le JavaScript de votre page web et définir des points d'arrêt dans votre code.
- Découpez votre code en morceaux plus petits et testez chaque morceau individuellement pour restreindre l'emplacement de l'erreur.
- Lisez attentivement votre code et recherchez des fautes de frappe, des erreurs de syntaxe ou des erreurs logiques.
- N'hésitez pas à demander de l'aide ou à chercher conseil auprès d'autres développeurs.
- Le débogage peut être un processus difficile mais gratifiant, et c'est une compétence importante pour tout développeur. Avec de l'entraînement et de la patience, vous deviendrez de plus en plus à même d'identifier et de corriger les erreurs dans votre code.