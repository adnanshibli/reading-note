# HTML
**LINKS**
Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.
The text between the opening <a> tag and closing </a> tag is known as link text. Where
possible, your link text should explain where visitors will be taken if they click on it (rather
than just saying "click here").Below you can see the link to
IMDB that was created on the previous page. 

HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!

HTML Links - Syntax
The HTML <a> tag defines a hyperlink. It has the following syntax:

<a href="url">link text</a>
The most important attribute of the  element is the href attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.

By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
Tip: Links can of course be styled with CSS, to get another look!

HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
![imgae](https://www.wikihow.com/images/thumb/3/37/Create-a-Link-With-Simple-HTML-Programming-Step-2-Version-3.jpg/v4-460px-Create-a-Link-With-Simple-HTML-Programming-Step-2-Version-3.jpg.webp)

### layout

HTML Layout Elements
HTML has several semantic elements that define the different parts of a web page:

HTML5 Semantic Elements	
<header> - Defines a header for a document or a section
<nav> - Defines a set of navigation links
<section> - Defines a section in a document
<article> - Defines an independent, self-contained content
<aside> - Defines content aside from the content (like a sidebar)
<footer> - Defines a footer for a document or a section
details> - Defines additional details that the user can open and close on demand
summary> - Defines a heading for the details> element
You can read more about semantic elements in our HTML Semantics chapter.
Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors
CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.
Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens).CSS frameworks aim to make your life easier by providing the code for
common tasks, such as creating layout grids, styling forms, creating
printer-friendly versions of pages and so on. You can include the CSS
framework code in your projects rather than writing the CSS from scratch.

![imsad](https://media.geeksforgeeks.org/wp-content/uploads/layout.png)
