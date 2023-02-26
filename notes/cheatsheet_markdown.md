___
#awake
```Markdown
<!---
This file was created in obsidian
use `<!--- COMMENT --->` to make a comment
--->
```
___
#linebreaking
```
To break a line simply use `Enter/return key` twice

Your text will then appear on the next like so

Remeber to seperate your lines, or...
They will stitch togethor like this.
```
To break a line simply use `Enter/return key` twice.

Your text will then appear on the next like so

Remeber to seperate your lines, or...
They will stitch togethor like this.
___
#headers
```markdown

# heading1 example
## heading2 example
### heading3 example
#### heading4 example
##### heading5 example
###### heading6 example

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

```
# heading1 example
## heading2 example
### heading3 example
#### heading4 example
##### heading5 example
###### heading6 example

Alt-H1
======

Alt-H2
------
___
#lists
```

- [] Github Markdown uses `- [] ` to create to do lists
1. A list can be started with any number `1.`
  * Unordered sublist via `..*` or `-` or `+`
  1. Sub lists also accept numbers `..1.` or `..-` or '..+'

```

- [list item] 
1. Numbered list
  * Unordered list
   * Sub Listing is based on number of `...` used
___
#emphasis
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

```

*Asterisk* or _Underscore_ 

**Asterisks** or __Underscores__

*__These can be used in combination__*

~~Tildes~~
___
#linkin
```
Linki

form1 inline-style

[I'm an inline-style link](https://www.notpornhub.com)

form2 inline-style w/ Title
[I'm an inline-style link with title](https://www.pornhub.com "It's not pornhub I swear")

form3 reference-style

[Totally Not Pornhub][Referencetag]

[Referencetag]: https://www.pornhub.com

[0]: https://www.pornhub.com
#numbers can be used for tagging

[]: https://www.pornhub.com
#blank will use the link as a tag

form4 relative-reference-style

[CSS Cheatsheet Link]("C:\Git\notes\notes\CSSCheatsheet.md")

#direct pathing: create links to files
#relative pathing: move from the present file to a parent/child directory and select file

form5 reference-style link can be used with numbers too



```

`form1`
[I'm an inline-style link](https://www.google.com)

`form2`
[I'm an inline-style link with title](https://www.pornhub.com "It's not pornhub I swear")

`form3`
[Totally Not Pornhub][Referencetag]
[Referencetag]: https://www.pornhub.com

[Totally Not Pornhub][0]

[0]: https://www.pornhub.com

Something [1]
[1]: https://www.pornhub.com

`form4`
[CSS Cheatsheet Link](C:\Git\notes\notes\cheatsheet_css.md)
[Readme Link](..\README.md)

`form5`

Or leave it empty and use the [tag]
[tag]: http://www.pornhub.com
___
#images
```
Here's our logo (hover to see the title text):

form1
Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title ext 1")

form2
reference-style: 
![alt text][logo]

form3
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

`form1`
![hover over text](https://di.phncdn.com/www-static/images/pornhub_logo_straight.svg?cache=2023022302)

`form2`
![Click me bruh](logo)
`form3`
[logo]: https://di.phncdn.com/www-static/images/pornhub_logo_straight.svg?cache=2023022302 "Logo Title Text"

___
#codeblocks
````
#codeblocks can be used to visually display chunks of code

form1
`Simply wrap text in accents(~tilde key)`
 
````

`form1`
___
#syntaxhighlighting
````
#codeblocks can be used to 

form1
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

form2
```python
s = "Python syntax highlighting"
print s
```
 
````

`form1`
```javascript
var form1 = "JavaScript syntax highlighting";
alert(form1);
```
 `form2`
```python
form2 = "Python syntax highlighting"
print form2
```
___
#footnotes
```
#footnotes can be used to add references to the bottom of a page

`[^0]` Create a footnote with the number 0

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

form1 single-line footnote
[^0]: This is a footnote

form2 multi-line footnote
[^1]: Footnotes can be 
  Multi lined notes require `..`

form3 named-footnote

[^name]:
	This footnote has a name, it still displays a number but can be referenced
	Via it's name for easier coding

```

`form1`
form1 Example[^0]

form2 Example[^1]

form 3 Example[^name]

[^0]: single-line footnote
  [^1]: multiline.  
  footnote.
[^name]: named-footnote
___
#table
```
#tables can be created from plain text

`|---|` 3 Dashes make the above a header cell
```

Waifu | Score | Trait
--- | --- | ---
*Mikasa* | `10/10` | **Hot**
*Hinata* | `10/10` | **Medium**
*Yo momma* | `11/10` | **MILF**
___
#BlockQuotes 
```
#It's greentext but less wizard flavoured

`>.` Creates a block Quote
```

>Commonly used to roast specific parts of internet arguments
>Or to tell fire stories without massive paragraphs
___
#inlineHTML
```
#inlineHTML can be used inside of markup but it's finnicky and you can literally just use HTML so it's cool that it works but... redundant

form1
<dl>
  <body>  
  
<h1>This was made</h1>  
<i><p>using html in markup but...</p> </i> 
<b>Don't do this, just use HTML</b>
</body>
</dl>

```

`form1`
<dl>
  <body>  
  
<h1>This was made</h1>  
<i><p>using html in markup but...</p> </i> 
<b>Don't do this, just use HTML</b>
</body>
</dl>

___

#HorizontalRule
```
#you can make content more readable by using spacing lines to break sections up
#all three forms produce the same result

form1
Hyphens
***

form2
Asterisks
___

form3
Underscores
```

`form1`

---


`form2`

***

`form3`

___

#youtube
```
#youtube videos cannot be embedded but an image preview can be generated from a link

<a href="http://www.youtube.com/watch?feature=player_embedded&v=C7cPUez_7v8
" target="_blank">
	<img src="http://img.youtube.com/vi/C7cPUez_7v8/0.jpg" 
	alt="watch it bruh" width="240" height="180" border="10" />
</a>
```

<a href="http://www.youtube.com/watch?feature=player_embedded&v=C7cPUez_7v8
" target="_blank">
	<img src="http://img.youtube.com/vi/C7cPUez_7v8/0.jpg" 
	alt="watch it bruh" width="240" height="180" border="10" />
</a>
___