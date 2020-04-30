<!DOCTYPE html>

<html lang="en">

<head>
    <title>web demo landing page</title>
    
    <!-- style is how you add internal css rules to your html -->
    <style>
        html {
            background-color: #ffebcd;
            color: #444;
        }

        body {
            width: 60vw;
            max-width: 800px;
            margin: auto;
            margin-top: 2rem;
            padding: 1rem;
            background: none;
        }

        a {
            color: #444;
        }
    </style>
</head>

<body>
    <!-- headline text -->
    <h1>web demo landing page</h1> 

    <!-- introduction text -->
    <p>I will add starting pages for the web demos. When you open them, you can
        download the files to use as starting point. Or you can View Source and
        copy/paste snippets into your existing code.</p>

        
    <!-- 
    structure of a link:
    <a> is an anchor and tells the browser to go somewhere
    href="filename" tells the browser where to go
    target="_blank" tells the browser to open it in a new blank tab
    <a>the visual element that becomes the link</a>

    notes: 
    * make sure the file is in the same folder as index.html and the filename is written correctly. 

    * no spaces are allowed in file names so use dashes instead: file-name.html
    -->


    <!-- bullet list with items that include a link to a new page -->
    <ul>
        <li><strong><a href="text.html" target="_blank">text.html</a></strong> -
            a demo of the basic text elements you use in html. I am giving you a
            starter file that you can then fill in.</li>
    </ul>


</body>

</html>
