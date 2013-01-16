# Markdown

<br>

##[OVERVIEW](id:anchor1)

### PHILOSOPHY

* Intended to be as easy-to-read and easy-to-write and used as a format for writing for the web
* Influenced by setext,atx,Textile,reStructured,Grutatext,email format
* Not a replacement for HTML
* HTML is a publishing format; Markdown is a writing format
* Simply use HTML markup if Markdown's syntax don't have<br> e.g.:[link markdown][]   <a href="http://www.xxx.com">link html</a>  

[link markdown]:http://www.xxx.com
<br>


## BLOCK ELEMENTS

### PARAGRAPHS AND LINE BREAKS

* Separated by one or more blank lines
* A blank line is any line that looks like a blank line 
* Support hard-wrapped
* End a line with two or more spaces, then type return can generate </br>

### HEADERS

* Two styles of headers, **Setext** and **Atx**
* Setext-style
    1. Equal signs (for first-level headers).
	2. Dashes (for second-level headers)
	3. Any number of underlining ` = `s or '-'s will work <br>
* Atx-style
	1. 1-6 hash(`#`) characters at the start of the line
	2. Optionally, you may “close” atx-style headers

### BLOCKQUOTES

* Use the > at begin of every line
* Also support put the > before the first line of a hard-wrapped paragraph
* Can be nested
* Support contain other Markdown elements, including headers, lists, and code blocks

### LISTS

* Ordered and unordered lists
* Use asterisk(*),pluse(+) and hyphen(-) for unordered list
* Use number followed by period for ordered list
* Actual numbers have no effect 
* Each subsequent paragraph in a list item must be indented by either 4 spaces or one tab
* The blockquote’s > delimiters need to be indented in a list
* The code block needs to be indented twice — 8 spaces or two tabs in a list
* A number-period-space sequence at the beginning of a line maybe wrong recognized 

### CODE BLOCKS

* Simply indent every line of the block by at least 4 spaces or 1 tab
* Continues until it reaches a line that is not indented
* Ampersands (&) and angle brackets (< and >) will be automatically converted into HTML entities

### HORIZONTAL RULES

* Three or more hyphens(`-`), asterisks(`*`), or underscores(`_`) on a line by themselves

<br>

## SPAN ELEMENTS

### LINKS

* Two style : **inline** and **reference**
* Inline 
	1. \[something](url "Optional Title")
* Reference
	1. \[**something**][id] <br>
	2. Id may consist of letters, numbers, spaces, and punctuation — but they are not case sensitive
	3. Id can be omitted,and use **something** as the id.

### EMPHASIS

* Use asterisks (`*`) and underscores (`_`)
* Text wrapped with one * or _ will be italic 
* Text wrapped with double * or _ will be bold

### CODE

* Use backtick quotes (`` ` ``) wrapped the text
* Use multiple backticks as the opening and closing delimiters if text include a literal backtick character

### IMAGES

* Begin with `!` ,then use just as link defined

<br>

## OTHERS

### AUTOMATIC LINKS

* Surround the URL or email address with angle brackets to show the actual text
  of a URL or email address  
  e.g.:<http://www.xxx.com>,<joebo@yoho.cn>

### BACKSLASH ESCAPES

* Use backslash escapes to generate literal characters
* Characters can be escaped  

![character](http://static.hibox.org/attachment/openPermissionFile/XWFWaA05BDdUMgM7UCRVMAE1XzcKbAg6AzUPaFI9UTcPZVE7VmEHYwc3VTxRaQlkUGBUYQRkXTMIagAsVzEHfV1gVm0NPAQythumb1024*768.jpg)

<br>
# Markdown Extra

### Footnotes
Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

That's some text with a footnote.[^1]

[^1]: And that's the footnote.


### Strikethrough

Wrap with 2 tilde characters:

~~Strikethrough~~


### Fenced Code Blocks

Start with a line containing 3 or more backticks, and ends with the first line with the same number of backticks:

```
Fenced code blocks are like Stardard Markdown’s regular code
blocks, except that they’re not indented and instead rely on
a start and end fence lines to delimit the code block.
```

### Tables

A simple table looks like this:

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

If you wish, you can add a leading and tailing pipe to each line of the table:

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

Specify alignement for each column by adding colons to separator lines:

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

### Anchor

You can also add an anchor for an element such as Headers, then you can link to this anchor anywhere, when you click that link in the Preview view, it'll auto scroll to the place of the destination anchor.

* \[something text in article](id:anchor1)

Click this [link](#anchor1) in the Preview view will auto scroll to the place of the destination anchor.

### [HOMEPAGE](http://daringfireball.net/projects/markdown/)

<!--# Mou Shortcuts
-->


<!--[setext]:comprised entirely of punctuation characters
[atx]:http://www.aaronsw.com/2002/atx/
[Textile]:http://textism.com/tools/textile/
[reStructured]:http://docutils.sourceforge.net/rst.html
[Grutatext]:http://www.triptico.com/software/grutatxt.html
-->
<!--### INLINE HTML-->