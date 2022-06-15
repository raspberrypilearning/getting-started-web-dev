## Vocabulary for Web Development

## Web development

+ The **world wide web** or **web** is a vast collection of connected web pages. 

+ A **web page** is a single page of content with a web address or universal resource locator (url). 

+ A **web site** is a group of web pages with the same domain name.

+ A **domain name** is the part of a web address after `http://` or `https://`, for example `projects.raspberrypi.org`.

### HTML

+ The **Hypertext Markup Language (HTML)** language is used to structure a web page so that a web browser (or screen reader) knows what to do with the content.

+ HTML uses **tags** to 'mark up' content so that a web browser or screen reader knows how to present it. Tags start and end with angle brackets and most have a matching end tag. For example, `<h1>` and `</h1>` tags are used to start and end a level one heading. 

+ The different parts of an HTML page are called elements and include tags. `<h1>The Heading</h1>` is a level one heading element.

+ HTML elements can have **attributes** which provide additional information. This example, `<img src="happy.png" alt="A happy face">` has a `src` attribute with a value for the image name and a `alt` attribute with a value for the alternative text to be used if an image cannot be viewed. 


### CSS

+ The **Cascading Style Sheets (CSS)** language  describes exactly how a web page should look.

+ A CSS file contains a list of **rules**. 

+ Each rule has a list of **properties** with values. For example `color: teal` sets the color property to the teal colour. 

+ Each rule has a **selector** which says which HTML elements to apply the rule to. This could be the name of an HTML element or `.classname` where 'classname' is the name of a class that can be applied to HTML elements to use the style. 

+ A CSS **class** is used to apply rules to HTML elements that have that class applied. For example `<section class="primary">` applies the primary class to a section element which means that the properties defined in rules with the `.primary` selector will be used. 

+ A CSS file is often called a **style sheet**. 