---
author: Heinz Wittenbrink
title: HTML for content authors
institute: M.A. program in content strategy
date: 2017-11-07
---




# Standardization

## W3C

[W3C HTML](https://www.w3.org/html/ "W3C HTML")

## WhatWG

- [HTML Standard](https://html.spec.whatwg.org/multipage/ "HTML Standard")
- Repository on GitHub: [whatwg/html: HTML Standard](https://github.com/whatwg/html "whatwg/html: HTML Standard")

## History of the standard; Beginnings

- 1992: Tim Berners-Lee: [Tags used in HTML](https://www.w3.org/History/19921103-hypertext/hypertext/WWW/MarkUp/Tags.html "Tags used in HTML")
- 1993: [Hypertext Markup Language (HTML) Internet Draft](https://www.w3.org/MarkUp/draft-ietf-iiir-html-01.txt "https://www.w3.org/MarkUp/draft-ietf-iiir-html-01.txt")
- 1995: [RFC 1866 - The 'text/html' Media Type](https://tools.ietf.org/html/rfc1866 "RFC 1866 - The 'text/html' Media Type")

Source: @2017c

## History of the standard: W3C Recommendations

- January 1997: [HTML 3.2 Reference Specification](https://www.w3.org/TR/REC-html32 "HTML 3.2 Reference Specification")
- December 1997: [HTML 4.0 Specification](https://www.w3.org/TR/REC-html40-971218/ "HTML 4.0 Specification"): strict - frameset - transitional
- 2000/2002: [XHTML 1.0](https://www.w3.org/TR/xhtml1/ "XHTML 1.0: The Extensible HyperText Markup Language (Second Edition)")

Source: @2017c

## History of the standard: WhatWG, W3C

- 2004: Gründung der [Web Hypertext Application Technology Working Group](https://whatwg.org/ "Web Hypertext Application Technology Working Group")(WhatWG)
- since 2006: Cooperation of WhatWG and W3C
- July 2012: Degree of separation (WhatWG: HTML as living standard, W3C: Snapshots)
- 2014: W3C-Specification [HTML5](https://www.w3.org/TR/2014/REC-html5-20141028/ "HTML5")

Sources: @2017c, @2017b

# Design principles

## Content first

- Separation of content and presentation
- Descriptive markup of content
- Additional markup for machines

## Progressive enhancement

- Accessibility and future friendliness
- Universal usability of the content
- Device independence

# Basic elements for authoring text

## Block- and Inline-Elements

- [Inline elements - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements "Inline elements - HTML | MDN")
- [Block-level elements - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements "Block-level elements - HTML | MDN")
- Important: The value of the `display`-property can be changed via CSS (see [display - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/display "display - CSS | MDN"))

## Headings

- Six levels from `h1` to `h6`
- Important for SEO
- Since HTML5: Outlines allow more than one `h1`-heading

## Paragraphs

```html
<p> ... </p>
```
- Fundamental for structuring text
- Should not be used for presentatiion purposes

## Lists

```html
<p>I have lived in the following countries:</p>
<ul>
 <li>Norway
 <li>Switzerland
 <li>United Kingdom
 <li>United States
 </ul>
 
<ol>
<p>I have lived in the following countries:</p>
 <li>Switzerland
 <li>United Kingdom
 <li>United States
 <li>Norway
 </ol>
 
 <dl>
 <dt> Authors
 <dd> John
 <dd> Luke
 <dt> Editor
 <dd> Frank
</dl>
```
- Three types: `ul`, `ol`, `dl`
- List items can include other blog level elements

Examples: @zotero-2358590-5495

## Tables

```html
<table>
 <caption>Characteristics with positive and negative sides</caption>
 <thead>
  <tr>
   <th> Characteristic
   <th> Negative
   <th> Positive
 <tbody>
  <tr>
   <th> Mood
   <td> Sad
   <td> Happy
  <tr>
   <th> Grade
   <td> Failing
   <td> Passing
</table>
```
Example: @zotero-2358590-5495

## Links

# Media integration

## iframes

# New Structural Elements in HTML5

# Multimedia

# HTML and XML

# Validating

# Editing with Atom

# Documentation

## Mozilla

[Element - HTML | MDN](https://developer.mozilla.org/de/docs/Web/HTML/Element "Element - HTML | MDN")

## Packages

## language-html

> Many Core and Community packages come bundled with their own snippets that are specific to it. For example, the language-html package that provides support for HTML syntax highlighting and grammar comes with dozens of snippets to create many of the various HTML tags you might want to use. If you create a new HTML file in Atom, you can type html and then press Tab and it will expand to:

```html
<html>
  <head>
    <title></title>
  </head>
  <body>

  </body>
</html>
```

> To see all the available snippets for the file type that you currently have open, choose "Snippets: Available" in the Command Palette.

> In that welcome screen, we are introduced to probably the most important command in Atom, the Command Palette. If you press Cmd+Shift+P while focused in an editor pane, the command palette will pop up.

## emmet

## htmlhint

## linter-spell-html
