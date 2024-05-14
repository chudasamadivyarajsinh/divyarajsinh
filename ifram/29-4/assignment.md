### (1) are the html tags are elements the same thing?
#### ans.
**html tags:-** tags are the building blocks of html markup.they are used to define different parts of the content and are enclosed within angel brackets such as '< p >' , '< div >' , '< a >' etc.
 html tags are the specific keywords or phrases used to create and define html elements.each tag is enclosed in angle brackets like <u>tagname</u> the opening tag indicates the start of an elements,and the closing tag,which is the same as the opening tag but with a forward slash before the tag name,indicates the and of an elements.
 tags are the starting and ending parts of an html elements.they begin with < symbol and end with > symbol. whatever written inside < and > are called tags.
 **example:-**`<i> this is italic </i>`
 **html elements:-** elements are made up of a start tag,content and an end tag.if applicable they consist of everything between the opening and closing tags, including the tags themselves and any content nested within them for  
 **example:-** `<p>` is a tag ,but`<p>`this is a paragraph.`<p>`is paragraph element.
 html elements refer to the overall structure and content of a web page for 
 elements enclosed the contents in between the tags.they consist of some kind of structure or expression. it generally consists of a start tag content and end tag.


 ### (2) what are tags and attributes in html?
 #### ans.
   tag and attributes are two concepts related to html.the main difference between tag and attributes is that a tag is a way of representing an html element in the program,while an attribute is a way of describing the characteristics of an html element. 

**<u>html tags:-</u>** html tags are a set of predefined characters used in an html document.tags are used to define content types and some time for formatting the content web brawsers don't display html tags on a webpage.
html tags and attributes are fundamental components used to structure and define content on a web page.tags are used to enclose and define elements and attributes provid additional information about those elements.
now that we've got a basic understanding of html,lets talk about tags.tags are the building blocks of html.they're used to define the structure and content of a web page.
imagine youre writing a letter and you want to lable certain parts of the letter,like the date,the recipient and the body of the letter.you might use brackets and labels to do this,like so:-[date],[recipient],[body].
html tags work in a similar way.they're used to label and organize the content of a web page.tags are enclosed in angel brackets like this:-< tag name >.most tags have an opening tag and enclosing tag,with the content in between. the content in between.the closing tag has a forward slash before the tag name,like this:-</ tagname >.

**example :-** < html></ html>,< body></ body>,< table></ table>,< audio></ audio>,< video></ video>,< article></ article>,< p></ p>,< a></ a>, etc.

**<u>html attributes:-</u>** 
* all html elements can have attributes 
* attributes provide additional information about elements
* attributes are always specified in the start tag
* attributes usually some in name/value pairs like:- name="value"

**the href attributes:-** the < a > tag define a hyperlink.the href attributes specifies the URL of the page the link goes to:-
**example:-** 
  ```html     
       <html>
    <head>
        <title>welcome</title>
    </head>
    <body>
        <a href="https://media-cdn.tripadvisor.com/media/photo-s/1d/f5/78/04/serenade-restaurant-bar.jpg ">
        </body>
        </html>
  ``` 
`<a href="https://media-cdn.tripadvisor.com/media/photo-s/1d/f5/78/04/serenade-restaurant-bar.jpg "></a>`

**the src attributes:-**
the < img > tag is used to embed an image in an html page.the src attributes specifies the path to the image to be displayed:-
**example:-**
<img src="https://as2.ftcdn.net/v2/jpg/02/94/26/33/1000_F_294263329_1IgvqNgDbhmQNgDxkhlW433uOFuIDar4.jpg"></img>

html attributes are modifiers used to control the behavior and representation of an html elements.
global attributes are attributes that can be used on all html elements.


### (3) what are void elements in html?

