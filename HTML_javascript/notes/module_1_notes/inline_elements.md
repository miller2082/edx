The most common inline element is the <span> element. There are many others including:

    strong
    ins
    del
    sup
    sub
    i
    em

Mixing Inline Elements and Block Elements

Inline Elements and Block Elements can be used together as sibling elements within HTML content. Typically you can only place inline elements within a block element since an inline element will be able to fit within the entire width of the HTML page but a block element may not fit within the potential width of an inline element.

Using the display CSS attribute, you can change the rendering of any element between block or inline but it is not a good idea to change the way HTML elements are expected to behave on a page.
Examples
Code

<span style="background-color: red;">This is the first line of text</span>
<span style="background-color: green;">This is the second line of text</span>



