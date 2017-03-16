Hands-On: Structuring a HTML Page using Block and Inline Elements
Hands-On: Structuring a HTML Page using Block and Inline Elements

Objective: In this guided exercise, you will use a combination of block and inline elements to structure a HTML web application.

Pre-requisite: You need to have Visual Studio Code installed on your local machine (Windows, OSX or Linux) in order to complete this exercise.
Setup

    On your local machine, open Visual Studio Code.
    Go to the File menu and select the Open Folder option.
    Create a new folder for this exercise and select this folder in the dialog.
    Create a new file name index.html. The index.html file should now be open in the editor.

Exercise

    Add the following basic HTML structure to your file:

    <!DOCTYPE html>
    <html lang="en-US">
    <head>
        <title>HTML Page</title>
    </head>
    <body>
    </body>
    </html>

    Within the body elements, add a div element:

    <body>
    <div>
    </div>
    </body>

    Within the div element, add the content DIV is a block-level element:

    <div>
    DIV is a block-level element
    </div>

    Within the body elements, add another set of a div element:

    <body>
    <div>
      DIV is a block-level element
    </div>
    <div>
    </div>
    </body>

    Within the new div element, add the content Notice the text is rendered on new lines:

    <div>
    Notice the text is rendered on new lines
    </div>

    Within the first div element, add two sets of a p element:

    <div>
    DIV is a block-level element
    <p>
    </p>
    <p>
    </p>
    </div>

    Within the first p element, add the content P is also a block-level element:

    <p>
    P is also a block-level element
    </p>

    Within the second p element, add the content Notice the text is rendered on new lines:

    <p>
    Notice the text is rendered on new lines
    </p>

    Within the second div element, add a set of a span element with the content SPAN is an inline element rendered on the same line:

    <div>
    Notice the text is rendered on new lines
    <span>
    SPAN is an inline element rendered on the same line
    </span>
    </div>

    Your body element should look like this:

    <body>
    <div>
        DIV is a block-level element
        <p>
            P is also a block-level element
        </p>
        <p>
            Notice the text is rendered on new lines
        </p>
    </div>
    <div>
        Notice the text is rendered on new lines
        <span>
        SPAN is an inline element rendered on the same line
        </span>
    </div>
    </body>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe that the P and DIV elements render text on separate lines while the SPAN element keeps text on the same line if there is enough width.
    Resize the browser window to observe the SPAN text wrapping if there is not enough available width.

    Close your open browser and Visual Studio Code.

Result: At the end of this guided exercise, you will have laid out a web application using both block and inline elements.


Hands-On: Formatting Text on a HTML Page
Hands-On: Formatting Text on a HTML Page

Objective: In this guided exercise, you will format various blocks of text.

Pre-requisite: You need to have Visual Studio Code installed on your local machine (Windows, OSX or Linux) in order to complete this exercise.
Setup

    On your local machine, open Visual Studio Code.
    Go to the File menu and select the Open Folder option.
    Create a new folder for this exercise and select this folder in the dialog.
    Create a new file name index.html. The index.html file should now be open in the editor.

