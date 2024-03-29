# reference-website
1. Naming convention for all filenames, paths and folders
- Make sure to follow three rules: all lowercase, no spaces and only letters, numbers, and dashes.

2. Best practices for commit messages?
writting out what has been changed to tell git when you make edits to a document. Make the short and simple but properly explain the changes.

3. What is HTML?
HTML stands for: Hypertext Markup Language
- It is the coding language used to describe the content of a website.

4. Proper syntax for HTML tags
<h1> I am a heading </h1>
- it is important to include an open tag, close tag and the element content. 

5. Explain or demonstrate commonly used html tags/elements:
- headings: h1-h6 (heading) 
<h1>heading</h1>
- P (paragraph)
<p> paragraph <p>
- lists: ul, ol, dl (list)
<ul>
<li> list </li>
</ul>
- A (link)
<a href="" > Link text </a>
- Img (image)
<img src="" alt=""/>
- figure (img & figcaption)
<figure>
<img src="" alt=""/>
</figure>
- Q (quote)
<q> quote </q>
- Blockquote (large standalone quote)
<blockquote>
<p> quote </p>
</blockquote>
- Cite (citation)
<cite> cite </cite>
- Em (emphasis)
<em> emphasis </em>
- Strong (bold)
<strong> strong </strong>
- B (a keyword)
<b> keyword </b>
- I (another language, technical term, title)
<i> I </i>
- Small (small text)
<small> small </small>

6. Explain block Elements and also explain the list of block elements and why they are used from below:
block elements: they are elements that start a new line in the code and use the full width of the page. They are commonly used to group together information and keep them in a "block" together.
- Html: it is used to structure a web page and its contents. 
- head: it is placed between the html and the body tag and contains metadata.
- body: it is used to define the main section of text in the document, also known as the body. It contains all of the contents shown in the document such as headings, images and paragraphs.
- Header: the header includes introductory content and is located at top of the page.
- Nav: it is the section of the website that provides navigation links.
- Main: the main wraps around main content of the page.
- Section: the section wraps around a related pieces of content.
- Article: the article wraps around self- contained composition in a web page.
- Div: the div is used to group elements together.
- aside: it is used to group together content that is indirectly reltated to the main content of the page.
- Footer: it is located at the bottom of page and includes copyright, links and extra information.
- Span: it is a container used to mark up part of a text.
- small: it is a container used to section elements of the document such as a copyright tag or side comments. 

7. Explain why accessibility is important and also explain the accessibility properties like:
Acessibility is important because it lets everyone including users with disabilities can access information equally and easily. 
- landmark roles: they are sections of the page that have been identified programically. They help users to orient themselves to a page and navigate to various sections with ease.
- aria labels: it is a label defined in the WAI-ARIA specefication. It is used to provide labels for objects to allow those with assisitive technology to access the information more easily.
- image alternative texts: it is a short written description of an image shown on the page, it allows those who cannot view the image to understand what is being shown.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS stands for Cascading style sheet. It is the code that styles web content by helping you to structure and design the web pages.
The way it is implimented into our css file is by targeting the element you want to design and then apply design styles.

9. What is the difference between CSS property and value (write explanation and an example code)
- The property in CSS is the aspect of a selector and the value is the possible setting for a property. 
for example if we could put width: 30px, in this case the property would be the width and the 30px would be the value.

10. Why do we use border-box property in CSS?
We use it to define padding and borders in an box. The box helps us to visually separate our content and make it visually appealing. 

11. Explain different type of ways we can add spacing to an element
One way we can add spacing would be using paddings and margins with an element to space it out from other elements. Another way would be using width and height to create space.

12. What is the main difference between margin and padding?
The padding is placed outside the content and is used to push the edge of the box away from the content. 
The margin is outside of the box and is used to push other boxes away.
They are different because margin pushes other boxes away and padding pushed the box away from the content.

13. What are different types of display properties?
The display properties specify the behaviour of an element.
Some examples are display:none, display:inline, display:block and display:inline-block.

14. Write a brief explanation of flexbox property
Flexbox property is a layout system used to create row or column axis layouts. It is one dimensional and helps to place elements vertically or horizontally. 

15. What are different types of flexbox properties and what is the major difference between them?
Different types of flexbox properties consist of display, flex-flow and justify content. 
Flex-flow specefies things such as the direction of the container and how it wraps. 
Justify-content defines how the space around the item.
Display specefies the beahviour of an element such as the box. 

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
.parent {
    flex-flow: row wrap;
    display: flex;
    justify-content: space-around;
}

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
.parent {
    flex-flow: row wrap;
    display: flex;
    justify-content: space-around;
}

.child (
    flex-flow: row wrap;
    display: flex;
    justify-content: space-around;
)
18. What is CSS grid property?
The CSS grid property is a property that sets all of the otger properties in a single declaration. It is designed for a two dimenstional layout instead of flexbox which was designed for a one dimensional layout.

19. Write the parent and two sub-properties used for CSS Grid Property.
.grid-container {
    display:grid;
    grid:100px;
}

20. What is the difference between display: flex and display: grid?
display: flex defines a flex container depending on the given value.
display: grid defines a new gird format for the contents inside the grid.

21. What sub-property we use to divide elements in CSS Grid properties?
we use subgrid to divide elements in css grid properties.

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
We use fr to fractionally divide the element width. 
An example of this would be:
.container {
    display grid;

    grid-template columns: 1fr 2fr 2fr 1fr;
}

23. What is the area property in CSS grid we use for the child elements?
Using a child combator which can be placed between two selectors. 

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
grid-auto-rows can be used to prevent displaying empty columns
example:
.container {
    gird-auto-rows: 100px;
}
25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
You have to go to the google font online, select all of the versions you want and copy the link. From there you bring it into your code and paste the link using a src: url



