IMAGES

Images

In HTML images are represented using the <img> tag. This tag provides metadata about the image file and preferred sizing to help the browser decide how to render the image.

Let's look at a simple example that shows an image located in the relative images folder name person.png.

<img src="images/person.png" />

The browser will interpret this and render an image like such:

You can adjust the size of the image using the height and width attributes.

If you adjust one of the attributes, the image will change size while maintaining its aspect ratio. In this example, the image is 130x129 to start. If I set the width to 350 using the following HTML:

<img src="images/person.png" width="350" />

The image will stretch to a height of 347.30:

If you set both the height and width, the image will change to the exact size ignoring aspect ratio.

<img src="images/person.png" width="350" height="60" />

This will result in an image that looks "warped" like in this example:

Warped Image Example

Alternate text

You can set the alternate text for an image using the alt attribute:

<img src="images/person.png" alt="Person holding computer" />

This text is rendered in scenarios where the image cannot be displayed.

    Accessibility: Some modern browsers, such as those for the visually impaired, do not render images. It is important to specify alt text for these browsers as it will allow these visitors to understand what you intended to show in your image.

