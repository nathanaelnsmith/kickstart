# Kickstart 4

## A Component-driven css framework that loves to be extended.

Kickstart is a CSS framework for the Scoped Component pattern. This means
modularized, namespaced CSS and JS with clean HTML and simple CSS classes.

## Simplification

Look elsewhere for frameworks who strive to be the kitchen sink. In Kickstart 4,
we've focused on getting the bare essentials right and being themeable and
extendable by design.

## Features

### Tiny

Kickstart has no JS dependencies and only needs Sass support. The entire
framework is just two files: kickstart.sass and kickstart.js.

### Component driven

The old web used insanely long CSS classes and repetitive naming conventions.
Kickstart uses the scoped component approach by defining main "components" of
the page in which its child elements can be manipulated within that component's
scope.

Instead of putting a click on `.js-document-upload-start` to put a row in
`.document-row` with an `.document-upload-status`, use the built-in mixins and
shorthand functions to style and bind the `"document"` scope with `.start`,
`.document`, and `.status`

[More on Scoped Components](https://gist.github.com/adamjgrant/599530dab67db17c5b2d)