#### ans.
not all html tags are of the same structure while most elements require an opening tag, a closing tag, and contents, some elements known as void elements-only require an opening tag as they themselves do not contain any elements.this topic explains and demonstrate the proper usage of void elements in html.

 **void elements :-**
 html 4.01/xhtml 1.0 strict includes the following void elements:
 * area- clickable,defined area in an image
 * base- specifies a base URL from which all links base.
 * br- link break
 * hr- horizontal ruel (line)
 * img- image
 * input- field where users enter data
 * link- link as external resource to the document
 * meta- provides information about the document
 * param- defines paramenters for plugins


 <u> the example below does not include void elements:- </u>


 notice how every elements has an opening tag,a closing tag,and text or other elements inside the opening and closing tags.void tags however are shown in the example belows:

 ```html
<html>
    <head>
        <title>welcome</title>
    </head>
    <body>
      <img height="500px" width="500pxs"
         src="E:\images\mahindra-thar-2020-left-front-three-quarter34.jpeg">
         <hr>
          <input type="text" name="" id="" placeholder="enter your name"><br>
            <input type="text" name="" id="" placeholder="enter your email"><br>
            <input type="text" name="" id="" placeholder="enter your password"><br>
            <input type="color" name="" id=""><br>

```
 with the exception of the img tag,all of these void elements have only an opening tag.the img tag,unlike any other tag has a self closing/before the greater then sign of the opening tag. it is best practice to have a space before the slash.



 ### (4) what are html entities?
 #### ans.
 an html entity is used to display invisible characters and reserved characters that would otherwise be interpreted as html code. it is a piece of text or string that begins with an ampersand(&)and ends with a semicolon (; ).

 entities are a way of representing special characters or symbols that cannot be directly used in html.they're like secret codes that the browser can understand and display as the intended character.think of entities as a secret language that only browsers can decipher.
 
 entities usually start with an amepellsand (&) and end with a semicolon(; ). there are two types of entities:named entities and numeric entities.named entities use a predefined name,while numeric entities use a numeric code.

 <u>here's an example of a named entities:-</u>
 
 ### &|t;

 this entity represents the lessthan symbol (<).if you were to type this entity into your html code the browser would display a less-than symbol instead of interpreting it as the start of an html tag.

 <u>and here's an example of a numeric entity:</u>

 ### & #60;

 this numeric entity also represents the less-than symbol.the number <u>60</u> corresponds to the unicode value of the less-than symbol.
 
 
 ### (5) What are different types of lists in HTML? 

#### ans.

#### (1) ordered list:-

These are also called numbered lists in HTML. It represents the HTML list items, which are sequentially ordered, either in increasing (1, 2, 3, etc.) or decreasing (3, 2, 1, etc.) order. An ordered list is represented by either numbers, letters (A, B, C, etc.), or roman numerals (I, II, III, etc.).

#### example of ol tag:-
```html
 <html>
    <head>
        <title>ol tag </title>
    </head>
    <body>
        <ol type="a" start="2">
            <li> chudasama </li>
        </ol>
        <ol type="I" start="3">
            <li> chudasama </li>
        </ol>
        <ol type="A" start="16">
            <li> chudasama </li>
        </ol>
    </body>
</html>
```

#### (2) unoreder list :-
An unordered list is a type of HTML element used to create a bulleted listing. Therefore, they are also called bulleted lists in HTML. The elements are typically indicated by bullet points (•) but can be customized with disc (◦), circle (o), and square shapes (■). 

Unordered lists are used to indicate a list of items that don’t have any particular order or hierarchy. 
#### example of ul tag:-
```html
<html>
    <head>
        <title> list tag </title>
    </head>
    <body>
        <ul type="square">
            <li> chudasama (a)</li>
            <li> divyarajsinh (a)</li>
        </ul>
        <ul type="circle">
            <li> rajkot (b)</li>
            <li> gandhinagar (b) </li>
        </ul>
        <ul type="disc">
            <li> chitravad (c) </li>
            <li> bhayavadr (c) </li>
        </ul>
    </body>
    </html>
```
#### (3) description list:-
It is also called a definition list in HTML that contains terms and their associated descriptions. It is denoted by individual elements, such as:

* HTML < dl > element to define a description list.
* HTML < dt > element to define the description term.
* HTML < dd > element to describe the term in a description list.

#### example of description list:-
```html
<html>
    <head>
        <title>document</title>
    </head>
    <body>
        <dl>
            <dt>science</dt>
            <dd> Optogenetically controlled inflammasome activation demonstrates two phases of cell swelling during pyroptosis · TNF-α signals through ITK- ...
            </dd>
        </dl>
        <dl>
            <dt>social science</dt>
            <dd>
                Social science is one of the branches of science, devoted to the study of societies and the relationships among individuals within those societies.
            </dd>
        </dl>
    </body>
</html>
```

