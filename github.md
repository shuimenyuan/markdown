#github
###URL autolinking
GFM will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.

###Fenced code blocks 
support

```
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Footnotes 不支持  Strikethrough 支持  Anchor 不支持

#stack
###URL autolinking
###Images ![atx]() 当显示不了图片时，atx会显示
[tag:elephants] 
###Spoilers
To hide a certain piece of text and have it only be visible when a user moves the mouse over it, use the blockquote syntax with an additional exclamation point: 

<span>This *will* work.</span>

but not within block elements:

/
<div>
  This *won't ddd* work.
</div> 

html 中的markdown


  `<blink>
       <>&You would *hate* this if it weren't
       wrapped in a code block.
  </blink>`
  
  `<body></body>`

