## Readings : Object-Oriented Programming, HTML Tables

### [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- > "Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem." - CodeFellows Repo
- > Here's some tips to follow when building your own domain models.

1. > When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. > Model its attributes with a constructor function that defines and initializes properties.
3. > Model its behaviors with small methods that focus on doing one job well.
4. > Create instances using the new keyword followed by a call to a constructor function.
5. > Store the newly created object in a variable so you can access its properties and methods from outside.
6. > Use the this variable within methods so you can access the object's properties and methods from inside.
- Domain modeling is still a concept i've yet to fully learn but this repo provided some really good insight that I could go back and reference throughout Lab 07!

*** 

### Chapter 6: “Tables” (pp.126-145) - From the Duckett HTML book
- This chapter covers how to create tables, the types of informations that suits tables, and how to represent complex data in tables
- Some examples of information used for tables would be sports results stock reports, or train timetables.
- You can think of a table as spreadsheet that contains rows and columns. We'll go over the syntax next!
- Basic Table Structure:
  * `<table>` is used to create a table. The contents of the table wrote out row by row.
  * `<tr>` stands for table row. It's used to indicate the start of each row.
  * `<td>` stands for table data. Each cell of a table is represented using table data elements
  * `<th>` stands for table heading. It used just like `<td>` but it represents the heading cells in a column or row.
  * `<thead>` is where headings of the table are fit into
  * `<tbody>` The body should sit inside the tbody element. Same theory with `<tfoot>` element.
 
***

### Chapter 3: “Functions, Methods, and Objects” (pp.106-144) - From the Duckett JS book
- Creating an object:
  * > The `new` keyword and the object constructor create a blank object. You can then add properties and methods to the object. - Duckett
- Updating an object
  * If you want to update the value of properties you can use dot notation or constructor notation and to delete, use the `delete` keyword.
- Creating many objects
  * In some cases, you will want several objects to represent simlar things.
  * >  Object constructors can use a function as a **template** for creating objects. Firstly, you'll need to create the template with the object's properties and methods.
Example:
-  `function Hotel(name, rooms, booked) {
this.name = name;
this.rooms = rooms;
this.booked = booked;

this.checkAvailability = function() {
return this.rooms - this.booked;
};
} `





 ## End of Notes
