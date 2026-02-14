# Chapter 01: Getting started with CSS

- ## External Stylesheet

    **HTML5**

    ```html
    <!DOCTYPE html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8" />
            <meta name="viewport" content="width=device-width initial-scale=1.0">
            <link rel="stylesheet" type="text/css" href="./01hello_world.css">
            <title>Hello World</title>
        </head>
        <body>
            <h1>Hello world!</h1>
            <p>I like CSS</p>
        </body>
    </html>
    ```

    **CSS**

    ```css
    h1 {
        color: green;
        text-decoration: underline;
    }
    p {
        font-size: 25px;
        font-family: 'Trebuchet MS', sans-serif;
    }
    ```

    *[Click here to see the output](./01hello_world.html)*

---

- ## Internal Styles

    **HTML5**

    ```html
    <!DOCTYPE html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width initial-scale=1.0">
            <style>
                h1 {
                    color: green;
                    text-decoration: underline;
                }
                p {
                    font-size: 25px;
                    font-family: 'Trebuchet MS', sans-serif;
                }
            </style>
            <title>Internal Style</title>
        </head>
        <body>
            <h1>Hello world!</h1>
            <p>I ♥ CSS</p>
        </body>
    </html>
    ```

    *[Click here to see the output](./02internal_styles.html)*

---

- ## CSS @import rule

    **HTML5**

    ```html
    <!DOCTYPE html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width initial-scale=1.0">
            <style>
                @import url('./01hello_world.css');
            </style>
            
            <title>Import Rule</title>
        </head>
        <body>
            <h1>Hello world!</h1>
            <p>I ♥ CSS</p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur reprehenderit velit labore autem assumenda corporis itaque ipsam officia ipsa, numquam exercitationem esse modi impedit incidunt accusantium soluta quibusdam. Animi, quibusdam.
            </p>
        </body>
    </html>
    ```

    *[Click here to see the output](./03import_rule.html)*

---

- ## Inline Styles

    **HTML5**

    ```html
    <!DOCTYPE html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width initial-scale=1.0">
            <title>Internal Style</title>
        </head>
        <body>
            <h1 style="color: green; text-decoration: underline;">
                Hello world!
            </h1>
            <p style="font-size: 25px; font-family: 'Trebuchet MS';">
                I ♥ CSS
            </p>
        </body>
    </html>
    ```

    *[Click here to see the output](./04inline_styles.html)*

---

- ## Styling Lists with CSS

    **HTML5**

    ```html
    <!DOCTYPE html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width initial-scale=1.0">
            <link rel="stylesheet" type="text/css" href="./list_style.css">
            <title>Import Rule</title>
        </head>
        <body>
            <ul>
                <li>one</li>
                <li>two</li>
                <li>three</li>
                <li>four</li>
                <li>five</li>
            </ul>
        </body>
    </html>
    ```

    **CSS**

    ```css
    li {
        list-style-type: square;
        list-style-position: inside;
    }
    ```

    *[Click here to see the output](./list_style.html)*

- ## Property Lists

    **CSS**

    ```css
    span {
        text-shadow: yellow 0 0 3px, green 4px 4px 10px;
    }
    ```

    *[Click here to see the output](./01property-list.html)*

- ## Selectors and Comments in CSS

    **CSS**

    ```css
    /* First comment*/

    .first, .blue, #two, div {  /* Multiple Selectors */
        color: palevioletred;
    }
    h2 {
        color:deeppink;
    }
    ```

    *[Click here to see the output](./02selectors.html)*
