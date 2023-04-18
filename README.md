# reference-website
1. Naming convention for all filenames, paths and folders
- The naming conventions for all filenames should be lowercase, no spaces and dashes 
  are fine. Folder naming convention should be similar to filenames. For paths, the 
  folders, assets and files should be inside the root folder so they can be easily 
  linked inside any .html files
    `index.html` 

2. Best practices for commit messages
- 
3. What is HTML?
- Hypertext markup language is the coding language used to describe the content of 
  websites.

4. Proper syntax for HTML tags
-  {When writing HTML, the tags used
   to define the purpose of the
   text follow a specific syntax.}

5. Explain or demonstrate commonly used html tags/elements.
- <h1>This is heading 1</h1>
- <h2>This is heading 2</h2>
- <h3>This is heading 3</h3>
- <h4>This is heading 4</h4>
- <h5>This is heading 5</h5>
- <h6>this is heading 6</h6>

- <p> I am a paragraph </p>

- <ul>Unordered list</ul>

- <ol>Ordered list</ol>

- <dl>Description list</dl>

- <img src="gfg.PNG" alt="GeeksforGeeks Image">

- <q>Used to mark up quotes embedded in
  other elements like a paragraph.</q>

- <blockquote>For large stand alone quotes.</blockquote>

- <cite>Marking the source of the quote. </cite>

- <em>Emphasis</em>

- <strong>Lots of emphasis, strong
importance or urgency</strong>

- <b>A keyword</b>

- <i>Another language, technical
term, title</i>

- <small>Example</small>

6. Explain block Elements and also explain the list of block elements and why they are used from below
- Block elements are used within the body of an HTML document and can contain inline elements, or other block-level elements.

- <html> is the code that is used to structure a web page and its content.</html>
- <head>The head of an HTML document is a part whose content is not displayed in the 
   browser on page loading.</head>
- <body>The tag in HTML is used to define the main content present inside an HTML 
   page</body>
- <header>The header is the introductory content
   usually at the top of the page and would
   include a logo or company name and main
   navigation.</header>
- <nav>This element represents a section of a
   page whose purpose is to provide
   navigation links, either within the
   current document or to other documents.</nav>
- <main>The main element wraps around the main
   content of the page. It’s only used once
   per page and it tells the browser that
   this is where the main content is.</main>
- <section>Section is used to wrap around related
   pieces of content. Usually each section
   has its own heading.</section>
- <article>blog post, product
   card, interactive widget</article>
- <div>Block element used to group
   elements together.</div>
- <aside>The aside element represents a portion of
   a document whose content is only
   indirectly related to the document's main
   content.</aside>
- <footer> lists of links, copyright information,
   extra information about the company,
   terms and services.</footer>
- <span>An inline container used to mark
   up a part of a text, or part of a
   document.</span>
- <small>this element represents side comments and small print</small>

7. Explain why accessibility is important and also explain the accessibility 
   properties like.
- including users with disabilities,
  will have an ideal experience and can
  access the information equally.

- <landmark-roles> ARIA has a set of landmark roles
   to help those using screen readers
   to jump directly to specific
   sections within our sites.
- <Aira-labels> is used to provide an accessible name or label for an element that 
   does not have an inherent label or that needs a more descriptive label than its 
   content provides
- <image-alternative-texts> The alt attribute has two purposes,
   To describe the photo if it doesn’t download
   and To describe the photo to someone who cannot
   see the image, maybe someone using a screen
   reader.

8. What is CSS and how can we implement CSS to our html file (write a proper 
   explanation with the code required to attach a CSS file inside html file)
- <what-is-CSS> Cascading Style Sheets is the
   language we use to control the
   appearance of our HTML pages.
   <head>
   <title>introduction to CSS<title>
   <link rel="stylesheet" href="/css/style.css"/>
   </head>

9. What is the difference between CSS property and value (write explanation and an 
   example code.
- Properties are inside curly brackets that take the from of words like color,font 
  weight and background color
  A value is given to the property following a colon

10. Why do we use border-box property in CSS?
- border-box is used to tell the browser to account for any border and padding in 
  the values you set for the elements width and height.

11. Explain different type of ways we can add spacing to an element
- to add an indent on a block element you use the CSS text-indent property. 

12. What is the main difference between margin and padding?
- the diffrents is that padding is the outside content that is
  pushing the edge of the box away from the content.
  Outside the box is the margin that transparent
  layer pushing other boxes away.

13. What are different types of display properties?
- (inline) this allows element on the same line, height
  and width properties have no effect
  (block) this forces the element to be on its own line
  regardless of its width
  (inline block) this element is formatted as an inline
  element that can have height and width values

14. Write a brief explanation of flexbox property
- this is a one dimensional layout pattern that makes it easy to design flexible and 
  effective layouts.

15. What are different types of flexbox properties and what is the major difference 
    between them?
- flex-end,center,space-between,space-around,space-evenly all of these properties do 
  somthing different things with the spacing of your layout

16. Explain with code the use of flexbox property on a parent element and also 
    explain the sub properties you might need for the flexbox property
- in order for flexbox to work the parent element must be givin a display of flex in 
  css code. the children then must be givin properties sush as algin content, 
  justify content. in order to be displayed in the flex form. these are all written 
  in the css code.

17. Write a code example on how you will use a flexbox property on a parent element 
    with sub properties.
- to add a flexbox to a section your code would look like 
  .container {
  display: flex;
}
18. What is CSS grid property?
- two dimensional layout system that lets you lay content out in rows and columns

19. Write the parent and two sub-properties used for CSS Grid Property.
- the parent property for css grid is display and sub properties are grid and inline 
  grid.

20. What is the difference between display: flex and display: grid?
- Flexbox is designed for one-dimensional layouts, and Grid for two-dimensional 
  layouts.

21. What sub-property we use to divide elements in CSS Grid properties?
- to divid elements in CSS grid properties you would use without .s <.div 
  .class.="grind-container">

22. What unit we use to fractionally divide the element width in CSS Grid property 
    and what are others unit we can use alternatively? (Write a code example)
- to fractionally divide the elements width in css grid you would use the fr unit . 
  witch would look like grind-template-columns: 1fr 1fr 1fr; other units you can use 
  are ex, px, %, and em

23. What is the area property in CSS grid we use for the child elements?
- we use grid: row and grid; column for child elements

24. Which sub-property of display grid you can use to prevent displaying empty 
    columns. Write a code example of that property.
- wrapper {
  display: grid; 
}
25. Explain the steps to add google fonts to your CSS file and how will you link it 
    to the html file
- Find a font in google fonts and click it  then, click + Select this style. On the 
  right side, you'll see a container with the name "Selected family".
  Click Embed and choose <link> or import depending on where you need to add the 
  font in HTML or CSS
  Copy and paste the codes you need

  font-face {
  font-family: myFirstFont;
  src: url(sansation_light.woff);
  }
  div {
  font-family: myFirstFont;}
