# Markdown syntax

Markdown is a better way to write HTML, withou all the complexities and ugliness that usually accompanies it

## Headings 
from h1 through h6 are constructed with a # for each level. 

html :
```html
<hi>Heading</h1>
<h2>Heading</h2>
```

## Comments

```
<!--
This is comment
-->
```

## Horizontal Rules

___ : three consecutive underscores
--- : three consecutive dashes
*** : three consecutive asterisks

html:
```html
<hr>
```

## Bold
**Bold Font**

html:
```html
<strong>Bold Font</strong>
```

## Italics
_Italics Font_

html:
```html
<em>Italics font</em>
```

## Strikethrough
~~Strike Through Font~~

html:
```html
<del>Strike through font</del>
```

## Blockquotes
add > before any text you want to quote

> **Bold Font** other words.

html:
```html
<blockquote>Block quotes</blocquote>
```

### Nested

> my test 
>> my nested test

## Lists

### Unordered
a list of items in which the order of the items does not explicitly matter.

* valid bullet
+ valid bullet
    - valid bullet

html:
```html
<ul>
    <li></li>
</ul>
```

### Ordered 

1. itemA
2. itemB
2. itemC

html:
```html
<ol>
    <li></li>
</ol>
```

## Inline code
Wrap inline snippets of code with `

html:
```html
<code>abs</code>
```

## Indented code
Or indent several lines of code by at least four spaces

html:
```html
<pre>
    <code></code>
</pre>
```

## Block code "fences"
Use "fences" ``` to block in multiple lines of code. 

``` markup
This is a sample 
```

## Syntax highlighting
To activate it, simply add the file extension of the language you want to use directly after the first code "fence", 
```js
 var a = 1 // this is javascript
```

> For syntax highlighting to work, the higlight plugin needs to be installed and enabled. it in turn utilizes a jquery plugin, so jquery needs to be loaded in your theme too. 

## Table 
Tables are created by adding pipes as dividers between each cell, and by adding a line of dashes (also separated by bars) beneath the header. Note that the pipes do not need to be vetically aligned. 

| Option | Description |
| ------ | ----------- |
| data   | this is my test text |
| data data | this is 
my test text 3 |

## Right aligned text
Adding a colon on the right side of the dashed below any heading will right align text for that column.

| Option | Description |
| -----: | ----------: |
| data   | this is my test text |
| data data | this is 
my test text 3 |

## Links 

### Basic Link 

[I am a link](http://mylink.com)

html:
```html
<a herf="http://mylink.com">I am a link</a>
```

add a title

[Have a link](httP//mylink.com "Visit link")

html:
<a herf="" title=""></a>

named anchors

eg:

# Table of contents
 * [chapter 1](#chapter-1)
 * [chapter 2](#chapter-2)


Image

image have a similar syntax to links but include a preceding exclamation point.

![Myimage](http://image.jpg "My image")

