##  How to change image size in CSS?

Sometimes, it is required to fit an image into a certain given dimension. We can resize the image by specifying the width and height of an image. A common solution is to use the max-width: 100%; and height: auto; so that large images do not exceed the width of their container. The max-width and max-height properties of CSS works better, but they are not supported in many browsers.

Another way of resizing the image is by using the object-fit property, which fits the image. This CSS property specifies how a video or an image is resized to fit its content box. It defines how an element fits into the container with an established width and height.

The object-fit property is generally applied to image or video. This property defines how an element responds to the width and height of its container. Mainly there are five values of object-fit property such as fill, contain, cover, none, scale-down, initial, and inherit. The default value of this property is "fill".

##  CSS background-image Property


The background-image property sets one or more background images for an element.

By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.

Tip: The background of an element is the total size of the element, including padding and border (but not the margin).

Tip: Always set a background-color to be used if the image is unavailable.

## CSS Syntax

background-image: url|none|initial|inherit;

## CSS background-repeat Property

The background-repeat property sets if/how a background image will be repeated.

By default, a background-image is repeated both vertically and horizontally.

Tip: The background image is placed according to the background-position property. If no background-position is specified, the image is always placed at the element's top left corner.

## CSS Syntax

background-repeat: repeat|repeat-x|repeat-y|no-repeat|initial|inherit;

## CSS background-position Property

The background-position property sets the starting position of a background image.

Tip: By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.

## CSS Syntax

background-position: value;

## Search Engine
Optimization (SEO)

SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.


## The Basics
Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.
At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.
In order to determine who comes
first in the search results, search
engines do not only look at what
appears on your site. They also
consider how many sites link
to you (and how relevant those
links are). For this reason, SEO
is often split into two areas:
on-page techniques and off-page
techniques.

## On-Page Techniques
On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.
The main component of this is
looking at keywords that people
are likely to enter into a search
engine if they wanted to find
your site, and then including
these in the text and HTML code
for your site in order to help the
search engines know that your
site covers these topics.
Search engines rely very heavily
on the text that is in your pages
so it is important that the terms
people are going to search for
are in text. There are seven
essential places where you want
your keywords to appear.
Ensuring that any images have
appropriate text in the value of
their alt attribute also helps
search engines understand the
content of images.


## Off-Page Techniques
Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of
other sites that link to yours.
They are particularly interested
in sites whose content is related
to yours. For example, if you
were running a website that
sold fish bait, then a link from
a hairdresser is not likely to be
considered as relevant as one
from an angling community.
Search engines also look at the
words between the opening
</a> tag and closing <//a> tag
in the link. If the text in the link
contains keywords (rather than
just click here or your website
address) it may be considered
more relevant.
The words that appear in links to
your site should also appear in
the text of the page that the site
links to.