### (6)  What is the ‘class’ attribute in HTML?
#### ans.
* Using The class Attribute:-

The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

In the following example we have three < div> elements with a class attribute with the value of "Animal". All of the three < div> elements will be styled equally according to the .Animal style definition in the head section:

##### exapmle:-
```html
<html>
<head>
<style>
.text {
  font-size: 120%;
  color: hsl(129, 92%, 46%);
}
</style>
</head>
<body>

<h1>My <span class="text">name</span>is XXX</h1>
<p>This is some <span class="text">notes</span></p>

</body>
</html>
```

### (7) What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?

#### ans.
##### <u> id attributes:-</u>
In HTML, the "id" selector is used id attribute of an element. For an HTML element, the "id" name starts with the symbol '#' followed by a unique name. One important characteristics of the id element is that we can only attach one id selector to an element. Hence, the ID selector is always unique within an HTML page.
#### example of id attributes:-
```html
<html>
<head>
<title>
  Id demo
</title>
<style>
  #idDemo{
     color:green;
     font-size:25px;
  }
</style>
</head>
<body style="text-align:center">
   <h1>Get element by Id</h1>
   <p id="idDemo">Demo for Id selector</p>
</body>
</html>
```
##### <u>class attributes:-</u>
In HTML, the "class" selector is used to select an element with a specific class attribute. The class selector starts with a period (.) followed by a class name. Unlike the id selector, we can attach multiple selector to an HTML element. Therefore, the class can be applied many time within a page. The important point to note about the class selector is that the class name must not be started with a number.

#### example of class attributes:-
```html
<html>
<head>
<title>
	Class demo
</title>
<style>
   .classDemo{
       color:orange;
       font-size:25px;
   }
</style>
</head>
<body style="text-align:center">
	<h1>Get element by class<h1>
	<p class="classDemo">Demo for class selector</p>
</body>
</html>
```

### (8)  What are the various formatting tags in HTML?

#### ans.
HTML Formatting Elements
Formatting elements were designed to display special types of text:

* < b> - Bold text
* < strong> - Important text
* < i> - Italic text
* < em> - Emphasized text
* < mark> - Marked text
* < small> - Smaller text
* < del> - Deleted text
* < ins> - Inserted text
* < sub> - Subscript text
* < sup> - Superscript text


### (9) How is Cell Padding different from Cell Spacing?

#### ans.
##### (1) Cellpadding:-
The cell padding property sets the distance between the edge of a box-shaped element’s border and its content. It applies to block-level boxes with borders but not those with none. For example, it is used to add padding to table cells, not to the elements. Cell padding is used to adjust the size of the cells in your table. For example, cell padding can create a consistent look across all your tables. The cell padding property is a CSS property that allows you to define the amount of space between each table cell. The cell padding is a feature in the layout of a website that is used to improve the overall look of a page. It can also be implemented to help reduce the size of an image and increase its resolution.

The importance of this approach is that it allows you to use smaller images without compromising on quality or clarity. Some web designers prefer this method to create web pages because it allows them to better utilise the space available on their site. Cell padding is the space left between the cell and its border. It helps control the white space that is present between the border of the cell and the contents within the cell. Cell padding is specified in pixels, but you can also set it in percentages. 

* It only associates with individual (single) cells.
* Using Cellpadding, one can easily control the white space  present between a cell border and the content present in it.
* It is a very effective method.
* It has a default value of 1.
* One can create Cellpadding using the tag of HTML < table >.
* Here, we set the type of attribute to cellpadding.


##### (2) Cellspacing:-
Cell spacing is the space between cells in a table. This can be either vertical or horizontal, depending on your needs. Cell Spacing is the space between two cells in a table. It is Sometimes called cell padding or field padding. Cell spacing to be relative or absolute. Absolute cell spacing means that the text will always be the same on every cell, regardless of its position. Relative cell spacing means that the text will change depending on its position.

