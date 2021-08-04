## Images 

Images can improve the design and the appearance of a web page

## HTML Images Syntax

The HTML <(img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <(img> tag is empty, it contains attributes only, and does not have a closing tag.

The <(img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image

## The src Attribute

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

## The alt Attribute

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

## Image Size - Width and Height

You can use the style attribute to specify the width and height of an image.

<(img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

## Color Names Supported by All Browsers

All modern browsers support the following 140 color names (click on a color name, or a hex value, to view the color as the background-color along with different text colors):

https://www.w3schools.com/cssref/css_colors.asp

## CSS Text

The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"
an RGB value - like "rgb(255,0,0)"
Look at CSS Color Values for a complete list of possible color values.

The default text color for a page is defined in the body selector.

body {
  color: blue;
}

h1 {
  color: green;
}

## Text Color and Background Colorbody {
  
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}

## JPEG

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos.

## GIF 

Use GIF format for images that contain animations.

## PNG 

images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent 
Partial transparency makes the edges blend smoothly into the background