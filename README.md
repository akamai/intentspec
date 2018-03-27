
## Purpose

IntentSpec is a LaTeX package to facilitate writing requirements documents in the "intent specifications" style described in Nancy Leveson's paper, ["Intent Specifications: An Approach to Building Human-Centered Specifications"](http://sunnyday.mit.edu/16.355/levesonintent.pdf).

## Contents

 * intentspec.sty - A LaTeX package you can include in your LaTeX documents.
 * intent_specifications_example.tex - An example document to look at and compile.

## Features

1. macros for citing and linking to another “iitem” with an arrow
2. modification of the enumeration environment to include a specified prefix
3. an “intent item” (iitem) macro to include four parameters:
  (a) a label to be used when citing this item elsewhere in the document
  (b) a short description (which appears in bold)
  (c) a longer description of the item
  (d) a place to cite other related intent items

## Example

For a demonstration, look at intent_specifications_example.tex and compile it with the following commands:

latex intent_specifications_example.tex
latex intent_specifications_example.tex
dvipdf intent_specifications_example.dvi

Then open the resulting PDF in a viewer of your choice.

### Caveat

For cross-referencing to work, you will need to compile the LaTeX multiple times.
