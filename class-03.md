## Readings : HTML Lists, Control Flow with JS, and the CSS Box Model

### Chapter 3: “Lists” (pp.62-73) -From the Duckett HTML book
- In HTML, you can create about 4 different types of lists for things like cooking recipes, legal contracts, or anything along those lines. The first example would be an "ordered list" which would present numerical bullet points using `<ol> </ol>`. Then we have "unordered lists" which presents regular bullet points using `<<ul> </ul>`. Then comes "definition lists" which usually used to provide a definition for a word inside a list using 3 types tags: `<d1> or <dt> or <dd>`. The finally you have nested lists which are basically lists inside of lists. It's important to note that once you've declared using one of these lists tags that you also include `<li> </li>` for each bullet point.

### Chapter 13: “Boxes” (pp.300-329) -From the Duckett HTML book
- In CSS, it recognizes each HTML: element as if it has its own box. You can usue differen't properties to control the dimension of a box as well as it's borders, margin, and padding. There are also differnt ways hide certain properties which comes in handy when attempting responsive design for mobile devices or anything else other than a desktop style viewport. Block level boxes can be made into inline boxes or vice versas which is important when creating a wepage's layout. Then finally, you can also do everything I just stated with images as well; introduced in more recent years.

*** 

### Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73) -From the Duckett JS book
- Arrays are a really interesting topic. It is basically a special kind of variable that doesn't just store one value but can store numerous amounts a differnt types of values! Arrays can be identified with square brackets and values inside them like: `let food equal = ['pizza', 'tacos', 'spaghetti'];
- Numbering items in an array: we refer to items within our arrays with index's. If you have 3 values within an array, that would 2 indexes. The first value always starts with 0 when refering to index's. You can access items in an array by calling out the index you'd like to see such as `food[2];` which output as 'spaghetti'. tho figure how many items are inside your array, you would do `food.length;`.
- Arrays are pretty cool too because you can change any values inside at any point in time like so `food[1] = 'cereal';` which now make your array: `['pizza', 'cereal', 'spaghetti']`.

### Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182) -From the Duckett JS book
- In my previous notes, I covered conditional statements and how they allow your code to make decisions about what direction it will run. We used comparison operators and logical operators to create these conditional statements. We also covered if, else if, and else.
- Loops have now been introduced at this point in time. "Loops check a condition. If it returns true, a code block will run." Then will be checked and repeat itself again and repeat itself and if the code runs true again, it'll repeat again until the condition is returned false.
- These are the three most common loops: For, While, and Do While.
- For: If you need to run a code a specific amount of times, you want to use a For Loop. 
- While: If you're unsure how many times your code needs to run, you will use a While Loop.
- Do While: Very similar to the While Loops except it will run the code inside your curly brackets at least once even if the condition is false.
- The most fun to write in my opinion is the For Loop which looks like: "`for (lest i = 0; i <10;, i++) {document.write(i);}`" (Intialization: let i + 0; | Condition: i < 10; | Update: i++)

