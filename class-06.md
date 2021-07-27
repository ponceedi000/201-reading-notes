## Readings : Problem Domain, Objects, and the DOM

### [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
- Unfortunetly I had to start this reading by looking up the definition of 'problem domain' before further reading into this blog. See below the definition:
- > A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics of an individual's interest, and excluding everything else. - https://softwareengineering.stackexchange.com/questions/125926/what-is-problem-domain
- The author explains that putting together a jigsaw puzzle is similar to coding. Sometimes you get a tough puzzle that can take hours if not days to piece to fully piece together and when you're stuck, you have to figure out where the problem is originating from in order to move foward or complete your project! Sounds like coding in a nutshell to me...
- > We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain. - John Sonmez
- The author states that as programmers, we're often not given complete information about the problem domain.. so from the start, we're already don't have the information we need to understand it. In an opposite scenario, programming becomes **much** easier!
- He says that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

*** 

### Chapter 3: “Object Literals” (pp.100-105) - From the Duckett JS book
- What is an object?
  * > Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names. - Duckett
- In an object, variables become know as properties. 
  * Properties essentially tell us about the object.
- In an object, functions become known as methods.
  * Methods in an object represent tasks that are associated with the object
- **key:** The name of your object is called a key.
- Example of object code from JS Duckett book pg.101:

` var hotel = { name: 'Quay', rooms: 40, booked: 25, gym: true, roomTypes: ['twin', 'double', 'suite'], checkAvailability: function() { return this.rooms - this.booked;}};`
  
- Biggest takeaways:
  * Objects are collections of properties.
  * Properties are a key-value pair
  * Rather than accessing data using an index, we use custom keys.

### Chapter 5: “Document Object Model” (pp.183-242) - From the Duckett JS book
> The Document Object Model specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. - Duckett
- The DOM is unique because it is neither HTML nor JavaScript; DOM is its own entity. It has its own set of rules and it is used by all major web browswers. DOM covers two primary areas:
  1. Making a model of the html page
  2. Accessing and changing the html page
- The DOM Tree is a model of a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.
  1. The document node
  2. Element nodes
  3. Attribute nodes
  4. Text nodes
- In order to access and update the DOM tree, it requires two steps:
  1. Locate the node that represents the element you want to work with
  2. Use its text content, child elements, and attributes
- DOM is not a quick and easy subject to perfect from my understanding but once you fully you fully understand, you will be able to do the following:
  * Select element nodes by their id or class attributes
  * Use DOM queries
  * From an element node, access and update its content using using properties such as textContent and innerHTML or using DOM manipulation
  * Use good practices to keep up with modern browsers and JQuery for older browsers that are inconsistent
 ## End of Notes
