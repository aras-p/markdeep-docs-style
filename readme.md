# Documentation CSS style for Markdeep

[Markdeep](https://casual-effects.com/markdeep/) is a sweet Markdown processor script
that allows you writing extended Markdown files, and have them vieweble formatted
directly in the browser. No Markdown processors to run or any of that stuff!

The default Markdeep styling makes the result look more like a book than a "documentation page",
so I cooked up an alternative CSS stylesheet to make it look different.

![This Markdeep style](/images/markdeep-docs.png?raw=true "This Markdeep style")
![Default Markdeep style](/images/markdeep-default.png?raw=true "Default Markdeep style")

Here's a little example page: [formatted](https://rawgit.com/aras-p/markdeep-docs-style/master/example.md.html)
and [raw source](https://raw.githubusercontent.com/aras-p/markdeep-docs-style/master/example.md.html).

To use it in your Markdeep document, just put a `<link rel="stylesheet" href="markdeep-docs.css">`
somewhere on the page, and have `markdeep-docs.css` in the same folder.
