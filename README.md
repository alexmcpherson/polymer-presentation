polymer-presentation
====================

An engineering lunch on Polymer elements, made with Polymer elements

This repo partially implements a `<presentation gist='13b5jbjbyhb'>` tag that will fetch specially-formed gists and digest it into a presentation of `<slide>` elements.

Make a gist with different files called `slide-1.md|markdown` and `code-1.js` and they will be sucked in and spit out into the presentation.

`.md|.markdown` from a `slide-X.md` file is put inside a `<markdown>` element, and code is put inside a syntax-highlighted `<code-highlight-element>` tag. It knows about `.js` and `.html` for now, easy to add more.

There is an initial-load bug that I didn't need to fix for my presentation. And other bugs. And the style is bad. Sorry.
