# HTML
**lists**
* Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
* Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
* Definition lists are made up of a set of terms along with the
definitions for each of those terms.
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)
The definition list is created with
the <dl> element and usually
consists of a series of terms and
their definitions.
Inside the <dl> element you will
usually see pairs of <dt> and
<dd> elements.
<dt>
This is used to contain the term
being defined (the definition
term).
<dd>
This is used to contain the
definition.
Sometimes you might see a list
where there are two terms used
for the same definition or two
different definitions for the same
term

You can put a second list inside
an <li> element to create a sublist or nested list.
Browsers display nested lists
indented further than the parent
list. In nested unordered lists,
the browser will usually change
the style of the bullet point too.
![imges](https://static.javatpoint.com/htmlpages/images/html-lists.png)

### Boxes
By default a box is sized just big enough to hold its contents. To
set your own dimensions for a box you can use the height and width properties.
The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have 
been the most popular method because they allow designers to accurately control their size. When you use percentages, the size of the 
box is relative to the size of the browser window or, if the box is encased within
another box, it is a percentage of the size of the containing box.
When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.
In the example on the right, you  can see that a containing <div>
element is used which is 300
pixels wide by 300 pixels high.
Inside of this is a paragraph
that is 75% of the width and
height of the containing element.
This means that the size of the
paragraph is 225 pixels wide by
225 pixels high.

Some page designs expand andshrink to fit the size of the user'sscreen. In such designs, the
min-width property specifiesthe smallest size a box can bedisplayed at when the browser
window is narrow, and themax-width property indicates the maximum width a box can
stretch to when the browser window is wide.
*Border*
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.
*Margin*
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes
*Padding*
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.
The padding property allows
you to specify how much space
should appear between the
content of an element and its
border.
The value of this property is
most often specified in pixels
(although it is also possible to
use percentages or ems). If a
percentage is used, the padding
is a percentage of the browser
window (or of the containing box
if it is inside another box).
Please note: If a width is
specified for a box, padding is
added onto the width of the box.
As you can see, the second
paragraph here is much easier
to read because there is a space
between the text and the border
of the box. The box is also wider
because it has padding.

# javascript
Query is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities