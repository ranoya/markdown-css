# CSS for markdown to HTML transition

Guilherme Ranoya, 2022

## What's this?

CSS definitions to ease the formatting of markdown into HTML.

## Global Variables

--md-bg - background color
--md-fg - text color
--md-code - code color
--md-h1 - headings color (all, h1-h6)
--md-mark - links and other differentiated markdown
--md-highlight - mouse over color
--md-hfont - headings font family
--md-codefont - code font family
--md-font - text font family

Use:

:root {

--md-bg: black;
--md-fg: #eeeeee;
--md-font: Helvetica, Arial, sans-serif;

}

## Use

Just load the CSS file from the web in this address:
https://www.ranoya.com/Assets/JSLibs/markdown/md.css

or, in your HTML:

```html
<style>
:root {
    /* set up variables if you need */
}

</style>
<link rel='stylesheet' typ='text/css' href='https://www.ranoya.com/Assets/JSLibs/markdown/md.css'></link>
```

That's it.
