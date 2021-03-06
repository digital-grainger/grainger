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


[pagenumber]()
~~~

Notice that, in the header above, there are two empty lines between the horizontal break and the bracketed page number. Include one empty line between the bracketed page number and the first line of poetry.

If you are transcribing a page that isn't poetry, use the layout: page to make sure it renders correctly.

As a general rule, modernize typography. But do not modernize or correct any of Grainger's spelling (or misspelling). We can discuss specific instances (and see the general transcription guide section below for some specific cases we've already come up with rules for).

## Saving each page
1. Naming convention: sc-page000.md
2. For an implicit page: sc-page000i.md (these include blank pages)
3. For pages that are named (e.g. preface): sc-preface.md

## Poetic body  
1. Begin each line with a hyphen, followed by a space and then the text of the line
2. If there is a line number in the original, include the line number in brackets with one space between the first bracket and the line text
4. Include an empty line in between stanzas  
\*Note: previously, the idea was introduced to indent the first line of each stanza. This idea will be revisited at a later time as we transcribe. In the meantime, please write the first line as a normal line of poetry.
5. Mark spots where you would like to put an internal link with [internal] so we can find and replace later.
6. Do not correct errata. Instead, mark with an editorial footnote on the same page.


## Between the poetic lines and the footnotes
The poetic lines will be followed by a horizontal break (make sure to include empty lines before and after the break):  
[poetic line]
~~~ markdown

---

~~~
[footnote text]

## Footnotes  
1. Begin with `>` followed by a space and then the text of Grainger's footnote.
2. Include a \ before the bracket of the footnote (this prevents the bracket from being confused as something else later)
3. For footnotes that include more than one paragraph: once you complete the first paragraph, include two spaces after the period and then hit enter. This will start a line break rather than a new section. Then include `>` and one space before continuing to transcribe the text.
4. If you would like to add editorial footnotes, please include your initials in parentheses at the end of each footnote that you add.

## For title pages
1. use \# for "The Sugar-Cane" and \#\# for the book number

### General Markdown guide  
1. To italicize, enclose the word in asterisks, like `*this*`  
2. To bold, enclose the word in double asterisks, like `**this**`
3. For an m-dash: shift option hyphen. When Grainger has a double m-dash, just type two m-dashes for now. 
4. For Greek and Hebrew characters, see links sent by email from Julie. Make sure to include the ampersand and the semicolon.
5. To add a comment to which you can return later, `<!--[text of comment]-->`   

### General transcription guide (from Julie)  
1. Do replicate capitalizations, except in the case of capital letters of a slightly larger size beginning words in all caps: those letters should be rendered as regular capital letters
2. Do not transcribe the long s: transcribe as regular “s”
3. Do not replicate ligatures between letters
4. Do not include spaces around commas, n-dashes, or m-dashes
5. Do not use “curly” apostrophes or any other curly punctuation
6. Do not italicize commas that separate italicized items in a list. For example, the commas between the following words are not italicized (and neither is the closing period): *horses*, *cats*, *dogs*.
7. Do italicize commas and other punctuation if they appear as part of a longer, continuous piece of italicized text (the final comma is italicized as well). For example, *It was raining horses, cats, and dogs.*

## To add to github
1. Navigate into \_texts folder
2. Select "Upload files" at the top of the page
3. Describe what you did in notes: e.g. "transcription for page 57"
4. If you want to add editorial notes, add them to the extended description
5. Commit file to master branch