Exercise

    Add the following basic HTML structure to your file:

    <!DOCTYPE html>
    <html lang="en-US">
    <head>
        <title>HTML Page</title>
    </head>
    <body>
    </body>
    </html>

    Within the body elements, add a p element:

    <body>
    <p>
    </p>
    </body>

    Within the p element, add the content Paragraph Text:

    <p>
    Pargraph Text
    </p>

    Below the previously entered line of text, add a br element:

    <p>
    Pargraph Text
    <br />
    </p>

    Below the br element, add a strong element with the content Bold Text:

    <p>
    Pargraph Text
    <br />
    <strong>Bold Text</strong>
    </p>

    Below the strong element, add another br element:

    <p>
    Pargraph Text
    <br />
    <strong>Bold Text</strong>
    <br />
    </p>

    Below the br element, add a i element with the content Italic Text:

    <p>
    Pargraph Text
    <br />
    <strong>Bold Text</strong>
    <br />
    <i>Italic Text</i>
    </p>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe the various text blocks and their formatting.
    Close your open browser and switch back to Visual Studio Code.

    Below the original p element, add a p element:

    <body>
    <p>
      Pargraph Text
      <br />
      <strong>Bold Text</strong>
      <br />
      <i>Italic Text</i>
    </p>
    <p>
    </p>
    </body>

    Within the p element, add a small element with the content Small Text:

    <p>
    <small>Small Text</small>
    </p>

    Below the small element, add another br element:

    <p>
    <small>Small Text</small>
    <br />
    </p>

    Below the br element, add a mark element with the content Marked Text:

    <p>
    <small>Small Text</small>
    <br />
    <mark>Marked Text</mark>
    </p>

    Below the mark element, add another br element:

    <p>
    <small>Small Text</small>
    <br />
    <mark>Marked Text</mark>
    <br />
    </p>

    Below the br element, add a del element with the content Deleted Text:

    <p>
    <small>Small Text</small>
    <br />
    <mark>Marked Text</mark>
    <br />
    <del>Deleted Text</del>
    </p>

    Below the del element, add another br element:

    <p>
    <small>Small Text</small>
    <br />
    <mark>Marked Text</mark>
    <br />
    <del>Deleted Text</del>
    <br />
    </p>

    Below the br element, add a ins element with the content Inserted Text:

    <p>
    <small>Small Text</small>
    <br />
    <mark>Marked Text</mark>
    <br />
    <del>Deleted Text</del>
    <br />
    <ins>Inserted Text</ins>
    </p>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe the new text blocks and their formatting.
    Close your open browser and switch back to Visual Studio Code.

    Below the newest p element, add a p element:

    <body>
    <p>
      Pargraph Text
      <br />
      <strong>Bold Text</strong>
      <br />
      <i>Italic Text</i>
    </p>
    <p>
      <small>Small Text</small>
      <br />
      <mark>Marked Text</mark>
      <br />
      <del>Deleted Text</del>
      <br />
      <ins>Inserted Text</ins>
    </p>
    <p>
    </p>
    </body>

    Within the p element, add the content Paragraph Text:

    <p>
    Pargraph Text
    </p>

    Add a sup element with the content Superscript Text:

    <p>
    Paragraph Text <sup>Superscript Text</sup>
    </p>

    Add the content Paragraph Text:

    <p>
    Paragraph Text <sup>Superscript Text</sup> Paragraph Text
    </p>

    Add a sub element with the content Subscript Text:

    <p>
    Paragraph Text <sup>Superscript Text</sup> Paragraph Text <sub>Subscript Text</sub>
    </p>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe the new text blocks and their formatting.

    Close your open browser and Visual Studio Code.

Result: At the end of this guided exercise, you have created formatted text elements in your HTML page using various types of dedicated formatting elements.


Hands-On: Creating External Hyperlinks
Hands-On: Creating External Hyperlinks

Objective: In this guided exercise, you will create a hyperlink to an external website.

Pre-requisite: You need to have Visual Studio Code installed on your local machine (Windows, OSX or Linux) in order to complete this exercise.
Setup

    On your local machine, open Visual Studio Code.
    Go to the File menu and select the Open Folder option.
    Create a new folder for this exercise and select this folder in the dialog.
    Create a new file name index.html. The index.html file should now be open in the editor.

Exercise

    Add the following basic HTML structure to your file:

    <!DOCTYPE html>
    <html lang="en-US">
    <head>
        <title>HTML Page</title>
    </head>
    <body>
    </body>
    </html>

    Within the body elements, add a a element.

    <body>
    <a></a>
    </body>

    Set the href attribute of the a element to http://www.microsoft.com:

    <a href="http://www.microsoft.com"></a>

    Set the content of the a element to Link to Microsoft:

    <a href="http://www.microsoft.com">Link to Microsoft</a>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Observe that your page now has a single hyperlink with the text Link to Microsoft.
    Click the hyperlink to navigate to http://www.microsoft.com.
    Close your open browser and switch back to Visual Studio Code.

    Set the target attribute of the a element to *_blank*:

    <a href="http://www.microsoft.com" target="_blank">Link to Microsoft</a>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Click the hyperlink and observe that the hyperlink now opens in a new browser tab or window.
    Close your open browser and switch back to Visual Studio Code.

    Set the content of the a element to http://www.microsoft.com:

    <a href="http://www.microsoft.com" target="_blank">http://www.microsoft.com</a>

    Add the download attribute to the a element:

    <a href="http://www.microsoft.com" target="_blank" download>http://www.microsoft.com</a>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:
        Press F1, search for and select the View in Default Application extension
        Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)
    Click the hyperlink and observe that the hyperlink now prompts you to download the web page.

    Close your open browser and Visual Studio Code.

