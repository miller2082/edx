HYPERLINKS

To create a hyperlink to a location within the same HTML page you must do two things:

    You must create an id attribute for the target HTML element. The id attribute is universal and can be placed on all HTML elements:

    <img id="coolImage" src="images/interestingImage.jpg" alt="Interesting Image" />

    You can create an anchor tag (<a>) and specify the id as the target of this anchor tag. You must use a number sign immediately in front of the element id:

    <a href="#coolImage">Navigate to Cool Image</a>

Now the hyperlink will jump directly to the image when someone clicks it.
External Links to Internal elements

You can also use the same internal ids# when someone navigates to your web page in their browser.

For example, if your image has an id of coolImage you can give the user a URL such ashttp://www.mywebsites.com/index.html" and they will be navigated to your web page at the top of the home page (default behavior).

If you use this url: http://www.mywebsites.com/index.html#coolImage", they will be navigated to your web page but they will start at the location of your image instead of the top of the home page.

This technique is very useful for web pages with large quanitites of text where you want a user to "jump" to a specific section.

IMAGES

Images

In HTML images are represented using the <img> tag. This tag provides metadata about the image file and preferred sizing to help the browser decide how to render the image.

Let's look at a simple example that shows an image located in the relative images folder name person.png.

<img src="images/person.png" />

The browser will interpret this and render an image like such:
