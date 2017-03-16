
Homework Assignment: Using Various HTML Elements on a HTML Page
Scenario

As a new developer at Contoso News Conglomerate, you are tasked with building a new, modern and responsive homepage for the news organization. The existing homepage was built with XHTML and is very hard to understand without deep institutional knowledge of each individual HTML element ID or CSS class. You have plenty of time to start fresh so you have decided to "frame out" a new homepage using HTML5 semantic elements, syntactically valid HTML and a cleaner header.
Overview

In this homework assignment, you will create the basic HTML web page that will be used for Contoso News homepage. You will not worry about formatting yet as this will be done in follow-up homework assignments.
Tasks

In this assignment you will:

    Setup your development environment using Visual Studio Code.
    Create a basic HTML document structure that is clean and concise.
    Add semantic elements to the HTML document for each section of your homepage.
    Populate your homepage with a header and lorem ipsum content so that you can begin to visualize the results.

Homework instructions

For each homework assignment, two sets of instructions are available to use:

    High-Level: These instructions are very simple and challenge you to use your knowledge from the module to implement the instructions.
    Detailed: These instructions are "step-by-step" and can guide you if you get stuck with the high-level instructions.

For more information , you can see:
Visual Studio Code: https://aka.ms/edx-dev211.1x-vscode1


High-Level Steps
Homework: Using Various HTML Elements on a HTML Page

    These instructions are intentionally vague. They are designed to validate your ability to complete the homework instructions without additional guidance. If you ever get stuck, you can always switch to the detailed variant of these instructions.

Setup Your Development Environment

    On your local machine, Create a new folder for all of your homework assignments. > This folder will be used for every homework assignment. Each assignment builds on the previous assignments.
    Open the newly created folder using Visual Studio Code.

    Create a new file within the folder name index.html and open the editor for the file.

Create a Basic HTML Document

    Create a DOCTYPE element at the top of your file.
    Below the DOCTYPE declaration, add a HTML element with the value en-US specified for the lang attribute.
    Within the HTML element, add head and body elements.
    Within the head elements, add a title element with Contoso News as the content of the element.

Add Semantic HTML Elements to The Page

    Within the body element, add a main element.
    Within the main element, add a h3 element with the content Latest Articles.
    Within the main element, add three article elements. Within each of the three article elements, add a h4 element and an p element.

Add Placeholder Text Content

    Locate the first article element within the main element. Populate this element's child elements with the following content:
        h4: International Story
        p: Curabitur pharetra luctus augue, non posuere orci tristique vel. Sed posuere nisi nec lacus ullamcorper, ac vulputate nisl consequat. Nullam sollicitudin nulla vel felis faucibus aliquam. Nunc sit amet velit orci. Proin sed orci fringilla, elementum felis condimentum, convallis augue. Aliquam erat volutpat. Mauris tempus nunc sit amet aliquet bibendum. Praesent vestibulum cursus ex, quis laoreet eros consectetur ac. Ut congue libero quis mauris egestas feugiat. Sed pharetra lorem et magna fringilla, a volutpat nibh sollicitudin. Nullam sagittis sollicitudin urna, sed sollicitudin mauris ornare id.
    After the text within the p element of the first article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #
        target: _blank
    Locate the second article element within the main element. Populate this element's child elements with the following content:
        h4: Finance Story
        p: Nullam tempor mi at libero elementum varius. Sed lobortis lacus feugiat est tristique, nec imperdiet turpis scelerisque. Ut sed urna malesuada, scelerisque dui sit amet, tempus mauris. Integer bibendum egestas urna, a bibendum sem gravida quis. Cras accumsan rhoncus vestibulum. Nam eu blandit leo. Integer at consectetur nunc, et tempus urna. Integer sit amet sollicitudin elit. Donec nec posuere erat. Sed vestibulum nisl neque, vitae tincidunt ex molestie quis. Nulla fringilla viverra turpis in volutpat. Cras vel orci quis velit efficitur ullamcorper sed eu ex. Nullam vel ex nec lectus imperdiet luctus vitae vel nibh. Donec eleifend velit eros, eu efficitur justo molestie id. In egestas gravida lectus. Ut ipsum odio, suscipit sit amet molestie non, scelerisque sed mi. Aenean sed augue eu arcu faucibus molestie. Sed eget ante gravida, rhoncus velit eu, tempus quam. Sed fermentum at odio sed commodo. Fusce lobortis cursus purus, quis consequat est faucibus at. Etiam massa felis, sodales at sodales sed, iaculis quis arcu.
    After the text within the p element of the second article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #
        target: _blank
    Locate the third article element within the main element. Populate this element's child elements with the following content:
        h4: Technology Story
        p: Morbi eget justo ut velit dapibus malesuada. Nunc elementum, neque quis convallis tempus, lacus ante tristique est, id porta tortor leo eget orci. Suspendisse hendrerit interdum lacus et condimentum. Mauris at ex dignissim, bibendum libero at, fermentum lectus. Maecenas porttitor purus quis augue interdum, eget malesuada neque placerat. Ut hendrerit risus in nibh elementum, quis vestibulum ipsum vulputate. Nulla facilisi. In consectetur et lacus vel tincidunt. Quisque feugiat ipsum et erat rhoncus efficitur. In in augue at enim tempor sollicitudin.
    After the text within the p element of the third article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #
        target: _blank

Add a Header Element

    Within the body element of your HTML document, add a new header before the main element.
    Within the new header element, add a h1 element with the content Contoso News:
    Within the new header element, add a h2 element with the content On Time, On Topic:

Validate

    Activate the View in Default Application extension in Visual Studio Code to view the resulting web page.
    Does your solution look similar to this?


Detailed Steps
Homework: Using Various HTML Elements on a HTML Page
Setup Your Development Environment

    On your local machine, open Visual Studio Code.
    Go to the File menu and select the Open Folder option.
    Create a new folder for all of your homework assignments. > This folder will be used for every homework assignment. Each assignment builds on the previous assignments.
    Select the newly created folder in the dialog.
    Create a new file name index.html. The index.html file should now be open in the editor.

You should now have an environment configured to create HTML web pages. Your editor should have a working folder with only a single file (index.html). This HTML file should be open in your editor.
Create a Basic HTML Document

    Add the following markup to your file:

    <!DOCTYPE html>

    Below the DOCTYPE declaration, add a HTML element:

    <!DOCTYPE html>
    <html>
    </html>

    Update the opening HTML element by specifying the value en-US for the lang attribute:

    <html lang="en-US">
    </html>

    Within the HTML element, add head and body elements:

    <html lang="en-US">
        <head>
        </head>
        <body>
        </body>
    </html>

    Within the head elements, add a title element with Contoso News as the content of the element:

    <head>
        <title>Contoso News</title>
    </head>

    Save your HTML file.

You now have a basic HTML document that has a very clean and concise structure.
Add Semantic HTML Elements to The Page

    Within the body element, add a main element between the opening and closing tags:

    <body>
        <main>
        </main>
    </body>

    Within the main element, add a h3 element with the content Latest Articles:

    <main>
        <h3>Latest Articles</h3>
    </main>

    Below the h3 element but still within the main element, add three article elements:

    <main>
        <h3>Latest Articles</h3>
        <article>
        </article>
        <article>
        </article>
        <article>
        </article>
    </main>

    Within each of the three article elements, add a h4 element and an p element.

    <article>
        <h4></h4>
        <p></p>
    </article>

    Your HTML should now look like this:

    <html lang="en-US">
        <head>
            <title>Contoso News</title>
        </head>
        <body>
            <main>
                <h3>Latest Articles</h3>
                <article>
                    <h4></h4>
                    <p></p>
                </article>
                <article>
                    <h4></h4>
                    <p></p>
                </article>
                <article>
                    <h4></h4>
                    <p></p>
                </article>
            </main>
        </body>
    </html>

    Save your HTML file.

You now have the basic structure of the articles that will be on your HTML web page.
Add Placeholder Text Content

    Locate the first article element within the main element. Populate this element's child elements with the following content:
        h4: International Story

        p: Curabitur pharetra luctus augue, non posuere orci tristique vel. Sed posuere nisi nec lacus ullamcorper, ac vulputate nisl consequat. Nullam sollicitudin nulla vel felis faucibus aliquam. Nunc sit amet velit orci. Proin sed orci fringilla, elementum felis condimentum, convallis augue. Aliquam erat volutpat. Mauris tempus nunc sit amet aliquet bibendum. Praesent vestibulum cursus ex, quis laoreet eros consectetur ac. Ut congue libero quis mauris egestas feugiat. Sed pharetra lorem et magna fringilla, a volutpat nibh sollicitudin. Nullam sagittis sollicitudin urna, sed sollicitudin mauris ornare id.

        <h4>International Story</h4>
        <p>
        Curabitur pharetra luctus augue, non posuere orci tristique vel. Sed posuere nisi nec lacus ullamcorper, ac vulputate nisl consequat. Nullam sollicitudin nulla vel felis faucibus aliquam. Nunc sit amet velit orci. Proin sed orci fringilla, elementum felis condimentum, convallis augue. Aliquam erat volutpat. Mauris tempus nunc sit amet aliquet bibendum. Praesent vestibulum cursus ex, quis laoreet eros consectetur ac. Ut congue libero quis mauris egestas feugiat. Sed pharetra lorem et magna fringilla, a volutpat nibh sollicitudin. Nullam sagittis sollicitudin urna, sed sollicitudin mauris ornare id.
        </p>

    After the last line of text within the p element of the first article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #

        target: _blank

        <article>
        <h4>International Story</h4>
        <p>
            Curabitur pharetra luctus augue, non posuere orci tristique vel. Sed posuere nisi nec lacus ullamcorper, ac vulputate nisl consequat. Nullam sollicitudin nulla vel felis faucibus aliquam. Nunc sit amet velit orci. Proin sed orci fringilla, elementum felis condimentum, convallis augue. Aliquam erat volutpat. Mauris tempus nunc sit amet aliquet bibendum. Praesent vestibulum cursus ex, quis laoreet eros consectetur ac. Ut congue libero quis mauris egestas feugiat. Sed pharetra lorem et magna fringilla, a volutpat nibh sollicitudin. Nullam sagittis sollicitudin urna, sed sollicitudin mauris ornare id.
            <a href="#" target="_blank">Read More...</a>
        </p>
        </article>

    Locate the second article element within the main element. Populate this element's child elements with the following content:
        h4: Finance Story

        p: Nullam tempor mi at libero elementum varius. Sed lobortis lacus feugiat est tristique, nec imperdiet turpis scelerisque. Ut sed urna malesuada, scelerisque dui sit amet, tempus mauris. Integer bibendum egestas urna, a bibendum sem gravida quis. Cras accumsan rhoncus vestibulum. Nam eu blandit leo. Integer at consectetur nunc, et tempus urna. Integer sit amet sollicitudin elit. Donec nec posuere erat. Sed vestibulum nisl neque, vitae tincidunt ex molestie quis. Nulla fringilla viverra turpis in volutpat. Cras vel orci quis velit efficitur ullamcorper sed eu ex. Nullam vel ex nec lectus imperdiet luctus vitae vel nibh. Donec eleifend velit eros, eu efficitur justo molestie id. In egestas gravida lectus. Ut ipsum odio, suscipit sit amet molestie non, scelerisque sed mi. Aenean sed augue eu arcu faucibus molestie. Sed eget ante gravida, rhoncus velit eu, tempus quam. Sed fermentum at odio sed commodo. Fusce lobortis cursus purus, quis consequat est faucibus at. Etiam massa felis, sodales at sodales sed, iaculis quis arcu.

        <h4>Finance Story</h4>
        <p>
        Nullam tempor mi at libero elementum varius. Sed lobortis lacus feugiat est tristique, nec imperdiet turpis scelerisque. Ut sed urna malesuada, scelerisque dui sit amet, tempus mauris. Integer bibendum egestas urna, a bibendum sem gravida quis. Cras accumsan rhoncus vestibulum. Nam eu blandit leo. Integer at consectetur nunc, et tempus urna. Integer sit amet sollicitudin elit. Donec nec posuere erat. Sed vestibulum nisl neque, vitae tincidunt ex molestie quis. Nulla fringilla viverra turpis in volutpat. Cras vel orci quis velit efficitur ullamcorper sed eu ex.
        Nullam vel ex nec lectus imperdiet luctus vitae vel nibh. Donec eleifend velit eros, eu efficitur justo molestie id. In egestas gravida lectus. Ut ipsum odio, suscipit sit amet molestie non, scelerisque sed mi. Aenean sed augue eu arcu faucibus molestie. Sed eget ante gravida, rhoncus velit eu, tempus quam. Sed fermentum at odio sed commodo. Fusce lobortis cursus purus, quis consequat est faucibus at. Etiam massa felis, sodales at sodales sed, iaculis quis arcu.               
        </p>

    After the last line of text within the p element of the second article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #

        target: _blank

        <article>
        <h4>Finance Story</h4>
        <p>
            Nullam tempor mi at libero elementum varius. Sed lobortis lacus feugiat est tristique, nec imperdiet turpis scelerisque. Ut sed urna malesuada, scelerisque dui sit amet, tempus mauris. Integer bibendum egestas urna, a bibendum sem gravida quis. Cras accumsan rhoncus vestibulum. Nam eu blandit leo. Integer at consectetur nunc, et tempus urna. Integer sit amet sollicitudin elit. Donec nec posuere erat. Sed vestibulum nisl neque, vitae tincidunt ex molestie quis. Nulla fringilla viverra turpis in volutpat. Cras vel orci quis velit efficitur ullamcorper sed eu ex.
            Nullam vel ex nec lectus imperdiet luctus vitae vel nibh. Donec eleifend velit eros, eu efficitur justo molestie id. In egestas gravida lectus. Ut ipsum odio, suscipit sit amet molestie non, scelerisque sed mi. Aenean sed augue eu arcu faucibus molestie. Sed eget ante gravida, rhoncus velit eu, tempus quam. Sed fermentum at odio sed commodo. Fusce lobortis cursus purus, quis consequat est faucibus at. Etiam massa felis, sodales at sodales sed, iaculis quis arcu.
            <a href="#" target="_blank">Read More...</a>
        </p>
        </article>

    Locate the third article element within the main element. Populate this element's child elements with the following content:
        h4: Technology Story

        p: Morbi eget justo ut velit dapibus malesuada. Nunc elementum, neque quis convallis tempus, lacus ante tristique est, id porta tortor leo eget orci. Suspendisse hendrerit interdum lacus et condimentum. Mauris at ex dignissim, bibendum libero at, fermentum lectus. Maecenas porttitor purus quis augue interdum, eget malesuada neque placerat. Ut hendrerit risus in nibh elementum, quis vestibulum ipsum vulputate. Nulla facilisi. In consectetur et lacus vel tincidunt. Quisque feugiat ipsum et erat rhoncus efficitur. In in augue at enim tempor sollicitudin.

        <h4>Technology Story</h4>
        <p>
        Morbi eget justo ut velit dapibus malesuada. Nunc elementum, neque quis convallis tempus, lacus ante tristique est, id porta tortor leo eget orci. Suspendisse hendrerit interdum lacus et condimentum. Mauris at ex dignissim, bibendum libero at, fermentum lectus. Maecenas porttitor purus quis augue interdum, eget malesuada neque placerat. Ut hendrerit risus in nibh elementum, quis vestibulum ipsum vulputate. Nulla facilisi. In consectetur et lacus vel tincidunt. Quisque feugiat ipsum et erat rhoncus efficitur. In in augue at enim tempor sollicitudin.              
        </p>

    After the last line of text within the p element of the third article element, add a hyperlink (a) element with the following attributes:
        content: Read More...
        href: #

        target: _blank

        <article>
        <h4>Technology Story</h4>
        <p>
            Morbi eget justo ut velit dapibus malesuada. Nunc elementum, neque quis convallis tempus, lacus ante tristique est, id porta tortor leo eget orci. Suspendisse hendrerit interdum lacus et condimentum. Mauris at ex dignissim, bibendum libero at, fermentum lectus. Maecenas porttitor purus quis augue interdum, eget malesuada neque placerat. Ut hendrerit risus in nibh elementum, quis vestibulum ipsum vulputate. Nulla facilisi. In consectetur et lacus vel tincidunt. Quisque feugiat ipsum et erat rhoncus efficitur. In in augue at enim tempor sollicitudin.
            <a href="#" target="_blank">Read More...</a>
        </p>
        </article>

    Save your HTML file.

You now have populated your HTML web page with lorem ipsum content. This content is intentionally designed to be hard to read so that reviewers would focus on the appearance and layout of your web page as opposed to the text and copy.
Add a Header Element

    Within the body element of your HTML document, add a new header immediately prior to the main element:

    <body>
        <header>
        </header>
        <main>
        ...
        </main>
    </body>

    Within the new header element, add a h1 element:

    <header>
        <h1></h1>
    </header>

    Update the h1 element by setting it's content to Contoso News:

    <h1>Contoso News</h1>

    Within the new header element, add a h2 element:

    <header>
        <h1>Contoso News</h1>
        <h2></h2>
    </header>

    Update the h2 element by setting it's content to On Time, On Topic:

    <h2>On Time, On Topic</h2>

You now have a header element on your web page using two heading elements for it's text content.
Validate

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe the HTML web page.
    Does your solution look similar to this?
    Close your open browser and Visual Studio Code.

    Remember to save your files. The next homework assignment will resume from this web page.




