## Readings : Basics of HTML, CSS & JS

### Chapter 2: “Text” (pp.40-61) -From the Duckett HTML book
-With HTML, you have the ability to modify text without having to use CSS; This is called Structural Markup. Examples of this look like adding headings, subheadings, paragraphs, boldness, italics, superscripts,subscripts, lines breaks and horizontal breaks utilizing simple tags. Semantic Markup however is differen't in a sense that it does not affect the structure of your webpage.
- Semantic Markup adds extra information to the webpage. Examples of this would be abbreviations used in your HTML. If i were to abbreviate "United States of America" , I could use `<abbr title="United States of America>USA</abbr>` and if I were to hover over "USA", the user could see what the abbreviation stood for. The same idea is applied to the rest of the Semantic Markup.

### Chapter 10: Ch.10 “Introducing CSS” (pp.226-245) -From the Duckett HTML book
-My favorite quote from this chapter was "The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element." - Jon Duckett. I never thought of CSS that way. Thinkning of this in the back of my head definetly would have helped me in the past. 
-CSS can be used both internally and externally. When using CSS in an HTML document simply use `<style type="text/css">` and `</style>` within your `<head> </head>` tags. Inside the style tags is where you would put your CSS. To link your your external CSS to a HTML file, you simply put `link href="style.css" rel="stylesheet"/>` inside the head tags of your HTML file and write CSS in it's dedicated CSS file. I also learned there is a ton of different CSS selectors to use at your disposal but the most common selectors i've noticed are type, class, ID, and child.

*** 
### Chapter 2: “Basic JavaScript Instructions” (pp.53-84) -From the Duckett JS book
-In this chapter I was introduced to the bread and butter of Javascript. Today I learned that a statement is used as an individual instruction that is finsished with a semi-colon. This tells JavaScript that a step is over and it should move onto the next step. It can also be organized into code blocks utilizing curly braces.
-Just like HTML, you can add comments to your code that can be used to your advantage. When away from your code for a while, it's often easy to forget why you wrote or if a peer views it for the first time, this could also help him/her interpret it. These comments never get ran by Javascript.
-Variables are essential as they are used to store values that can be used later on in your logic as many times as needed. Old syntax for declaring a variable used to be `var`, it's better practice to used `let` and `const` which both serve different purposes.
-There are 6 data types in JS. The most common I've seen used thus far would undefined, Boolean, Number, and String.
  1.undefined
  2.Boolean
  3.Number
  4.String
  5.Bigint
  6.Symbol
The most common I've seen used thus far would undefined, Boolean, Number, and String. These data types are incorporated into variables.
-Arrays are a unique because unlike a variables, it can store mutliple values. Arrays are created with square brackets. Example: `let animals = ['cat', 'dog', 'bird'];`. The rest of the chapter describes how to access and change values in an array.

### Chapter 4: “Decisions and Loops” (pp.145-162) -From the Duckett JS book
