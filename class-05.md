## Readings : Images, Color, Text

### Chapter 5: “Images” (pp.94-125) -From the Duckett HTML book
- This chapter covered how to add images to pages, choose the right format, and how to optimize images for the web.
- Pictures are worth a hundred words; so they say. It goes without saying that images are an important tool to create a great experience for you users. 
  * > ... you might want to include a logo, photograph, illustration, diagram or chart... Images should be relevant, convey information, convey the right mood, be instantly recognisable, fit the color palette.- Jon Duckett
- In **HTML**, you want to create a folder within your project dedicated to images for easy access (have a clean file directory).
- Adding images is done with an `<img>` element. `src` tells the browser where it can find the file to the image. `alt` provides a text description of the image in a situation where a user can't see the image. `title` also provides addtional information about the image, specifically when you hoever over the image! A full example would look like this: `<image src="images/guitar.jpg" alt="Fender Strat" title="Fender's most sold guitar is the stratocaster model"/>`.
- Though it's better to style your elements with CSS, you can adjust height & width with HTML by using `width="123* height="123"` inside of your img tag. Deciding where to place an image in your HTML is important for your layout. For example, you can place an image before a paragraph, inside the start of a paragraph, or in the middle of a paraghraph which all have different affects of how it is rendered in the broswers. You used to be able to align your image in old HTML code but that is no longer supported with HTML5; you can do this with CSS instead.
- If you're a front end developer or UX/UI developer, it's important to know your differnt image formats such as GIF and PNG. Both files are used for paticular reasons depending on the type of image you are using. An example of a GIF would be a 'loading' animation. 
  * >  Like GIF images, PNG also have the ability to display transparent backgrounds. In addition to that, PNG files are capable of containing 24bit RGB color palettes and greyscale images. - www.paintshoppro.com

### Chapter 11: “Color” (pp.246-263) -From the Duckett HTML book
- In this chapter, the author covered how to specify colors, color terminology, contrast, and background colors.
- > The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
  * RGB Values: this used describing how much much red, green, and blue you want together to return a paticular color. Example: `color: rgb(100, 90, 100);`
  * HEX Code: A six digit code that represents the same concept as RGB. Example: `color: #ee3e81;
  * Color Names: In CSS, there are 147 predefined color names that can be recognized in browsers. For example: `color DarkBlue;`
- Background-color is another property to create a color. Like mentioned in earlier notes, HTML see's an element as if it were in its own box. With that being said, you manipulate that color of that box to whatever color you;d like using one of the three methods listed above.
- Creating proper contrast between the text and the background is important for readibility so make sure your webpage is easy to read.
- `opacity` is a property used to make an element(s) transparent. You can assign it a value between 0.0(most opaque) and 1.0(most transparent). Example: `opacity: 0.5;`

### Chapter 12: “Text” (pp.264-299) -From the Duckett HTML book
-In this chapter, the author covers size and typeface of text, and differnt text decorations
-With the `font-family` you can select what kind of want you'd like to use for you web page. You can also use Google Fonts to pick a specific font you want that are not default in CSS.
  * It's important to understand that not all Operating Systems will display the font selected... that's why it's important to have multiple fonts selected in case the desired font isn't displayed. For example: `font-family: arial, calibri, gill sans;`
  * If you got to https://www.cssfontstack.com/, this will tell you what fonts can and cannot be read on a specific operating systems in case you are unsure.
- To create a specific font size of an element, you would use `font-size:` and specify what size you want with a unit of measurement such as px, em, %, etc.
- If you'd like to modify text with bold, use `font-weight bold;`. For italic use `font-style: italic;`. For uppercasing/lowercasing text, use `text-transform: uppercase;`. For underline & strike, use `text-decoration:`.
- `text-align:` very common to use. You can align text to left, right, center, and justify.
- IF you'd like like to indent a text, use `text-indent`. You get the point, you can probably remeber most of these properties but if not, it's an easy google search.
- There are also fun properties such as `:hover`, `:active`, and `:focus` that have cool effects to your text to make the site more interactive!

*** 

### JPEG vs PNG vs GIF -Blog Post




 ## End of Notes
