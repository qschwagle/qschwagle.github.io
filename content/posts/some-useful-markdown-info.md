---
title: "Some Useful Markdown and Related Text formating Information"
date: 2023-01-13T17:08:43-05:00
draft: false
---

## Specifications

Markdown is an incredible useful, extensible format for writing human readable text content to be
rendered to HTML and other formats. Parsed and styled, the output can be used for a variety of
puposes from websites to formal documents to slide shows. 

Here are some notes and links for the format and information on useful extensions.

### CommonMark

[Link](https://commonmark.org/)

Before CommonMark, Markdown did not have a solid specification closely followed by markdown parsers.
They followed the description given by John Grubar and the ouput of his perl parser for the first
markdown implementation, but they didn't follow them closely. Close enough for most markdown to be
parsed by any of them and generate usable products. Not close enough to ensure the products would be
the same.

Then CommonMark came along to fix the issues.

![xkcd standards comic](https://imgs.xkcd.com/comics/standards.png)

If you need to implement a markdown specification or need to use/reference an implementation,
CommonMark is a good starting point.

### Github Flavored Markdown

[Link](https://github.github.com/gfm/)

Github Flavored Markdown is a superset of CommonMark and is used by Github.com and Github
Enterprise. 

Some extensions added with to CommonMark are Tables, Task list items, strikethrough, autolinks, and 
disallowing raw HTML.

### Markdown (Daring Fireball)

[Link](https://daringfireball.net/projects/markdown/)

This is the original description and perl parser for markdown by John Gruber.

## Extensions

Not strictly simply for markdown, the following parsers can be integrated into markdown or markdown
html rendered content to either properly format or generate useful content.

### Mermaid

[Link](https://mermaid.js.org/)

A JS application for rendering diagrams. Embedding it into either the markdown to html generator or
the website directly makes it an incredibly easy text to graphic generator.

### MathJax

[Link](https://www.mathjax.org/)

A latex math formatting application. Easily embed into the website to properly render equations

