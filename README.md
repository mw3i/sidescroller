---
title: Markdown Viewer Idea (Side Scroll View)
---

# Description

The main ways we read english text are:

1. Page horizontally (1-2 pages at a time)
- pdf viewers
- epub readers
2. Scroll vertically (either page-by-page or continuously)
- pdf viewers
- webpages

Another option is to instead structure text as vertical columns, and scroll horizontally

- rather than being page-by-page, we could do a continuous, column-by-column scroll

This html script let's you view markdown files as a continuous stream of vertical columns

- [zero-md](https://zerodevx.github.io/zero-md/) is used to convert the markdown file you're viewing to html

## Why

Why not try it out as a potentially more efficient way to read text; maybe it's the right balance of descrete (columns) and continuous (horizontal scroll) viewing

# Usage

1. Open the html file in your webbrowser
2. click "Upload"; use the file picker to select the md file you want to view
3. scroll horizontally to read

# RoadMap

- Make the text edit-able
    - maybe there's a way to do this with the `textarea` element
    - there's also stuff like [simpleMDE](https://github.com/sparksuite/simplemde-markdown-editor)
- add side panel with:
    - table of contents (navigatable)
    - display settings (change textsize, column width, column spacing, etc)
- probably keep it as a single, pur HTML/CSS/JS file (and avoid anything server-side; if it comes down to it may have to just make it an electron app or something)
- get to the app-quality level of typora

# Design Inspirations

- paperWM & [cardboard](https://www.ctrl.blog/entry/cardboardwm.html) does side scroll windowing in linux <-- primary source of this idea
- Typora
