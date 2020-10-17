# HTML
### Images
HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">

**The src attribute**
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.
Example
<img src="img_chania.jpg" alt="Flowers in Chania">
The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:
If a browser cannot find an image, it will display the value of the alt attribute:

Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.

Example
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
Alternatively, you can use the width and height attributes:Width and Height, or Style?
The width, height, and style attributes are all valid in HTML.

However, we suggest using the style attribute. It prevents styles sheets from changing the size of images:

## Information
To wrap up the book we are going to look
at some practical information that will
help you launch a successful site.
There are entire books written about each of the topics
covered in this chapter but I will introduce you to the key
themes that each subject deals with and give you pointers for
what you need to be considering. You will see:
*  The basics of search engine optimization
* Using analytics to understand how people are using your
site after it has launched
* Putting your site on the web
Search Engine
Optimization (SEO)
1: Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <title> element which lives
inside the <head> element.
2: URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.
3: Headings
If the keywords are in a heading
<hn> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.
4: Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.
As soon as people start coming to your site, you can start analyzing
how they found it, what they were looking at and at what point they are
leaving. One of the best tools for doing this is a free service offered by
Google called Google Analytics.
The content link on the left-hand side allows
you to learn more about what the visitors are
looking at when they come to your site.