The first step in setting the table’s cell spacing is determining the width and height of your table cells. This can be done using CSS or creating a template that includes these dimensions in its HTML markup. Tables created with CSS will automatically calculate their size based on the page’s viewport width and height, but if you’d rather not have your tables take up all the room they’re meant for, use a template instead. A template is just an HTML file you save as an attachment to an email or message board post and then upload to your site—cell Padding Vs. Cell Spacing


* It associates with multiple cells- not just a single one.
* Using Cellspacing, you can set the spaces between various cells.
* It is comparatively less effective than the process of cell padding.
* In this case, the spacing value by default becomes 2.
* One can easily create Cellspacing by using the tag of HTML < table >.
* Here, we set the type of attribute to cellspacing.

 Parameters |	Cellpadding |	Cellspacing
|-----------|-------------|------------|
Purpose	| Cell padding is the term used to describe the area between a table cell’s border and its content.|	The gap between each neighbouring cell is often called “cellspacing.”
Process of Creation	|It may be made using the HTML table> tag but changes the type property to cell padding. |	It may be produced using the HTML table> tag. However, that changes the type property to cell spacing.
Number of Cells	| It concerns just one cell. |	It is exposed to several cells (more than one) at once.
Default Value | 	The default value for cell padding is 1.|	Cellspacing has a default value of 2.
Effectiveness|	When compared to cell spacing, it is quite effective. It is, therefore, very commonly used.|	Comparatively speaking, it is less efficient than cell padding.


### (10) How can we club two or more rows or columns into a single row column in an HTML table?

### ans.
```html
<html>
    <head>
        <title>document</title>
    </head>
    <body>
        <table border="2"
        cellspacing="5"
        cellpendding="5">
        <caption>
           <h1> basic html table </h1>
        </caption>
        <tr>
            <th>leval1</th>
            <th>leval2</th>
            <th>leval3</th>
            <th>info</th>
            <th>name</th>
        </tr>
        <tr>
            <td rowspan="6">system</td>
            <td rowspan="4">system apps</td>
            <td rowspan="3">systemenv</td>
            <td>app test</td>
            <td>foo</td>
        </tr>
        <tr>
            <td>app memory</td>
            <td>foo</td>
        </tr>
        <tr>
            <td>app test</td>
            <td>bar</td>
        </tr>
        <tr>
            <td>systemenv2</td>
            <td>app test</td>
            <td>bar</td>
        </tr>
        <tr>
            <td rowspan="2">system memory</td>
            <td rowspan="2">memory test</td>
            <td>memory func</td>
            <td>foo</td>
        </tr>
        <tr>
            <td>apes test</td>
            <td>foo</td>
        </tr>

        </table>
    </body>
</html>
```

### (11) What is the difference between a block-level element and an inline element?
#### ans.

* #####  Block Elements:-

Block elements begin from a new line by default and cover space to its left and right as far as it can go. The height that it covers is equal to the content height. Also, it covers the whole horizontal space of its parent element.
These are some supported tags of Block elements:

* < article> - Self- contained and independent content.
* < aside> - The content inside aside is often placed at the sidebar in a document.
* < div> - Container for HTML elements.
* < fieldset> - Group the same or related items.
* < figcaption> - Define the caption for < figure> element.
* < figure> - Contain content like illustrations, figures, images etc.
* < footer> - It defines the footer of the section.
* < form> - Get information from the user input.
* < h1>-< h6> - Define HTML headings, where h1 is largest and h6 is smallest.
* < header> - Container of introduction.
* < hr> - Separate content using horizontal lines.
* < li> - Add list items, ordered(< ol>) or unordered lists (< ul>).
* < main> - Add the main content we used the main tag.
* < nav> - Add navigation links.
* < section>- Add a section.
* < table> - Add a table.

* ##### Inline Elements:-
Inline elements never start from a new line and only cover the width according to the size of bounded tags in the HTML element.

* <u> Example:-</u>
```html

<!DOCTYPE html>
<html>
  <body>
    <p>Hello, <span style="border: 1px solid black">Long time no see</span>.</p>

    <p>Inline element example</p>

  </body>
</html>
```

 These are some Inline elements in HTML.

