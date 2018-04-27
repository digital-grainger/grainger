---
layout: page
title: Stylesheet
---

# Grainger style sheet  

## Starting each page  
Each page of the Grainger poem will be a separate file. We will join them later.  
Each transcription page must begin with the following information (all words in brackets are what will be changed for each page and for each transcriber). Make sure to include the three dashes before and after this entry. Do not replicate the original heads or footers (i.e., “The Sugar-Cane,” “Book I,” or printers marks):

~~~ markdown
---
layout: poem
title: "page [number]"
editor: [transcriber name]
source: "1764 edition"
---
~~~

Leave two lines between this header and the text of the poem.

## Poetic body  
1. Begin each line with a hyphen, followed by a space and then the text of the line
2. If there is a line number in the original, include the line number in brackets with one space between the first bracket and the line text
3. Include all footnotes on the word that Grainger references using [^f1] (and proceed sequentially: [^f2], [^f3], etc.)
4. Include an empty line in between stanzas  
/*Note: previously, the idea was introduced to indent the first line of each stanza. This idea will be revisited at a later time as we transcribe. In the meantime, please write the first line as a normal line of poetry.*


## Between the poetic lines and the footnotes
The poetic lines will be followed by a horizontal break (make sure to include empty lines before and after the break):  
[poetic line]
~~~ markdown

---

~~~
[footnote text]

## Footnotes  
1. Begin with `>` followed by a space and then the text of Grainger's footnote.
2. For footnotes that include more than one paragraph: once you complete the first paragraph, include two spaces after the period and then hit enter. This will start a line break rather than a new section. 
3. If you would like to add editorial footnotes, please include your initials in parentheses at the end of each footnote that you add.

### General Markdown guide  
1. To italicize, enclose the word in asterisks, like `*this*`  
2. To bold, enclose the word in double asterisks, like `**this**`  
3. To add a comment to which you can return later, `<!--[text of comment]-->`   

### General transcription guide (from Julie)  
1. Do replicate capitalizations, except in the case of capital letters of a slightly larger size beginning words in all caps: those letters should be rendered as regular capital letters
2. Do not transcribe the long s: transcribe as regular “s”
3. Do not replicate ligatures between letters
4. Do not include spaces around commas, n-dashes, or m-dashes
5. Do not use “curly” apostrophes or any other curly punctuation
6. Do not italicize commas that separate italicized items in a list. For example, the commas between the following words are not italicized (and neither is the closing period): *horses*, *cats*, *dogs*.
7. Do italicize commas and other punctuation if they appear as part of a longer, continuous piece of italicized text (the final comma is italicized as well). For example, *It was raining horses, cats, and dogs.*
