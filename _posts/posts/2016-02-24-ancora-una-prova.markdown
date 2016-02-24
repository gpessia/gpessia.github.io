---
title:  "Ancora una prova"
date:   2016-02-19 10:18:00
description: 
type: post
layout: default
---
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores atque incidunt corporis id debitis esse ullam! Ullam minus sequi, harum veniam, ipsum minima provident, accusantium adipisci sapiente eaque iusto! Quisquam!

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores atque incidunt corporis id debitis esse ullam! Ullam minus sequi, harum veniam, ipsum minima provident, accusantium adipisci sapiente eaque iusto! Quisquam!

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores atque incidunt corporis id debitis esse ullam! Ullam minus sequi, harum veniam, ipsum minima provident, accusantium adipisci sapiente eaque iusto! Quisquam!

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```

Headings

# This is an H1.
## This is an H2.
###### This is an H6.
​
This is also an H1.
==================
​
This is also an H2.
------------------
Paragraphs

Paragraphs are separated by empty lines. Within a paragraph it's possible to have a line break,
simply press <return> for a new line.
​
For example,
like this.
Character styles

*Italic characters* 
_Italic characters_
**bold characters**
__bold characters__
~~strikethrough text~~
Unordered list

* Item a
* Item a
* Item a
  * Item aa
  * Item ab
  * Item ac
Ordered list

1. Step a
2. Step a
3. Step a
   1. Step a
   2. Step a
   3. Step a
List in list

1. Step a
2. Step a
3. Step a
   * Item aa
   * Item ab
   * Item ac
Quotes or citations

Introducing my quote:
​
> Neque porro quisquam est qui 
> dolorem ipsum quia dolor sit amet, 
> consectetur, adipisci velit...
Inline code characters

Use the backtick to refer to a `function()`.
 
There is a literal ``backtick (`)`` here.
Code blocks

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
Indent every line of the block by at least 4 spaces.
​
This is a normal paragraph:
​
    This is a code block.
    With multiple lines.
​
Alternatively, you can use 3 backtick quote marks before and after the block, like this:
​
```
This is a code block
```
​
To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 
​
```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
Bitbucket Server uses CodeMirror to apply syntax highlighting to the rendered markdown in comments, READMEs and pull request descriptions. All the common coding languages are supported, including C, C++, Java, Scala, Python and JavaScript. See Configuring syntax highlighting for file extensions.
Within a code block, ampersands (&) and angle brackets (< and >) are automatically converted into HTML entities.
Links to external websites

This is [an example](http://www.example.com/) inline link.
​
[This link](http://example.com/ "Title") has a title attribute.
​
Links are also auto-detected in text: http://example.com/

Images
Inline image syntax looks like this:

![Alt text](/path/to/image.jpg)
![Alt text](/path/to/image.png "Optional title attribute")
![Alt text](/url/to/image.jpg)

Tables

| Day     | Meal    | Price |
| --------|---------|-------|
| Monday  | pasta   | $6    |
| Tuesday | chicken | $8    |