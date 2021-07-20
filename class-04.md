## Readings : 

### Chapter 4: Ch.4 “Links” (pp.74-93) -From the Duckett HTML book
- > "links are the defining feature of the web because they allow you to move from one web page to another - enabling the very idea of browsing or surfing." -Duckett
- Some important jobs of links:
  * Used to surf from one website to another
  * Move from one page to another on same website
  * Move from one part of a webpage to another part of the same webpage
  * links that open in new browser window
  * Links that start up your email program and address a new email to someone
- Writing Links: You create links using the `<a>` element (open/close). You then specify which page you want to link with an `href` attribute. Example: `<a href="http://www.google.com">Google</a>`. Notice the text between tags-this is the test that will render on a webpage with the link embedded into it. This specific link will take you to another website.
- When linking another webpage on your website, you do not need the domain name; you would use a what's called a Relative URL. This means you use your direcotry structure to link your pages; Example: `<a href="music/listings.html">Listings</a>` -Duckett.
- For the rest of the other link types, the syntax remains mostly similar. It's an easy google search if you ever forget it.

### Chapter 15: “Layout” (pp.358-404)
- This chapter discusses:
  * Controlling the position of elements
  * Creating site layouts
  * Designing for different sized screens
- When developing your CSS in accordance with your HTML, it's important to know the difference between a Block-Level Element and an Inline Element! In short, a Block-Level Element starts on a new line and an Inline Element flows in between surrounding text.
- Containing Elements: 
- > If one block-level element sits inside another block-level element then the outer box is known as the **containing** or **parent** element. -Duckett
  * It is pretty common to group multiple elements together inside of a `<div>` element. An example would be your header or your navigation section of the website.
- There are numerous ways to control the positioning of your elements to create the layout you desire.
  * Normal Flow
  * Relative Positioning
  * Absolute Positioning
  * Fixed Positioning
  * Floating Elements

*** 

### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY) -From the Duckett JS book
- > Functions let you group a series of statements together to perform a specific task. If differnt parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). - Duckett
- when creating a function, you give it a name then write your statements inside the curly braces. This is declaring a function: `function sayGoodbye() {document.write('Goodbye!'); }`. Then when you need to call a function later, you write just the name of the function and it will execute the code you declared within it previously.
- Some functions need information to perform its task. This is where you give it **parameters**. The parameters will act like variables; Example: `function getArea(width, height) {return width * height; }` - Duckett
- Calling a function with parameters is slightly different than a normal call for a function. For a function with parameters, you specify the values inside it with paranthesis; Example: `getArea(3, 5);`
- There are also methods to get a single value out of a function or multiple values.

### Article: “6 Reasons for Pair Programming” -From the Duckett JS book

