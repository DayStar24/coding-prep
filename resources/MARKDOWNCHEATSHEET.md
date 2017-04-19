---
title: Markdown Cheatsheet
currentMenu: resources
---
## Basic Markdown Syntax  
To demonstrate the various effects of Markdown syntax, we'll first see the code as it appears in a Markdown document (in the shaded box), and then how the text looks when it is rendered into HTML.  

### Italics:  
```nohighlight
_These underscores will italicize this statement_
*These single asterisks will also italicize this statement*
```  
_These underscores will italicize this statement_  
*These single asterisks will also italicize this statement*  

### Bold:  
```nohighlight  
**These two asterisks will make this statement bold** 
```  
**These two asterisks will make this statement bold**   

### Headers:
```nohighlight  
Hint: the level of a header is equal to the number of hash marks before it  

# Header One
## Header Two
### Header Three
#### Header Four
##### Header Five
###### Header Six
```  
# Header One  
## Header Two  
### Header Three  
#### Header Four  
##### Header Five  
###### Header Six  

### Links without Text:  
```nohighlight  
<http://google.com>  
```  
<http://google.com>  

### Inline Links:  
```nohighlight  
[Text you want to be hyperlinked](google.com)
```  
[Text you want to be hyperlinked](google.com)  

### Reference Links:  
```nohighlight 
Here's [a link to something else][another place].
Here's [yet another link][another-link].
And now back to [the first link][another place].
[another place]: www.github.com
[another-link]: www.google.com
```  
Here's [a link to something else][another place].  
Here's [yet another link][another-link].  
And now back to [the first link][another place].  
[another place]: www.github.com  
[another-link]: www.google.com  

### Inline Images:  
```nohighlight
![Cute Cat](http://www.cutestpaw.com/wp-content/uploads/2011/11/cute-cat.jpg)
```  
![Cute Cat](http://www.cutestpaw.com/wp-content/uploads/2011/11/cute-cat.jpg)  

### Reference Images:  
```nohighlight  
![Cute Cat][Everyone Loves Kittens]
[Everyone Loves Kittens]: http://www.cutestpaw.com/wp-content/uploads/2011/11/cute-cat.jpg
```  
![Cute Cat][Everyone Loves Kittens]  
[Everyone Loves Kittens]: http://www.cutestpaw.com/wp-content/uploads/2011/11/cute-cat.jpg  

### Blockquotes:  
```nohighlight
> "Stuff you want in the blockquote."
```  
> "Stuff you want in the blockquote."  

### Multi-Line Blockquotes:  
```nohighlight  
> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.
```
> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.  

### Unordered List: 
```nohighlight
Note: the space b/w the * and the list item is important! 
So is each item being on new line!

* One list item
* Another list item
* Yet another list item
```  
* One list item  
* Another list item  
* Yet another list item  

### Ordered List:  
```nohighlight  
Again: the space b/w the number and the list item is important! 
So is each item being on new line!

1. First list item
2. Second list item
3. Third list item
```  
1. First list item  
2. Second list item  
3. Third list item  

### Nested Unordered List:  
```nohighlight
Note: indent each inner list item by one space more than its outer list.

* Tintin
 * A reporter
 * Has poofy orange hair
 * Friends with the world's most awesome dog
* Haddock
 * A sea captain
 * Has a fantastic beard
 * Loves whiskey
```  
* Tintin
 * A reporter
 * Has poofy orange hair
 * Friends with the world's most awesome dog
* Haddock
 * A sea captain
 * Has a fantastic beard
 * Loves whiskey  

### Lists With Paragraph Text (or other non-list text):  
```nohighlight
Note: extra line is important, and indent at least one space.  

1. Crack three eggs over a bowl.

 Now, crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Don't be messy, but if you are, clean it up!
```  
1. Crack three eggs over a bowl.

 Now, crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Don't be messy, but if you are, clean it up!  

### Paragraphs:  
```nohighlight  
Create new line by adding 2 spaces above the new line.
Dots below represent where the two spaces would be. 

Do I contradict myself?··
Very well then I contradict myself,··
(I am large, I contain multitudes.)
```  
Do I contradict myself?  
Very well then I contradict myself,  
(I am large, I contain multitudes.)  

### Code Blocks:  
```nohighlight
Create by using 1 tab, or 4 spaces, for the code block.
Additional tab or 4 spaces for indented code lines within that.
Or surround the entire block with opening and closing triple backtics ```

    tell application "Foo"
        beep
    end tell
```  
    tell application "Foo"
        beep
    end tell  

### Inline Code:
```nohighlight
`print("This is a piece of code. Notice the single backticks.")`
```
`print("This is a piece of code. Notice the single backticks.")`  

### Definition List:
```nohighlight  
Term
  : definition

Complex term
  : first definition

  : second definition
```
Term
  : definition   

Complex term
  : first definition

  : second definition

### Horizontal Rules:  
```nohighlight
Note: need a blank line above asterisks/dashes to render a solid line.  

*******
or

------
```  
*******
or

------