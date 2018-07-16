# Intro
1. Basic HTML Syntax
    1. tag
        1. paragraph element
            1. <p> content </p>
        2. heading
            1. <h1> content </h1>
        3. emphasize
            1. <em> content </em>
    2. attributes
        1. info attribute
            1. ex: <p lang="en"> —— language is english
        2. functional attribute
    3. nesting
        1. children tag must close before parent tag closes

2. Basic Page Structure
    1. HTML Document
        1. DOCTYPE
            1. <!doctype html>
        2. head
            1. <html lang="en">
                 <head>
                  <meta charset="utf-8">
                  <meta name="description" content="A Page for exploring HTML documents">
                  <title>Basic HTML documents</title>
                </head>
                <body>
                </body>
               </html>
        3. body
            1. sibling to head
            2. <body>
                    <h1>Page content</h1>
                    <p>Some<b>random</b> text.</p>
               </body>
        4. Content Models
            1. old version
                1. block level element
                    1. take up own line
                2. inline level element
                    1. in line
            2. new version
                1. flow
                2. metadata
                3. embedded
                4. interactive
                5. heading
                6. phrasing
                7. sectioning

3. Formatting Page Content
    1. Formatting content with HTML
        1. <pre>content</pre> —— preformat
        2. <b>content</b> —— bold
        3. <strong>content</strong> —— strong emphasize
    2. Headings
        1. h1 to h6
    3. Paragraphs
    4. Line Breaks
        1. <br>
    5. Emphasize Texts
        1. <b>content</b>
        2. <strong>content</strong>
        3. <i>content</i>
        4. <em>content</em>
    6. Displaying Special Characters
        1. named character identity
            1. &xxxx;
    7. Controlling white space
        1. &nbsp; —— non breaking white space
    8. Displaying images
        1. <img src="path_to_the_image" width="x" height="x" alt="description_of_the_image">
            1. width, height, and alt are optional
        2. other attributes to use
            1. align="right"
                1. text wrapped around on the right


