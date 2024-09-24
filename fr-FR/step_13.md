## Vocabulaire du développement web

## Développement web

- Le **World Wide Web** ou **web** est une vaste collection de pages web connectées entre elles.

- Une **page web** est une page unique de contenu dotée d'une adresse web ou d'un Universal Resource Locator (URL).

- Un **site web** est un groupe de pages web portant le même nom de domaine.

- Un **nom de domaine** est la partie d'une adresse web après `http://` ou `https://`, par exemple `projects.raspberrypi.org`.

- Un **développeur web** ou **développeur front-end** est une personne qui crée des sites web en utilisant HTML, CSS et JavaScript.

### HTML

- Le langage **Hypertext Markup Language (HTML)** est utilisé pour structurer une page web de manière à ce qu'un navigateur web (ou un lecteur d'écran) sache ce qu'il doit faire avec le contenu.

- Le langage HTML utilise des **balises** pour « baliser » le contenu afin qu'un navigateur web ou un lecteur d'écran sache comment le présenter. Les balises commencent et se terminent par des chevrons et la plupart d'entre elles ont une balise de fin correspondante. Par exemple, les balises `<h1>` et `</h1>` sont utilisées pour commencer et terminer un titre de niveau 1.

- Les différentes parties d'une page HTML sont appelées **éléments** et comprennent des balises. `<h1>L'en-tête</h1>` est un élément d'en-tête de niveau 1.

- Les éléments HTML peuvent avoir des **attributs** qui fournissent des informations supplémentaires. Dans cet exemple, `<img src="happy.png" alt="A happy face">` a un attribut `src` avec une valeur pour le nom de l'image et un attribut `alt` avec une valeur pour le texte alternatif à utiliser si l'image ne peut pas être visualisée.

- Les éléments peuvent être des éléments de niveau **inline** ou **block**. Un élément **inline** est un élément qui se trouve à l'intérieur d'une phrase. Par exemple, `<strong>` crée un texte en gras. Un élément **block** est un bloc entier de HTML, comme un `<section>` ou un `<blockquote>`.

### CSS

- Le langage **Cascading Style Sheets (CSS)** décrit exactement l'apparence d'une page web.

- Un fichier CSS contient une liste de **règles**.

- Chaque règle comporte une liste de **propriétés** avec des valeurs. Par exemple, `color: teal` attribue à la propriété colour la couleur teal.

- Chaque règle possède un **sélecteur** qui indique à quels éléments HTML appliquer la règle. Il peut s'agir du nom d'un élément HTML ou de `.classname` où 'classname' est le nom d'une classe qui peut être appliquée aux éléments HTML pour utiliser le style.

- Une **classe** CSS est utilisée pour appliquer des règles aux éléments HTML auxquels cette classe est appliquée. Par exemple, `<section class="primary">` applique la classe primaire à un élément de section, ce qui signifie que les propriétés définies dans les règles avec le sélecteur `.primary` seront utilisées.

- Un fichier CSS est souvent appelé **feuille de style**.

- CSS peut utiliser des **variables** pour contenir des données sur des éléments qui peuvent changer, comme la police et les couleurs de la police. L'utilisation de variables permet de modifier plus rapidement le style d'une page entière, car il suffit de changer ce qui est contenu dans la variable.

- CSS permet de créer des **animations**. C'est le cas lorsque le style d'un élément passe d'un style à un autre au cours d'une période donnée. Des effets sympas, tels que des pulsations, peuvent être obtenus à l'aide d'animations CSS.
