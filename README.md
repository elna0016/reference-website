# web-design
1- Naming convention for all filenames, paths and folders

. For the naming all files should be kowercase, no spaces, but we can add dashes, the name of the folder should match the name of file or smiliar, also for the path, all files should be in one folder so it can be easily linked to index.html

 2- Best practices for commit messages

 . In order to commit your messagesthere is 5 steps which is:
 Minimum 3 words & 10 characters
 Proper spelling & grammar
 Capital starting letter, no period
 Must start with an imperative verb: Create, Fix, Add, Solve, etc.
 Pretend every commit starts with the phrase: “This commit will…”

 3- What is HTML?

 . Html is a the coding language used to describe the content of websites.

 4- Proper syntax for HTML tags

 . The proper way to start syntax for HTML tags is to always start with < , then add list of characters without spacing , after that ended up with >

 5-Explain or demonstrate commonly used html tags/elements:
.headings: h1-h6 this tages define headings, the h1 is defines the  most important heading when its h6 is defines the least important thing.

.p : p is a tag that used for paragraph <p></p>

. lists: ul, ol, dl : the ul tag is to define the unordered list item , the ol tag is used when the list is ordered, the dl tag is used to group name value pairs of information.

. a : is to link to another files or folder.

. img: is add an image.

. q : defines short quotation.

. Blockquote: defines long quotatiom.

. cite : to defines the title of work.

. em : the tag marks a text that has stress emphasis.

. strong : to makee the tex bold.
. b: to bring attention to the reader.

. i : italics style.

small : smaller text.

6-Explain block Elements and also explain the list of block elements and why they are used from below:

. html : wrap the whole entire HTML content.

. head: Give your content structure.

. body: is a container element that surrounds all the content visible to the user in the web browser, including headings, paragraphs, lists, images, and other tags.

. header: is a container for a data,

. nav: the tag defines a set of navigation links.

. main: The definition of tag main is specifies the main content of a document , browswer support the number in the table specify the first browser version that fully supports the element.

. section: defines a section in docoument, and it used to support the global Attributes in HTML.

. article: to represent an article.

. div: It is a generic container tag, they use it to group various tag of HTML so styles can be applied to it.

. aside: the definition of aside is provide information to the source, used to describe the primary object of the web page more briefly.

.footer: It can defines a footer in a document or section in HTML, also a footer at the bottom can includes any final information related to the content in the section.

. span: Is a tag to group elements for styling purposes, and it used to change font size, color and background color.

. small : defines smaller text such as copy-right, ir other small comments.

Explain why accessibility is important and also explain the accessibility properties like:
landmark roles
aria labels
image alternative texts

7- Explain why accessibility is important and also explain the accessibility properties like:

. Accessibilty is importatn because it writes HTML code, it makes your HTML code semantic as possible, also it provide the user a good way to navigate and interact with the site.

. landmark roles: it helps those using screen readers to jump directly to specific sections within our sites.

. aria labels: attribute provides the user with a non-visual label that will only be announced by screen readers 

. image alternative texts: this alternative text has to be added to the image, also image alternative texts is a written copy that perfrom in place of an image on webpage.

8- What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)

What is CSS and how can we implement CSS to our html file ? 

 . Css , Cascading Style Sheets , is to style the webpage, with layout and color also style the size of the text and font.
 This is an example for implamenting css to html file :
 <!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

9- What is the difference between CSS property and value (write explanation and an example code)?

. Css is includes proper way of value pair, when it a value can only include either single integer or keyboard .

10- Why do we use border-box property in CSS?

. The reason why we use border box is because the the content box shrinks to make space for both padding and border, however,  seting your element width to 200 pixels, border-box it can makes  that the content, padding, and borders fit in this number.

11-Explain different type of ways we can add spacing to an element?

. There is 4 ways to make spcae to an element :
1- padding-top.
2- padding right.
3- padding-bottom.
4- padding-left.

12- What is the main difference between margin and padding?

. Padding is space inside the content, but margin is the space outside of the content.

13- What are different types of display properties?

Here are different type of display properties:

. inline: An element it used to show it as an inline element.
  block: It used to view an element as a block element.
  contents: It used to removes the container.
  flex: it  used to view an element as a flex container at the block level.
  grid: it used to view an element as a grid container at the block level.

14- Write a brief explanation of flexbox property

. Flexbox helps Css looks good with fonts , size, layout, spacing, of an elements.

15- What are different types of flexbox properties and what is the major difference between them?

Here is all type of flexbox property:

1-flex-direction : it describes in which direction the container wants to stack the flex items.
2-flex-wrap: it tells the content wheather the flex should be wrap or not.
3-flex-flow: its  property for setting both the flex-direction and flex-wrap.
4-justify-content: is used to align the flex items in the content.
5-align-items: is used to align the flex items in the content.
6-align-content: is used to align the flex lines in the content

16- Explain with code the use of flexbox property on a parent element and also explain the sub?

for the flex-direction: 

. flex-container { - defines as using the flex or inline-flex values of the display property on the parent item.
  display: flex; to enalble flexbox
  flex-direction: column- to make the content in column way
}

for the flex-wrap: 

.flex-container { - defines as using the flex or inline-flex values of the display property on the parent item.
  display: flex; to enable flexbox
  flex-wrap: wrap; control whether the flex container is a single-line or multi-line layout.

}

for the flex-flow:

.flex-container { - defines as using the flex or inline-flex values of the display property on the parent item.
  display: flex; eanble the flexbox
  flex-flow: row wrap; - used for both flex-direction and flex-wrap
}

for the justify-content:
 
 flex-container { -defines as using the flex or inline-flex values of the display property on the parent item.
  display: flex; eanble flex box
  justify-content: space-between; - make space between
}

for the align-items:

. flex-container {- defines as using the flex or inline-flex values of the display property on the parent it
  display: flex; - to eanble flex box
  height: 200px; - the size of the content
  align-items: center; the content has to be in the center
}

for align-content:

. flex-container {
  display: flex; defines as using the flex or inline-flex values of the display property on the parent it
  height: 600px; size of the box
  flex-wrap: wrap; to wrap the content 
  align-content: space-between:  value displays the flex lines with equal space between them:
}

17- What is CSS grid property?

. Css grid makes you lay contentin 2 ways either rows or culomns, it makes it easier to design.

18- What is the difference between display: flex and display: grid?

. Basically, flexbox used to create flebox container , when is display: grid used to create layout based on rows and columns.

19- What sub-property we use to divide elements in CSS Grid properties?

. CSS grid gap is used to divide element.

What unit we use to fractionally divide the element width in CSS Grid property? hat are others unit we can use alternatively? (Write a code example)

. Fr, which is " Fraction', and there's more such as pixel (px), percent (%), em, and rem,

. first example:
<!DOCTYPE html>
<html>
<head>
<style>
p {
  font-size: 16px;
  line-height: 2em;
}

20- What is the area property in CSS grid we use for the child elements?

. The grid-area CSS propertis is specifing  the location and the size of a grid item in a grid layout.

21- Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

 . The gap property can display grid to displaying empty columns , here is an example ;
  
  .grid-container {
  display: grid;
  column-gap: 50px;
 }

 22- Explain the steps to add google fonts to your CSS file and how will you link it to the html file.?

. 1- Find the font and click on the card with the font, then, click  the plus sign, then Select the stylr of your choice.

  2-Next on the right side, you'll see a container with the name Selected family .

  3-Click "Embed"  botton and choose the <link> and then Copy/paste the codes you need.