* < a> - It is used to link other web pages. The most important attribute of the anchor tag is the href because it indicates the destination of the link.
* < b> - It makes the text bold.
* < br> - It is used to insert a line break and has no end tag.
* < button> - To create a clickable button.
* < code> - To add computer code.
* < img> - To link image addresses.
* < input> - It is used to get user input text where users can enter data.
* < span> - To highlight a text or part of a document.
* < textarea> - It is used to get input data from users in multiline form.

Block Elements|	Inline Elements|
|-------------|----------------|
Block elements always start from a new line.	|Inline elements never start from a new line.
Block elements cover space from left to right as far as it can go.|	Inline elements only cover the space as bounded by the tags in the HTML element.
Block elements have top and bottom margins.|	Inline elements don't have a top and bottom margin.
Examples of block elements - < p>,< div>,< hr> . |	Examples of inline elements - < span>,<u br>

### (12) How to create a Hyperlink in HTML? 
#### ans.
```html
<html>
    <head>
        <title>HTML Links</title>
    </head>

    <body>
        <p>Click on the following link</p>
        <a href="https://media-cdn.tripadvisor.com/media/photo-s/1d/f5/78/04/serenade-restaurant-bar.jpg "></a
        >
    </body>
</html>
```

### (13) What is the use of an iframe tag? 
#### ans.

An iframe in HTML allows you to embed another HTML document within your current webpage. It’s like having a mini window that displays content from an external source. It supports various attributes for specifying dimensions, borders, scrolling, and more to customize the appearance and behaviour of the embedded content.
##### example:-
```html
<html>
    <head>
        <title>my website</title>
    </head>
    <body>
        <iframe src="https://en.wikipedia.org/wiki/Wikipedia#History"
        hight="1000px"
        width="1000px"
        frameborder="2">
    </iframe>


    <iframe src="E:\divyarajsinh\ifram\img-ex-1.html"
    height="500px"
    width="500px"
    frameborder="2">
    </iframe>
    

    <iframe src="https://www.youtube.com/shorts/hCy2pgzUUsc"
    hight="500px"
    width="500px">
    </iframe>
    </body>
</html>
```
### (14) What is the use of a span tag? Explain with example?
#### ans.

Below are the use cases of Span Tag in HTML.

<u>1. Used for Applying Styles:-</u>
The span tag can be used for applying styles to any specific text in an HTML document. For example, we can change color, increase or decrease font size, etc.

<u>2. Scripting:-</u>
The span tag can be used to group elements together, and then we can apply any functionality using JavaScript or other scripting languages on it.

<u>3. Semantic Markup:-</u>
The span tag can be used in combination with other tags in order to give additional meaning to the content. For example, 
< p>Ninja Name: < span itemprop="name">Ninja1</>.</>
Here, we have used attribute itemprop on the span tag in order to provide an additional meaning. Here it is indicating that it represents the Ninja name.


Below code and output shows the implementation of use cases of span tag in HTML.
#### example:-
```html
<html>
<head>
   <title>Span Tag in HTML</title>
</head>
<body>
    <h1> Hello Ninjas </h1>
    <p> Be more than a coder <span style="color: orangered;font-weight: bold;"> Be a Coding Ninja!!! </span> Let the jobs chase you.</p>

<p>World has enough <span id="my-section">coders</span>.</p>

<script>
  var section = document.getElementById("my-section");
  section.style.backgroundColor = "yellow";
</script>
</body>
</html>
```

### (15) How to insert a picture into a background image of a web page?
#### ans.
Images can make a page look more appealing and captivating. One of such ways for making the page more attractive is adding background image to it. You can add backgrond image in HTML by using two methods: Background attribute (Html Tag) and Internal Style Sheet (CSS).

In this article, we will explore how to add background image in HTML. But, before we begin exploring different methods to add background image in HTML, let’s go through the list of topics listed under the table of contents (TOC) that we will cover in this blog.
##### How to add background image in HTML:

You can add background image in HTML using two methods:

Background attribute (Html Tag)
Internal Style Sheet (CSS)

* Background attribute:
If you want to add background image in HTML using background attrubute, perform the following steps:

