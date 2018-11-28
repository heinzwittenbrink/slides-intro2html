---
title: notes intro2frontend
author: Heinz Wittenbrink
date: 2018-11-23
---

# Plan for today


12:00 - 13:00: Why HTML, Basics

13:00 - 14:00 Break

14:00 - 15:00 Document structure, authoring

15:00 - 16:00 Layout, CSS, Role of JavaScript

16:00 - 16:30 Break

16:30 - 17:15 Metadata, schema.org   

17:15 - 18:15 HTML, Web technology and content strategy

18:15 - 19:00 Next steps, documentation


# Introduction

---

# Examples


[A narcissist’s prayer of Thanksgiving. (My Glamorous Life) | Zeldman on Web & Interaction Design](http://www.zeldman.com/2018/11/18/a-narcissists-prayer-of-thanksgiving-my-glamorous-life/ "A narcissist’s prayer of Thanksgiving. (My Glamorous Life) | Zeldman on Web & Interaction Design")

[Adactio: Links—Great Leap Years - Official site of Stephen Fry](https://adactio.com/links/14547 "Adactio: Links—Great Leap Years - Official site of Stephen Fry")


---


[Accelerated Mobile Pages Project – AMP](https://www.ampproject.org/ "Accelerated Mobile Pages Project – AMP")

[Washington Post – AMP](https://www.ampproject.org/case-studies/washingtonpost/ "Washington Post – AMP")

[AMP Stories Code Example - Paul Shapiro's Search Wilderness](https://searchwilderness.com/amp-stories-code-example/#gref "AMP Stories Code Example - Paul Shapiro's Search Wilderness")

---

[What Beautiful HTML Code Looks Like | CSS-Tricks](https://css-tricks.com/what-beautiful-html-code-looks-like/ "What Beautiful HTML Code Looks Like | CSS-Tricks")

[Exploring an HTML5 Example Document | Coding Dojo](https://www.codingdojo.com/blog/html5-examples/ "Exploring an HTML5 Example Document | Coding Dojo")

[html - HTML5 best practices; section/header/aside/article elements - Stack Overflow](https://stackoverflow.com/questions/4781077/html5-best-practices-section-header-aside-article-elements "html - HTML5 best practices; section/header/aside/article elements - Stack Overflow")

[An Overview of HTML5 Semantics by Michelle on CodePen](https://codepen.io/mi-lee/post/an-overview-of-html5-semantics "An Overview of HTML5 Semantics by Michelle on CodePen")

---

[Adactio: Articles—The Design of HTML5](https://adactio.com/articles/1704 "Adactio: Articles—The Design of HTML5")

[HTML5 For Web Designers by Jeremy Keith](https://html5forwebdesigners.com/ "HTML5 For Web Designers by Jeremy Keith")

[How to Use Semantic HTML5 to Structure Your Page Correctly](https://www.semrush.com/blog/semantic-html5-guide/ "How to Use Semantic HTML5 to Structure Your Page Correctly")

---
# Semantic HTML - why?

Good (semantic) HTML is

- fast
- easy to maintain
- better searchable
- device independent
- accessible



---

1. As content strategists we are in charge of content as a part of applications and services.

---

2 Content has to be described for machines in order to be used by humans.

---

3.HTML is the primary format or digital content.


---

4. As content responsibles we are in charge of steering the authoring, the management and the delivery of HTML formatted content.

---

5. The quality of the digital user experience depends directly or indirectly on the quality of the HTML describing our content.


---

6. The main factor of the technical quality of HTML is its semantic appropriateness.


# Parsing

by using HTML we make a document readable for a computer in order to make it usable for humans

---

The different properties of HTML serve to make it parseable - the output is standardized and contains the information needed for further processing. By JavaScript information can be added to this output. CSS serves to present this (and only this) output. (Every textual content on the web can be formatted as HTML. )

---

> HTML is used to specify whether your web content should be recognized as a paragraph, list, heading, link, image, multimedia player, form, or one of many other available elements or even a new element that you define. [Learning HTML: Guides and tutorials - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML "Learning HTML: Guides and tutorials - Learn web development | MDN")

---

HTML serves to describe content

Elements and tags: With tags you mark content up, elements are part of the DOM

---

Upper case and lower case

Nesting of elements -> parsing HTML

---

block elements and inline elements (block elements cannot be nested in inline elements) > default CSS styling  (CSS boxes: [The box model - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model#Types_of_CSS_boxes "The box model - Learn web development | MDN"))

---



# Attributes:

id and class

Boolean attributes

---

Doctype declaration

`<meta charset="utf-8">`

---

Whitespace (good example for parsing)

character references

comments

---

# head

What are metadata

---

# Developer tools

[What are browser developer tools? - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools "What are browser developer tools? - Learn web development | MDN")

---

Github raw

Code editor

---

meta `author` and `description`

Configure site links in the search console? [Sitelinks - Hilfe für Search Console](https://support.google.com/webmasters/answer/47334?hl=de "Sitelinks - Hilfe für Search Console")

---

open graph `og:twitter`;

language tags `<html lang="en-US">`


# Text

Hierarchy

h1

[HTML Standard](https://html.spec.whatwg.org/multipage/sections.html#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements "HTML Standard")

---

syntax and semantics

Presentational elements

# Hyperlinks

Linking to content and applications


# URLs

`../../` moving up in a diretory, command line

`id`-Attribute

---

HTTP protocol and domain name (ports)

Links best practices: Accessibility

---

`download` attribute to provide a default save filename

URL query notation: [Creating hyperlinks - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#Specifying_details "Creating hyperlinks - Learn web development | MDN")



# Website structure

Accessibility issues

[HTML elements reference - HTML: HyperText Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element "HTML elements reference - HTML: HyperText Markup Language | MDN")

---

Non-semantic wrappers

# Validation

# Images

---

CSS background images for decorative images: [Images in HTML - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML#CSS_background_images "Images in HTML - Learn web development | MDN")

# Video and Audio

>  Including WebM and MP4 sources should be enough to play your video on most platforms and browsers these days.

---

# iframes

---

iframe example disqus

Iframe: embedding nur über HTTPS

---

# Responsive images

`<meta name="viewport" content="width=device-width">`

device pixel and CSS pixel

---
new image formats (such as WebP and JPEG-2000

---

# Additional stuff

---

A list apart  How browsers work

SVG and MathML

Markdown

Progressive Enhancement (and Graceful Degradation)

URLs

---

APIs

Progressive Web Apps

Custom elements

Web Components

Validation

JavaSript Frameworks

AMP

---

# What did we learn?

- Frontend Components
- Writing and validating HTML
- HTML 5
- DOM
- Layouts (Grid)
- Progressive Enhancement

---

Frontend and backend, Client and Server



# Tools

- Text Editor
- Command line
- IDE

---

- W3 Validator
- Github
- MDN

# Basic notions programming

- variables
- conditions
- functions
- interpreter

---
# Discussion

What is the open web and why is it important?

Content strategy and the web

Documentation



# Web vs. other environments:

What is characteristic for the web

- open standards
- Independence from software and hardware
- inclusiveness
