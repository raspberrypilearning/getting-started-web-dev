## Create your first web page

In order to prepare for facilitating this path you can have a go at creating your own webpage. The [Intro to Web](https://projects.raspberrypi.org/en/pathways/web-intro) uses the Trinket online editor so there is no software to install. 

**Tip:** If you will be using Trinket in a school, library or other place that has internet filtering then check you are able to access Trinket. See the [Trinket FAQ](https://trinket.io/faq){:target="_blank"} for more information. 

In this step you will add HTML and CSS using the same approach as in our web projects. 

--- task ---

Open this [starter project](https://trinket.io/library/trinkets/d048a9e878){:target="_blank"}. It will open in a separate browser tab.

You will need to switch between these instructions and the editor. 

--- /task ---

--- task ---

Trinket will open the `index.html` page. 

Add the highlighted code:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 15
line_highlights: 16
---
<body>
    <h1>The heading</h1>
</body>

--- /code ---

**Notice:** The name of the file you need to edit is displayed and the line numbers and highlighted code show the changes you need to make. 

--- /task ---

Trinket will automatically update the web page output. 

--- task ---

**Test:** Check that your title appears in the result area of Trinket. 

--- /task ---

--- task ---

Now click on the `style.css` file tab in the Trinket editor. The file will be empty. 

Add the following CSS **rule**:

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 15
line_highlights: 16
---
h1 {
    color: teal;
    text-align: center;
}
--- /code ---

--- /task ---

--- task ---

**Test:** Check that your heading has changed colour and is centered. 

--- /task ---