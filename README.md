# project-1

This is my first project

# things to learn

## HTML

##### what are html tags?

names of the specific html elements (they are contained in brackets).

---

##### what are html attributes?

html attributes are created for specific tag manipulation purposes. For example we have:

```html
<div>
  <h1 class="my-headline">Who We Are</h1>
  <h1>Life At Github</h1>
</div>
```

And for this html element the attribute is `class` we give him a value `my-headline` after which we are able to change current `h1` styles from CSS level, without affecting the other tag without the same class value.

---

##### what is the role of head and body?

We use EVERY time those elements!!!! (ONCE only in every .html file)
they both contain the most amount of elements, a code can work without them but it will look un professional and har to understand

---

##### what type of tags should be in body?

The visible part of the website, for example:
headings, texts, hyperlinks, banners, images, videos, contact forms, etc.:

---

##### what type of tags should be in head?

The part of website which is not visible for user, for example:
meta , link , title , style , script , noscript , and base

---

##### when and how should tags listed below be used?

| HTML Tag           | When and How should be used                                                                            |
| ------------------ | ------------------------------------------------------------------------------------------------------ |
| html               | defines the area in which html document exists                                                         |
| head               | contains the data of the website inside it use it at the beginning of the code, right after "html" tag |
| title              | defines html document's name and it's visible on browser current tab                                   |
| meta (description) | provides important information about the document and it's visible on google when you search website   |
| meta (keywords)    | hashtags - helps to find easier the website on google                                                  |
| body               | contains the main content of the document                                                              |
| header             | heading that differentiates the information inside of it from the rest of the text (outside of `main`) |
| main               | specifies the main content of the document                                                             |
| section            | just a section - commonly used inside `main`                                                           |
| footer             | website's footer, should be used at the bottom (outside of `main`)                                     |
| div                | contains text and other things can be used whenever and wherever you wish                              |
| span               | inline-block element - the element that can be used in h1,h2,h3,h4,h5,h6,p etc :)                      |
| ul                 | unordered list                                                                                         |
| ol                 | ordered list                                                                                           |
| li                 | used in representing items in a list used in "ol", "ul", "menu"                                        |
| h1                 | headings, h1 biggest by default, size can be changed, used to add secondary or tertiary headings       |
| h2                 | headings, size can be changed, used to add secondary or tertiary headings                              |
| h3                 | headings, size can be changed, used to add secondary or tertiary headings                              |
| h4                 | headings, size can be changed, used to add secondary or tertiary headings                              |
| h5                 | headings, size can be changed, used to add secondary or tertiary headings                              |
| h6                 | headings, h6 smallest by default, size can be changed, used to add secondary or tertiary headings      |
| a                  | hyperlink <a href = "URL_or_PATH">Link Name</a>                                                        |
| br                 | break - new line                                                                                       |

## HTML & CSS

---

##### how to link CSS to HTML?
to link css to html you need to type in this command into the index.html:
```html
<link rel="stylesheet" type="text/css" href="reset.css" />
```
---

##### what is the prioritization of linked files
the file that is linked the lowest has the highest prority, the file with a higher priority overrides anything contradicting that the less prioritized file has with the more prioritized one.

---

## CSS

---

##### what is css class? (what is the character)
css style is an attribute that defines a class of html elements  in order to style and format those elements with css, to use a class you input the character "."

---

##### what is css id? (what is the character)
css id uses the id of an html to select a specific element, the id for an element is unique in a page, to select the id use thee character "#"
##### what is the proper structure for css blocks?
the proper stucture of css block is like this:
```html
<body>
  <section>
    <p>This is a paragraph!</p>
  </section>
</body>
```
```css
body {
  background: beige;
}

section {
  display: block;
  width: 400px;
  height: 160px;
  background: lightgray;
}

p {
  width: 50%; /* == 400px * .5 = 200px */
  height: 25%; /* == 160px * .25 = 40px */
  margin: 5%; /* == 400px * .05 = 20px */
  padding: 5%; /* == 400px * .05 = 20px */
  background: cyan;
}
```
it has to contain a proper structure and contain all of the tags needed

---

##### how cascading works in CSS? [CSS prioritization] (probably video)

---

##### (BONUS) find CSS reset defaults file and integrate to HTML

---

##### what are attribute and value in CSS

---

##### find out what do these attributes do:

| Attribute        | What does it do? |
| ---------------- | ---------------- |
| color            | TODO             |
| background-color | TODO             |
| font-size        | TODO             |
| font-weight      | TODO             |
| width            | TODO             |
| height           | TODO             |
| max-width        | TODO             |
| max-height       | TODO             |
| border           | TODO             |
| border-radius    | TODO             |
| text-decoration  | TODO             |
| margin           | TODO             |
| padding          | TODO             |


---

##### (EXTRA BONUS) what is Flexbox?

---
