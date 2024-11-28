## Créer ta première page web

Pour te préparer à faciliter ce parcours, tu peux essayer de créer ta propre page web. Le parcours [Intro au web](https://projects.raspberrypi.org/fr-FR/pathways/web-intro) utilise le Code Editor, il n'y a donc pas de logiciel à installer.

Dans cette étape, tu ajouteras du HTML et du CSS en utilisant la même approche que dans nos projets web.

\--- task ---

Ouvre ce [projet de démarrage](https://editor.raspberrypi.org/fr-FR/projects/gswd-starter){:target="_blank"}. Il s'ouvrira dans un autre onglet du navigateur.

Tu dois passer de ces instructions à l'éditeur.

\--- /task ---

\--- task ---

Le Code Editor ouvre la page `index.html`.

Ajoute le code en surbrillance :

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 15
line_highlights: 16
--------------------------------------------------------

<body>
    <h1>Le titre</h1>
</body>

\--- /code ---

\*\*Remarque :\*\*le nom du fichier que tu dois modifier s'affiche et les numéros de ligne ainsi que le code surligné indiquent les modifications que tu dois apporter.

\--- /task ---

\--- task ---

**Test :** clique sur **Run** et vérifie que ton titre apparaît dans la zone de résultat de Trinket.

\--- /task ---

\--- task ---

Clique maintenant sur l'onglet du fichier `style.css` dans le Code Editor. Le fichier est vide.

Ajoute la \*_règle_ CSS suivante :

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 15
line_highlights: 16
--------------------------------------------------------

h1 {
color: teal;
text-align: center;
}
\--- /code ---

\--- /task ---

\--- task ---

**Test :** vérifie que ton titre a changé de couleur et qu'il est centré.

\--- /task ---