(1) Open the HTML file in text editor.
(2) Within the starting < body> tag in your Html file, type < Body background=” “>
(3) Give the path of the image we want to add. ( Example, < Body background=”C:Usersanshuman.singhDownloadsinfoedge.jpg “>
(4) Save the Html file in the text editor and run the file.

##### example:-
```html
<html>
    <head>
        <title> document</title>
    </head>
    <body background="E:\images\mahindra-thar-2020-left-front-three-quarter34.jpeg">
    </body>
</html>
```

### (16)  How are active links different from normal links? 

#### ans.
* <u>normal links:-</u>
In HTML, an unvisited link is a hyperlink that is not yet clicked by the user. By default, the unvisited links will be in blue in color with an underline. However, we can customize the style using the CSS properties (a:link).
##### Example:-
In the following example, we have created a hyperlink without any customization using CSS properties.
```html
<html>
    <head>
        <title>welcome</title> 
    </head>
    <body>
        <a href ="https://www.cookingcarnival.com/wp-content/uploads/2022/04/Veg-hot-dog-4.webp">
    </body>
</html>
```

* <u>Active Links:-</u>

An Active link is a hyperlink that is currently being interacted with the user. Whenever the user holds the mouse button on the link and not released yet or if right clicked on it, it will change its color into red, this is when the link will be in active state.

The active state is temporary and ends once the user releases the mouse button. However, we can customize the style of the active links using the CSS properties (a:active).

Example
In the following example, we are creating a hyperlink and customized it’s style using CSS.
```html
<html>
<head>
   <title>Difference between normal links and active links</title>
   <style>
      a:hover {
         color: red;
         background-color: transparent;
         text-decoration: underline;
      }
      a:active {
         color: yellow;
         background-color: transparent;
         text-decoration: underline;
      }
   </style>
</head>
<body>
   <h3>Click here to visit → <a href="https://www.tutorialspoint.com/">Tutorialspoint</a>
   </h3>
</body>
</html>
```




 ### (17) What are the different tags to separate sections of text?
 
 #### ans.

 defines the section of documents such as chapters, headers, footers, or any other sections. The section tag divides the content into sections and subsections. The section tag is used when requirements of two headers or footers or any other section of documents are needed. Section tag grouped the generic block of related contents. The main advantage of the section tag is, it is a semantic element, which describes its meaning to both browser and developer.

In this article, we will discuss how to separate a section from another section in HTML.

##### example:-
```html
<html>
<body>
	<section>
		<h1>Geeksforgeeek: Section 1</h1>
		<p>Content of section 1</p>
	</section>
	<section>
		<h1>GeeksforGeeks: Section 2</h1>
		<p>Content of section 2</p>
	</section>
	<section>
		<h1>GeeksforGeeks: Section 3</h1>
		<p>Content of section 3</p>
	</section>
</body>
</html>
```


 ### (18) What is SVG?
 #### ans.
(1) HTML SVG is used to describe the two dimensional vector and vector/raster graphics.
(2)HTML SVG is a modularized language which is used to describe graphics in XML.
(3)It describe two-dimensional vector and mixed vector/raster graphics in XML.
(4)It is a W3C recommendation.
(5)SVG images and their behaviors are defined in XML text files. So as XML files, you can create and edit an SVG image with text editor, but generally drawing programs like inkspace are preferred to create it.
(6)SVG is mostly used for vector type diagrams like pie charts, 2-Dimensional graphs in an X,Y coordinate system etc.
(7)The < svg> element specifies the root of a SVG fragment.
(8)You can animate every element and every attribute in SVG files.

### <u> example:-</u>
```html
<html>
  <body>
    <svg width="100" hight="100">
      <circle cx="50" cy="50" r="40" stroke="yellow" stroke-width="4" fill="red">
    </body>
    </html>
```


 ### (19) What is difference between HTML and XHTML?
 #### ans.
 * <u> HTML:- </u>

 Hypertext Mark-up Language (HTML) is a programming language that shows information and depicts a site page's design. Hypertext works with perusing the web by referring to an HTML page's hyperlinks. The hyperlink empowers one to go to any put on the web by clicking it. There is no set request to do as such.

Mark-up language calls attention to how labels characterize the page design and the components inside the page. It comprises different HTML components containing labels and their substance. HTML language empowers the formation of connections of reports, is static, and can overlook little mistakes. In HTML, shutting labels are excessive. It tends to be characterized as a markup language that makes the content unique and intelligent.


HTML is a programming language used to make sites that anybody with web access can see. The labels are the words between the < angle brackets > and separate standard content from HTML code. These are shown on website pages as pictures, tables, outlines, etc.

The labels are not shown on the pages however influence the presence of information on site pages. Various sorts of tags perform various capacities.

### example:-
``` html
<html>  
<head>  
<title> Title </title>  
</head>  
<body>  
  
<h1> Hello World </h1>  
<p> welcome this is your first HTML program </p>  
  
</body>  
</html>  

```
* <u>XHTML:-</u>

XHTML stands for extensible hypertext markup language which is a connection between HTML (hypertext mark-up language) and XML (extensible markup language) also at most of the places XHTML is considered superior than HTML.

XHTML is easy to use with other data formats, and it creates more neat code as it is stricter than HTML. Therefore, it is more compatible with most browsers, and it maintains a standard of code that can be used for various devices.

S.No.|HTML	|XHTML
-----|------|-----
1.|	Hypertext mark-up language - - > HTML|	Extensible Hypertext Mark-up Language - - > XHTML.
2.|	Tim Berners created in 1991|	World wide web consortium or W3C created in 2000
3.|	It is an extension of standard generalized markup language or SGML|	It is a combination of extensible markup language XML and hypertext markup language HTML
4.|	It stored in a document file format	|It stored as a markup language format
5.|	It is not case sensitive as there is no mandatory rule to write the entire mark up in uppercase or lower case. It can also be a combination of both.|	It is case-sensitive, and every tag and attribute used inside must be in lowercase.
6.|	It is not mandatory to add document label < DOCTYPE >at the top of every page. We can even skip it.|	It is mandatory to add a document label < DOCTYPE > at the beginning of the page.
7.|	We can close any tag anytime and anywhere as per our needs|	It is mandatory to close all the tags in strict residing order as they were declared.
8.|	We can add attributes without any quotes. |	It is mandatory to add quotes on every attribute we declare
9.|	,html and .htm are the extensions used by HTML |	.xhtml, .xml and .xht are the file extensions used by XHTML
10.|	Lewd structure is used	|It contains a very strict structure, and the developer cannot go out of the bounds of these structures.



 ### (20) What are logical and physical tags in HTML?
 
 #### ans. 
 * <u>logical tag:-</u>
 Logical tags are used to indicate to the visually impaired that there is some emphasizes on the text. Each browser has its own technique as to how to indicate to its viewer that the text between the tags are different.
The syntax or format for using a LOGICAL TAG is as follows:
``` html

<EM>	Indicates that characters should be emphasized in some way. Usually displayed in italics.	</EM>
<STRONG>	Emphasizes characters more strongly than <EM>. Usually displayed in a bold font	</STRONG>
<CODE>	Indicates a sample of code. Usually displayed in a Courier font or a similiar font that allots the same width to each character.	</CODE>
<KBD>	Used to offset text that the user should enter. Often displayed in a Courier font or a similiar font that allots the same width to each character.	</KBD>
<VAR>	Indicates a variable. Often displayed in italics or underlined.	</VAR>
<CITE>	Indicates short quotes or citations. Often italized by browsers.	</CITE>
```


 * <u>physical tag:-</u>
 Physical tags are used to indicate exactly how specific characters are to be formatted.
The syntax or format for using a PHYSICAL TAG is as follows:
``` html
<B>	Indicates that the text should be bold.	</B>
<I>	Indicates that the text should be italic.	</I>
<TT>	Indicates that the text should be used with a font such as Courier that allots the same width to each character.	</TT>
<BIG>	Indicates that the text should be displayed in a big font. Available in HTML 3.0 or higher.	</BIG>
<SMALL>	Indicates that the text should be displayed in a small font. Available in HTML 3.0 or higher.	</SMALL>
<SUB>	Indicates that the text should be displayed as a subscript, in a smaller font if possible. Available in HTML 3.0 or higher.	</SUB>
<SUP>	Indicates that the text should be displayed as a superscript, in a smaller font if possible. Available in HTML 3.0 or higher.	</SUP>
<U>	Indicates that the text should be displayed underlined. Not all browsers support this tag.	</U>
```

