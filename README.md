# refrence-website

1. Naming convention for all filenames, paths and folders

2. Best practices for commit messages

3. What is HTML? 

HTML is the Hypertext Markup Language that is used for the coding language ans to describe the content for websites.

4. Proper syntax for HTML tags

5. Explain or demonstrate commonly used html tags/elements:

headings: h1-h6 - These headings are the open and closed tag along with an element content. For example: <H3> Butterfly Flowers </H3>
p - The paragroah element defines a paragraph of the text. It is a block-level element and it always starts on a new line. Before and after each paragraph,
browsers add margin automatically.
lists: ul, ol, dl - Ul is the unordered list, OL is the ordered list, and DL is the description list.
a - The a tag element is the is the hyperlink which is used to link one page to another.
img - The IMG tag is used to incorperate  in-line graphics usually icons or small graphics in a HTML documents.
q - The q element is used to mark up quotes embedded in other elements like a paragraph.
blockquote - Blockquotes are large stand alone quotes.
cite - The cite element is used for marking a source of the quote.
em - It is the emphasis element.
strong - It is Lots of emphasis, strong importance or urgency.
b - b is the keyword element.
i - Another language, technical term, title
small - It is an element that represents side-comments and small print like copyright and legal text, independent of its styled presentation. 
 
 6. Explain block Elements and also explain the list of block elements and why they are used from below
 
 A Block element is an HTML element that begins a new line on a web page and extends the full width of the horizontal space of its parent element and it creates large blocks of content like paragraphs or page divisions. 
 
 html - An HTML element is a component of an HTML document that tells a web browser how to construct and interpret a part of an HTML document.
head - The head tag is a container for metadata and is placed between the <html> tag and the <body> tag.
body - The body element contains all the contents of an HTML document.
header - The header is the introductory content that is usually at the top of the page and it would include a logo, company name and main navigation. Headers are also within sections and articles to introduce the content for 
headings, subheadings, author, etc..
nav - The nav element is described by a section of a page which is to provide navigation links, either within the current document or other documents.
main - The main element wraps around the main content of the page. This is used only one time per page and it convinces the browser that this is where the main content is.
section - The section element is used to wrap around related pieces of the content and Usually each section has its own heading.
article - The article element represents a self-contained composition in a web page. It is also intended to be independently distributable or reusable.
div - The div tag defines a division or a section in an HTML document. 
aside - Aside represents a portion of a document whose content is only indirectly related to the document's main content.
footer - Footer elements typically end their pages at the bottom. This often includes lists of links, copyright information, extra information of the company, terms and services.
span - The span tag is an inline container that is used to mark up a part of a text, or part of the document.
small - The small element represents side comments and small prints.

7. Explain why accessibility is important and also explain the accessibility properties like:

Accessibility is improtant because people to make sure that the website will also make sense to visually-impaired or blind users.

landmark roles - ARIA has a number set of landmark roles to help those using screen readers to jump directly to specific sections with the websites.
aria labels - The aria-label defines a string value that labels an interactive element.
image alternative texts - The alternative (Alt) Text is used to convey the “why” of the image as it relates to the content of a document or webpage.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)

CSS stands for Cascading Style Sheets that is the language we use to control the appearance of HTML pages. 

We can create a CSS file in a code editor and save it with the extension .css., We name the file using proper naming conventions and place it within the css folder. also, We need to link the CSS file to the HTML so that the browser knows where to look for the CSS file.

9. What is the difference between CSS property and value (write explanation and an example code)

CSS properties are styles that are used on specified selectors. They are written before values in the CSS ruleset and are isolated from property values by a colon.

For instance, .box {
float: right;
}

10. Why do we use border-box property in CSS?

We use border-box in CSS because, it tells the browser to account for any border and padding in the values you specify for an element's width and height.

11. Explain different type of ways we can add spacing to an element

Some diffrent ways we can add spacing in CSS is by, using either the margin or padding properties to add space around elements. Furthurmore, the text-indent property adds space to the front of the text, such as for indenting paragraphs.

12. What is the main difference between margin and padding?

The diffrence between margin and padding are; a margin is a space around an element's border and padding is the space between an element's border and the element's content.

13. What are different types of display properties?

A few other diffrent types of display properties are; 

display: none;
display: flex;
display: inline-block;
display: block;
dislpay: grid;

14. Write a brief explanation of flexbox property

In CSS, the flex shorthand property can set how a flex item will grow or diminish to fit the space available in its flex container. It is also used to build a one dimensional layout in CSS. One dimensional means that flexbox can build a one dimensional layout either the column or row at once. Also for two dimensional layouts, CSS grids can handle both the row and column. As well, display flex or inline-flex is also used to build a flexbox.

15. What are different types of flexbox properties and what is the major difference between them?

The diffrent types of flex properties are; order, flex-grow, flex-shrink, flex-basis, align-self and flex. 
The major diffrence between them are; the order property can change the order of flex items, The flex-grow property identifies how much a flex item will grow, The flex-shrink property shows how much a flex item will shrink, the flex-basis property shows the initial length of a flex item, the flex property is a shorthand property for the flex-grow, flex-shrink, and flex-basis, the align-self property identifies the alignment for the selected item inside the flexible container and it overrides the default alignment that is set by the align-items property.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property

In order to create a flex container, we start by selecting the parent element in CSS and set it to display: flex;
For the sub properties, you need to also incude flex-direction, flex-wrap, flex-flow, justify-content, align-content and align-items.

17. Write a code example on how you will use a flexbox property on a parent element with sub properties. 

.flex-container {
display: flex;
flex-direction: column-reverse;

}

18. What is CSS grid property?

CSS grid property is when it lets you easily implement a complex layout design by using the row and column.

19. Write the parent and two sub-properties used for CSS Grid Property.

.parent {                   
display: grid;

}

.grid-container div {
 border: 5px solid #e5c3d1;
  padding: 70px;

}

.grid-container {

background-color: #f2f2f2;
max-width: 600px;

}

20. What is the difference between display: flex and display: grid?

The diffrence between these two are, flexbox was made for a layout in one a dimension either a row or a column. Grid was designed for two-dimensional layout for rows, and columns at the same time.

21. What sub-property we use to divide elements in CSS Grid properties?

The sub-property you can use to divide elements in CSS grid properties is the grid-template-columns element.

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)

.grid{

display: grid;

grid-template-columns: repeat (4, 25%)

grid-column-gap: 10px; 


}

23. What is the area property in CSS grid we use for the child elements?

p {
    font-weight: bold;
}

li:nth-child(-n + 2) {
    border: 2px solid blue;
    margin-bottom: 3px;
}

li:nth-child(even) {
    background-color: purple;
}

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

The sub-property display-grid you can use to prevent displaying empty colums is the column-gap element.

For example,

column-gap: 0;
column-gap: 10%;
column-gap: 1em;
column-gap: 20px;

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.

The steps to add google fonts to the CSS file and linking to HTML file are; 

1. Open the Google Fonts
2. Look for the font then click "Select this Style"
3.  On the right side there is a container with the name "Selected family".
4. Click the "Embed" tab and choose <link> or @import depending on where you need to add the font (in HTML or CSS).

  