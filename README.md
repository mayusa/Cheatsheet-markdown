
From [Github - Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
# Markdown Examples  

###Contents
1. [text](#1text)
2. [lists](#2lists)
3. [images](#3images)
4. [headers & quotes](#4headers--quotes)
5. [code](#5code)
6. [An email example@example.com link.](#6an-email-exampleexamplecom-link)
7. [extras](#7extras)
	1. [emphasis](#71-emphasis)
	2. [emoji icons (github)](#72-emoji-icons-github)
	3. [strikethrough](#73-strikethrough)
	4. [tables](#74-tables)
	5. [check box](#75-check-box-github) 
8. [resources](#resources)  

---
 
	


##1.Text

'It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)  

```
markdown code:
'It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)
```

##2.Lists 

*Sometimes you want numbered lists:*

1. One
2. Two
3. Three


```
markdown code: 
1. One
2. Two
3. Three
```


*Sometimes you want bullet points:*

* Start a line with a star
* Profit!

```
markdown code:
* Start a line with a star
* Profit!
```
*Alternatively,*

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

```
markdown code:
- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
```

##3.Images 

*If you want to embed images, this is how you do it:*

![Image of Yaktocat](https://kev.inburke.com/wp-content/uploads/2014/04/hackedocat-300x300.png)  

```
markdown code:
![Image of Yaktocat](https://kev.inburke.com/wp-content/uploads/2014/04/hackedocat-300x300.png)
```
##4.Headers & Quotes 

###- Headers:

*atx-style:*

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6  

```
markdown code:
# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6

```

### - Quotes

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

```
markdown code:
> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway
```
##5.Code 

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in **backticks**: `var example = true`.   

```
markdown code:
`var example = true`
```
If you've got a longer block of code, you can indent with __four spaces__:

    if (isAwesome){
      return true
    }

```
markdown code:
    
____if (isAwesome){
________return true
____}
    
```
GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```  

```
markdown code:
    ```
    if (isAwesome){
    	return true
    }
    ```
```
And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

##6.An email <example@example.com> link.

- inline link <http://chenluois.com>,   
- another inline link [Smaller](http://25.io/smaller/),   
- one more inline link with title [Resize](http://resizesafari.com "a Safari extension").

```
markdown code:
- inline link <http://chenluois.com>,   
- another inline link [Smaller](http://25.io/smaller/),   
- one more inline link with title [Resize](http://resizesafari.com "a Safari extension").
```
A [reference style][id] link. Input id, then anywhere in the doc, define the link with corresponding id:

[id]: http://25.io/mou/ "Markdown editor on Mac OS X"

Titles ( or called tool tips ) in the links are optional.    
  
  
##7.Extras

###7.1 Emphasis
*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

*You **can** combine them*  


```
markdown code:
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*
```



   
###7.2 Emoji icons (github)
[emoji-cheat-sheet](http://www.emoji-cheat-sheet.com/)  

I love Emoji  :sparkles: :camel: :boom:

```
markdown code:
I love Emoji  :sparkles: :camel: :boom:
```

###7.3 Strikethrough

_Wrap with 2 tilde characters:_

~~Strikethrough~~
  
```
markdown code:
~~Strikethrough~~
```
###7.4 Tables

A simple table looks like this:

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell
  
```
markdown code:
First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell
```

If you wish, you can add a leading and tailing pipe to each line of the table:

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |  

```
markdown code:
| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |
```

Specify alignment for each column by adding colons to separator lines:

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

```
markdown code:
First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right
```

###7.5 Check Box (github)
- [x] This is a complete item
- [ ] This is an incomplete item
  
```
markdown code:
- [x] This is a complete item
- [ ] This is an incomplete item
```

  
# Resources

- [segmentfault.com: 78 款 Markdown 工具](http://segmentfault.com/a/1190000000506986)
- [Github: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Mahua: Online markdown editor ](http://mahua.jser.me/)
- [emoji-cheat-sheet](http://www.emoji-cheat-sheet.com/)   
- [创始人John Gruber的Markdown语法说明](http://daringfireball.net/projects/markdown/syntax)
- [Markdown中文版语法说明](http://wowubuntu.com/markdown/#list)

--- 
by ashucn@gmail.com 3/5/2015  
  

