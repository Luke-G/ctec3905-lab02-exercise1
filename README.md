Basic CSS Exercise

The index.html file contains the module handbook, with the code (generated by the Markdown file) indented and modified ready for you to style up.

Go through the following steps, reloading your file (`ctrl/cmd-R`) in the browser after each change.

1. create a new folder "css" and create a file "styles.css" inside it
1. link to the stylesheet in the HTML `head` section using the syntax `<link rel="stylesheet" href="css/styles.css">`
1. make sure your styles are being read into the HTML file by adding the following at the top of "styles.css": `body{ background: red; }`
1. reload in the browser. If the background is red it has worked, so comment out the above code between CSS comments `/*` and `*/`
1. Set a `font-family` style for the `body` tag that will cascade throughout the entire document. See the [CSS Font Stack](https://www.cssfontstack.com/) for examples
1. Set a `max-width` value for the `body` tag to ensure the [line lengths (see this article)](https://www.usability.gov/get-involved/blog/2006/08/line-length-and-onscreen-reading.html) don't get too wide to be readable
1. set a different font-family style for all the headings (`h1, h2, h3, h4, h5, h6`). The CSS selector for **multiple targets** is comma-separated e.g. `h1, h2 { property: value; }`
1. Style the `ul` element inside the `nav` section. To target an element that is *nested inside* another element, the selector is a space-separated list e.g. `nav ul` or for the li tags themselves `nav li` (you can skip an element)
1. Style the table elements. Adding `width: 100%` will ensure they stretch to match the body width
1. change the default blue/purple link (`a` tag) colours