Result: At the end of this guided exercise, you have created a hyperlink in HTML, specified the target and enabled download of the hyperlink.


Hands-On: Creating Hyperlinks to Anchors
Hands-On: Creating Hyperlinks to Page Anchors

Objective: In this guided exercise, you will create a hyperlink that can navigate to specific anchors on a page.

Pre-requisite: You need to have Visual Studio Code installed on your local machine (Windows, OSX or Linux) in order to complete this exercise.
Setup

    On your local machine, open Visual Studio Code.
    Go to the File menu and select the Open Folder option.
    Create a new folder for this exercise and select this folder in the dialog.
    Create a new file name index.html. The index.html file should now be open in the editor.

Exercise

    Add the following basic HTML structure to your file:

    <!DOCTYPE html>
    <html lang="en-US">
    <head>
        <title>HTML Page</title>
    </head>
    <body>
    </body>
    </html>

    Within the body elements, copy the following h1 elements (placeholder content) and paste them twice within your web page.

    <h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce feugiat scelerisque nisi, sed sollicitudin eros volutpat consectetur. Sed quis interdum erat. Nunc vulputate metus eu enim hendrerit dignissim. Proin blandit, elit vel semper euismod, nunc sem varius mauris, a tempus tellus dolor ut leo. In a metus pulvinar, porttitor odio non, auctor risus. Ut et condimentum elit, a efficitur ex. Nulla pretium tortor sed lacinia lacinia. Sed pulvinar metus vel malesuada rhoncus. Sed at lacinia velit. Quisque vel metus nulla.</h1>
    <h1>Vivamus malesuada gravida ex eu vulputate. Aenean pulvinar purus ut consequat dictum. Nunc tincidunt iaculis felis vel sagittis. Praesent ac enim ut purus rhoncus fringilla non sed eros. Nam vitae sapien dolor. Aenean id sapien vestibulum, rutrum enim sagittis, varius eros. Nulla facilisi. Nulla faucibus est eu nibh eleifend malesuada. Vestibulum dapibus vestibulum urna, non suscipit felis lacinia ut. Mauris pharetra, urna at facilisis dictum, nibh velit condimentum leo, pretium tincidunt metus mi at nunc. Aliquam tincidunt ex id libero viverra ultricies consectetur sit amet augue. Quisque pellentesque mi vitae ante vehicula consequat. Nulla malesuada est id felis ultrices ultricies.</h1>
    <h1>Nunc magna dui, elementum ut elit eget, scelerisque posuere enim. Maecenas ullamcorper dolor quis aliquam scelerisque. Nunc tortor ligula, facilisis mollis lobortis sit amet, venenatis vel sem. Phasellus pharetra lectus et ligula tincidunt rhoncus. Curabitur suscipit lorem a ligula blandit aliquam. Quisque luctus ipsum nisi, auctor placerat ligula euismod et. Cras ac arcu id tortor convallis lacinia quis id urna. Nunc sed aliquam velit, ac laoreet turpis. Aenean lacinia pharetra tellus, vel pellentesque neque porta id. Morbi bibendum ornare sapien, eget laoreet tellus facilisis ac.</h1>
    <h1>Morbi mattis ligula libero, at tincidunt ex venenatis quis. In non urna congue augue cursus lacinia rhoncus condimentum arcu. Donec malesuada viverra augue, vel vestibulum velit commodo ut. Donec odio tellus, eleifend iaculis hendrerit id, cursus id augue. Sed non lacus eros. Aenean laoreet tempor nulla, in tincidunt erat luctus eu. Duis lacinia mollis quam ac varius. Cras eget mi justo. Maecenas maximus dui in nisi cursus, bibendum iaculis diam posuere. Sed mollis, nulla vel tincidunt consectetur, metus velit cursus ex, non dictum diam erat non tellus. Morbi et quam lectus. Nullam sit amet porttitor turpis. Aenean a ornare leo. Proin sed arcu purus. Aliquam sed ex venenatis, tincidunt nisi ut, tincidunt mauris. Duis sollicitudin nibh et lorem gravida, vel cursus nunc vulputate.</h1>
    <h1>Vestibulum auctor enim sed massa congue, at dapibus sapien sodales. Aenean ullamcorper arcu luctus convallis imperdiet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Phasellus feugiat maximus libero ut placerat. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Pellentesque vitae tellus luctus est dictum venenatis sed non eros. Duis faucibus odio in lobortis finibus. In non porta nunc.</h1>

    Your html should now look like this:

    <body>
    <h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce feugiat scelerisque nisi, sed sollicitudin eros volutpat consectetur. Sed quis interdum erat. Nunc vulputate metus eu enim hendrerit dignissim. Proin blandit, elit vel semper euismod, nunc sem varius mauris, a tempus tellus dolor ut leo. In a metus pulvinar, porttitor odio non, auctor risus. Ut et condimentum elit, a efficitur ex. Nulla pretium tortor sed lacinia lacinia. Sed pulvinar metus vel malesuada rhoncus. Sed at lacinia velit. Quisque vel metus nulla.</h1>
    <h1>Vivamus malesuada gravida ex eu vulputate. Aenean pulvinar purus ut consequat dictum. Nunc tincidunt iaculis felis vel sagittis. Praesent ac enim ut purus rhoncus fringilla non sed eros. Nam vitae sapien dolor. Aenean id sapien vestibulum, rutrum enim sagittis, varius eros. Nulla facilisi. Nulla faucibus est eu nibh eleifend malesuada. Vestibulum dapibus vestibulum urna, non suscipit felis lacinia ut. Mauris pharetra, urna at facilisis dictum, nibh velit condimentum leo, pretium tincidunt metus mi at nunc. Aliquam tincidunt ex id libero viverra ultricies consectetur sit amet augue. Quisque pellentesque mi vitae ante vehicula consequat. Nulla malesuada est id felis ultrices ultricies.</h1>
    <h1>Nunc magna dui, elementum ut elit eget, scelerisque posuere enim. Maecenas ullamcorper dolor quis aliquam scelerisque. Nunc tortor ligula, facilisis mollis lobortis sit amet, venenatis vel sem. Phasellus pharetra lectus et ligula tincidunt rhoncus. Curabitur suscipit lorem a ligula blandit aliquam. Quisque luctus ipsum nisi, auctor placerat ligula euismod et. Cras ac arcu id tortor convallis lacinia quis id urna. Nunc sed aliquam velit, ac laoreet turpis. Aenean lacinia pharetra tellus, vel pellentesque neque porta id. Morbi bibendum ornare sapien, eget laoreet tellus facilisis ac.</h1>
    <h1>Morbi mattis ligula libero, at tincidunt ex venenatis quis. In non urna congue augue cursus lacinia rhoncus condimentum arcu. Donec malesuada viverra augue, vel vestibulum velit commodo ut. Donec odio tellus, eleifend iaculis hendrerit id, cursus id augue. Sed non lacus eros. Aenean laoreet tempor nulla, in tincidunt erat luctus eu. Duis lacinia mollis quam ac varius. Cras eget mi justo. Maecenas maximus dui in nisi cursus, bibendum iaculis diam posuere. Sed mollis, nulla vel tincidunt consectetur, metus velit cursus ex, non dictum diam erat non tellus. Morbi et quam lectus. Nullam sit amet porttitor turpis. Aenean a ornare leo. Proin sed arcu purus. Aliquam sed ex venenatis, tincidunt nisi ut, tincidunt mauris. Duis sollicitudin nibh et lorem gravida, vel cursus nunc vulputate.</h1>
    <h1>Vestibulum auctor enim sed massa congue, at dapibus sapien sodales. Aenean ullamcorper arcu luctus convallis imperdiet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Phasellus feugiat maximus libero ut placerat. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Pellentesque vitae tellus luctus est dictum venenatis sed non eros. Duis faucibus odio in lobortis finibus. In non porta nunc.</h1>
    <h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce feugiat scelerisque nisi, sed sollicitudin eros volutpat consectetur. Sed quis interdum erat. Nunc vulputate metus eu enim hendrerit dignissim. Proin blandit, elit vel semper euismod, nunc sem varius mauris, a tempus tellus dolor ut leo. In a metus pulvinar, porttitor odio non, auctor risus. Ut et condimentum elit, a efficitur ex. Nulla pretium tortor sed lacinia lacinia. Sed pulvinar metus vel malesuada rhoncus. Sed at lacinia velit. Quisque vel metus nulla.</h1>
    <h1>Vivamus malesuada gravida ex eu vulputate. Aenean pulvinar purus ut consequat dictum. Nunc tincidunt iaculis felis vel sagittis. Praesent ac enim ut purus rhoncus fringilla non sed eros. Nam vitae sapien dolor. Aenean id sapien vestibulum, rutrum enim sagittis, varius eros. Nulla facilisi. Nulla faucibus est eu nibh eleifend malesuada. Vestibulum dapibus vestibulum urna, non suscipit felis lacinia ut. Mauris pharetra, urna at facilisis dictum, nibh velit condimentum leo, pretium tincidunt metus mi at nunc. Aliquam tincidunt ex id libero viverra ultricies consectetur sit amet augue. Quisque pellentesque mi vitae ante vehicula consequat. Nulla malesuada est id felis ultrices ultricies.</h1>
    <h1>Nunc magna dui, elementum ut elit eget, scelerisque posuere enim. Maecenas ullamcorper dolor quis aliquam scelerisque. Nunc tortor ligula, facilisis mollis lobortis sit amet, venenatis vel sem. Phasellus pharetra lectus et ligula tincidunt rhoncus. Curabitur suscipit lorem a ligula blandit aliquam. Quisque luctus ipsum nisi, auctor placerat ligula euismod et. Cras ac arcu id tortor convallis lacinia quis id urna. Nunc sed aliquam velit, ac laoreet turpis. Aenean lacinia pharetra tellus, vel pellentesque neque porta id. Morbi bibendum ornare sapien, eget laoreet tellus facilisis ac.</h1>
    <h1>Morbi mattis ligula libero, at tincidunt ex venenatis quis. In non urna congue augue cursus lacinia rhoncus condimentum arcu. Donec malesuada viverra augue, vel vestibulum velit commodo ut. Donec odio tellus, eleifend iaculis hendrerit id, cursus id augue. Sed non lacus eros. Aenean laoreet tempor nulla, in tincidunt erat luctus eu. Duis lacinia mollis quam ac varius. Cras eget mi justo. Maecenas maximus dui in nisi cursus, bibendum iaculis diam posuere. Sed mollis, nulla vel tincidunt consectetur, metus velit cursus ex, non dictum diam erat non tellus. Morbi et quam lectus. Nullam sit amet porttitor turpis. Aenean a ornare leo. Proin sed arcu purus. Aliquam sed ex venenatis, tincidunt nisi ut, tincidunt mauris. Duis sollicitudin nibh et lorem gravida, vel cursus nunc vulputate.</h1>
    <h1>Vestibulum auctor enim sed massa congue, at dapibus sapien sodales. Aenean ullamcorper arcu luctus convallis imperdiet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Phasellus feugiat maximus libero ut placerat. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Pellentesque vitae tellus luctus est dictum venenatis sed non eros. Duis faucibus odio in lobortis finibus. In non porta nunc.</h1>
    </body>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:

    Press F1, search for and select the View in Default Application extension
    Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)

    Observe that the text fills your entire browser and you must scroll to see all of the text. > If the text does not fill your entire browser's window, simply add more elments.
    Close your open browser and switch back to Visual Studio Code.

    Before the closing body element, add a h5 element.

    <h5></h5>
    </body>

    Set the id of the h5 element to sampleLink:

    <h5 id="sampleLink"></h5>

    Set the content of the h5 element to Sample Text:

    <h5 id="sampleLink">Sample Text</h5>

    After the opening body element, add a a element.

    <body>
    <a></a>

    Set the href of the a element to sampleLink:

    <a href="#sampleLink">Sample Link</a>

    Activate the View in Default Application extension to view your HTML file in your preferred browser using one of the following methods:

    Press F1, search for and select the View in Default Application extension
    Use the Ctrl+K, Ctrl+B keyboard combination (Cmd+K, Cmd+B on OSX)

    Click the hyperlink at the top of the page and observe that you are navigated to the smaller text at the bottom of the page.
    Close your open browser and Visual Studio Code.

Result: At the end of this guided exercise, you created a hyperlink that can navigate to elements on a page using the element's id value.




