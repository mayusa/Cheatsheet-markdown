
From [Github - Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
# Markdown Examples

##1.Text
---
'It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)

##2.Lists 
---
Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

##3.Images 
---
If you want to embed images, this is how you do it:

![Image of Yaktocat](https://kev.inburke.com/wp-content/uploads/2014/04/hackedocat-300x300.png)
##4.Headers & Quotes 
---
###- Headers:

This is H1
==========

This is H2
----------

atx-style:

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6

### - Quotes

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

##5.Code 
---
There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

##6.An email <example@example.com> link.
---
Simple inline link <http://chenluois.com>, another inline link [Smaller](http://25.io/smaller/), one more inline link with title [Resize](http://resizesafari.com "a Safari extension").

A [reference style][id] link. Input id, then anywhere in the doc, define the link with corresponding id:

[id]: http://25.io/mou/ "Markdown editor on Mac OS X"

Titles ( or called tool tips ) in the links are optional.    
  
  
##7.Extras
---
###7.1 Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*

  
###7.2 Lists
  
#### Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
####Ordered
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b
   
###7.3 Footnotes

Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

That's some text with a footnote.[^1]

[^1]: And that's the footnote.


###7.4 Strikethrough

Wrap with 2 tilde characters:

~~Strikethrough~~
###7.5 Tables

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

Specify alignment for each column by adding colons to separator lines:

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

  
  
  
# Resources
- [segmentfault.com: 78 款 Markdown 工具](http://segmentfault.com/a/1190000000506986)
- [Github: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Mahua: Online markdown editor ](http://mahua.jser.me/)
