# Documentation CSS style for Markdeep

[Markdeep](https://casual-effects.com/markdeep/) is a sweet Markdown processor script
that allows you writing extended Markdown files, and have them vieweble formatted
directly in the browser. No Markdown processors to run or any of that stuff!

The default Markdeep styling makes the result look more like a book than a "documentation page",
so I cooked up an alternative CSS stylesheet to make it look different.

Here's a little example page: [formatted](https://rawgit.com/aras-p/markdeep-docs-style/master/example.md.html)
and [raw source](https://raw.githubusercontent.com/aras-p/markdeep-docs-style/master/example.md.html).

![Comparison](/images/comparison.png?raw=true "Comparison")

To use it in your Markdeep document, just put a `<link rel="stylesheet" href="markdeep-docs.css">`
somewhere on the page, and have `markdeep-docs.css` in the same folder.

License is either public domain or BSD 2-clause, whichever is more convenient for you.
