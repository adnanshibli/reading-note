# HTML
### Images
There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.
There are several things to consider when selecting and
preparing images for your site, but taking time to get them
right will make it look more attractive and professional


**Choosing Images for Your Site**
A picture can say a thousand words, and great images help make the difference
 between an average-looking site and a really engaging one.
 **Storing Images on Your Site**
 If you are building a site from scratch, it is good practice to create a folder 
 for all of the images the site uses.

 To add an image into the page
you need to use an Img
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
alt
This provides a text description
of the image which describes the
image if you cannot see it.
title
You can also use the title
attribute with the  element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image
HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.
The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

## colors
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
 hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread
## Understanding Color
Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker
This example shows a pH scale to demonstrate
the different ways that colors can be specified
using CSS (using color names, hex codes, RGB,
and HSL)
The rule for the <> element sets a default color for all the text as
well as the default background color for the page. Both use color names.
The rule for the < element sets the color of the heading using a hex
code. There are two values for the background-color property of the
<> element. The first provides a fallback color using a hex code and
the second is an HSLA value for browsers that support this method.
Each paragraph is then shown in a different color to represent the
varying levels of acidity or alkalinity, and these are specified using RGB
values.
### Text
The properties that allow you to control
the appearance of text can be split into
two groups:
● Those that directly affect the font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
● Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)
The formatting of your text can have a significant effect
on how readable your pages are. As we look through these
properties I will also give you some design tips on how to
display your type.