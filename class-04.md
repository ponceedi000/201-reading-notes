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

### Article: “6 Reasons for Pair Programming” -Allie Grampa
- THis article by Allie G. was very insightful. It talks about the major advantages to pair programming. What is pair programming? It's a method to working on coding project with more than one person involved. It often connects with the "two heads are better than one" concept.
- How does it work? Well, there are multiple types of styles to it but most commonly you have the **Driver** and the **Navigator**. The Driver is the one with his hands on the keyboard, working the text editor and utilizing all of the essential tools required as a programmer. The Navigator is the one guiding the driver in the right direction but isn't touching the machine.
  * The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.
- Why pair program? It requires developers to "explain out loud what the code should do, listen others' guidance, read code that other have written, and write codes themselves."-Allie G.
- There are many benefits to paired programming but here are the biggest ones:
  * Greater efficiency: Some people think this makes coding slower but in reality, you catch mistakes much quicker this way which will save time in the long run!
  * Engaged collaboration: This means that experience is more engaging than if you were doing this on your own. Your less prone to procrastinating too!
  * Learning from fellow students: This goes without saying... but you'll never know everything! You and your coding partner may have the oppertunity to share knowledge a long the way to one another which builds your skills even more.
  * Social Skills: This will help build your communication skills later down the road when you eventually work with a bigger team! Employers like to hire programmers who can work well with others!
  * Job Interview readiness: Did you know that a common step in many interviews inolves paired programming with a current employee and the applicant? I didn't know that until now!
  * Work Environment readiness: Many companies who hire fresh CS degree personnel often have to spend extra time and resources on teaching them how to deliver a product vs Code Fellows graduates who are **already** familiar with how pari programming works!
 
 ## End of Notes
