---
title: "My1st eTextbook Boilerplate"
author: Harry Longworth
date: 2025-11-12
layout: eBook
tags:
  - markdown
  - yaml
  - metadata
---
# Front Matter

Front matter content as suggested by Kindle Create.

## Title Page

**My1st eTextbook Boilerplate in 2025:**

Ebook Textbook Template, Boilerplate and Example Document Structuring using Markdown, VSCode, Pandoc and Github for Kindle Self Publishing

v0.1 Edition (Alpha Testing)

Status: DRAFT

by Harry Longworth

Amhazing Pty Ltd

`<Publisher Logo Image> here`

[![Amhazing Pty Ltd](media/amhazing-name-logo.png)](https://amhazing.com "Amhazing")

## Contents

[TOC]: # (Use VS Code extension to generate TOC - e.g. Enhanced Markdown Preview)

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Front Matter](#front-matter)
  - [Title Page](#title-page)
  - [Contents](#contents)
  - [Copyright](#copyright)
  - [Feedback](#feedback)
  - [Dedication](#dedication)
  - [Foreword](#foreword)
  - [Preface](#preface)
    - [Boilerplate](#boilerplate)
  - [Introduction](#introduction)
    - [Who and Why?](#who-and-why)
    - [In Scope](#in-scope)
    - [Out of Scope](#out-of-scope)
    - [Prerequisites](#prerequisites)
    - [Outline](#outline)
- [CHAPTER 1: Start with the End in Mind](#chapter-1-start-with-the-end-in-mind)
  - [Legacy of Paper](#legacy-of-paper)
- [CHAPTER 2: Markdown?](#chapter-2-markdown)
- [CHAPTER 3: Markdown Syntax](#chapter-3-markdown-syntax)
  - [Headings `#` and `##`](#headings--and-)
  - [Escape Symbol `\`](#escape-symbol-)
  - [Bullets with `#`, `-` and `_`](#bullets-with----and-_)
  - [Multi level list](#multi-level-list)
  - [Numbered Lists `1.`](#numbered-lists-1)
  - [Bold  `**`](#bold--)
  - [Italics  `_`](#italics--_)
  - [Block Quote  `>`](#block-quote--)
  - [CODE  \`](#code--)
    - [Other Code formats](#other-code-formats)
  - [Alert/code](#alertcode)
  - [Horizontal line `---`](#horizontal-line--)
  - [Manual line break](#manual-line-break)
  - [Indent](#indent)
  - [Tables `|x|x|x|`](#tables-xxx)
  - [Table Text Alignment](#table-text-alignment)
  - [Links = `<>` or ``](#links---or-)
  - [Reference Style Links](#reference-style-links)
  - [Images `![]()`](#images-)
- [CHAPTER ?: Extended Markdown Syntax](#chapter--extended-markdown-syntax)
  - [Underlining](#underlining)
  - [Text Alignment `<center>`](#text-alignment-center)
  - [Colour](#colour)
  - [Strikethrough `~~`](#strikethrough-)
  - [To Do List Checkboxes `- [x]`](#to-do-list-checkboxes---x)
  - [Highlighting `<mark>`](#highlighting-mark)
  - [Subscript](#subscript)
  - [Footnotes ``](#footnotes-1)
  - [Table of Contents](#table-of-contents)
    - [VS Code Extension approach](#vs-code-extension-approach)
    - [Another TOC Way](#another-toc-way)
  - [Comments `[//]: #`](#comments--)
- [CHAPTER ?: Pandoc Conversion](#chapter--pandoc-conversion)
  - [ePub Conversion](#epub-conversion)
  - [MS Word docx Conversion](#ms-word-docx-conversion)
- [CHAPTER 5: Conventions](#chapter-5-conventions)
  - [Formatting](#formatting)
  - [Language](#language)
- [Chapter 6: Testing](#chapter-6-testing)
  - [Kindle Create Testing](#kindle-create-testing)
  - [Kindle Preview Testing](#kindle-preview-testing)
- [END Matter](#end-matter)
  - [About the Author](#about-the-author)
  - [Resources and Links](#resources-and-links)
    - [Markdown](#markdown)
    - [VS Code](#vs-code)
  - [References](#references)
  - [Appendix A - Markdown Cheat Sheet](#appendix-a---markdown-cheat-sheet)
  - [Praise for the Author](#praise-for-the-author)
  - [Review This book please](#review-this-book-please)
  - [Books by this Author](#books-by-this-author)
  - [Books in this Series](#books-in-this-series)
  - [Acknowledgement](#acknowledgement)

<!-- /code_chunk_output -->

Table of Tables

Table of Figures

Table of Equations

Table of Symbols

## Copyright

My1st eTextbook Boilerplate in 2025

Copyright © 2025 Harry Longworth. All rights reserved.

In this case see refer to the Creative Commons license file in the git.

**Kindle Create version:**

Example of content suggested by Kindle Create for his section:

> Start:

All rights reserved.

The characters and events portrayed in this book are fictitious. Any similarity to real persons, living or dead, is coincidental and not intended by the author.

No part of this book may be reproduced, or stored in a retrieval system, or transmitted in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without express written permission of the publisher.

ISBN-13: TBA
ISBN-10: TBA

Cover design by: Harry Longworth
Library of Congress Control Number: TBA
Printed in the United States of America

> END Kindle Create suggestion.

You might also want to add other legal content here. For example:

**Legal Disclaimer:** All care taken, but no responsibility.  You use the information and advice in this document at your own risk!

## Feedback

Please provide and feedback or issues encountered with this work via the contact form on the author's website:

[Harry Longworth](https://harrylongworth.com)

## Dedication

To our family! Thank you for supporting us in the creation of this work.

## Foreword

A foreword should be written by someone other than the Author.  

As this is a brand new project no such someone exists.  If you would like to volunteer to be that person drop me a line.

## Preface

Why you wrote this book. I wrote this because I have a wide range of technical content to publish and this is the logical place to start with go live for all that work.  

By sharing this simple outline and guide and then polishing it over time I, and thus you, don't start my tech how to guides and textbooks with an empty page!

It helps me get my boilerplate checklist of content out of the road and provides a checklist of format.

I hope it serves you well!

Harry Longworth

As I write this, thousands of authors around the world are creating content to share with others and make the world a better place.  The focus of this guide is technical content rather than fiction, but it can still apply to fiction if you choose.

### Boilerplate

What is boilerplate? It's a technical writer term for the sort of content that every document should, or needs, to have in it.  It is the difference between a quick jotted how to guide and a polished professional document - that hopefully - you expect to get paid for.

To quote Google Gemini:

>The term "boilerplate" generally refers to standardized, reusable text, language, or code that can be used in various documents or applications with little or no change

If you come from a programming background, you can consider this my "abstract class" or interface definition. It doesn't instantiate the actual working classes, it provides a high level definition of the interface that I expect most of my textbooks to meet.

This template is the starting point document I use for my eBook textbooks.

I expect it to evolve over time. So stay tuned for version updates!

## Introduction

Kindle Create suggests the use of an Introduction for non fiction books in the front matter as separate from the content.  Not sure why but lets give it a go.

### Who and Why?

Start with your audience in mind, and the problem they have that would compel them to pay to read your book.

For instance this guide is for technical writers, not fiction writers.  i.e. you are working on a textbook or how to guide, not a romance novel.

### In Scope

Be clear up front on What will your book cover.

For example, this one will cover:

- Definitions.  What is an eTextbook.
- Standard structure of an eTextbook.
- Standard content to consider for every technical textbook and document.
- For Example:
  - Navigation.
  - Front Matter.
  - Body formatting.
  - End Matter.
- Content and structure derived from Kindle Create as a starting point.
- Basic tool use.
- Basic Markdown syntax.
- How to test!

### Out of Scope

What won't your book cover! Just as important.

This document will not cover:

- The HTML format.
- the ePub format.
- How to use MS Word.
- how to use Pandoc.
- how to use Kindle Create or Preview.
- Installation of tools.
- Kindle publishing.

### Prerequisites

What do you expect your reader to already know.  

I expect readers of this guide to have a technical background.

### Outline

Provide a quick outline of your book content.  This content should align with your TOC.

# CHAPTER 1: Start with the End in Mind

What should every eTextbook contain?

To answer this question I reviewed a whole bunch of physical and "virtual" textbooks from a range of publishers.

For example, my go to guides for quick start have been the _Dummies_ series <https://www.dummies.com/> by Wiley and the _Complete Idiot_ guides [Wikipedia reference](https://en.wikipedia.org/wiki/Complete_Idiot%27s_Guides).  

I also referenced a number of open source documents on GitHub.  The Godot game engine project docs for example.

You can look at their project  documentation as an example online at:

<https://docs.godotengine.org/en/stable/>

## Legacy of Paper

Historically textbooks were in paper.  And that format had different requirements which bled into the first digital version.  But the requirements for an online, digital, text book are different to what we had back in the old days.  

Now we expect to be able to read our technical content on small screens and ALSO big screens.  We switch between devices depending on the time of the day and our current needs.

That usage provides a challenge.  That challenge is mostly met by the use the ePub format.

So when we consider the options for the configuration, structure and formatting of an eTextbook we need to consider the constraints of the epub format.

Then from a commercial perspective we need to factor in Amazon Kindle eBook use and the restrictions grayscale eInk devices place on our format. 

For example if you want to maximize compatibility then you should drop the use of colored text.  Seems obvious but lots of historical content that was migrated use it.

One of the other key expectations of screen reading content is shorter, sharper content.  We avoid large blocks of text!

So what are the format capabilities we expect for modern electronic reflow textbooks?

Lets start by exploring the use of Markdown.

# CHAPTER 2: Markdown?

ePub is basically HTML and CSS.  But no one wants to think about writing HTML and CSS whilst trying to brain dump.

That often leads us to using editors like MS Word.  But then the problem is we start to have too many options and get distracted into adding color to fonts for example.

If you are a technical writer in the software development space you're then you will be using git.  And then because of that possibly GitHub.

In that case the very first file you are expected to create is a Readme.md for your project.

So in that space Markdown is the the go to text formatting convention.

And you can also use it to create content for website generation and more.

So to that end I focus on the use of Markdown for text content formatting and then in turn the challenges of conversion of that with Pandoc.

You can grab the Markdown version of this document / template from the GitHub for this project.  See resources section at the end for the link.

# CHAPTER 3: Markdown Syntax

Whilst the Markdown is not the point of this book, I include the content below as an example of each of the various capabilities we expect to be able to show in an ePub eTextbook.

Standard Markdown formatting syntax as discussed below is based on the creator's website as listed in the resources section.

Jump to the [Markdown Cheat Sheet](#appendix-a---markdown-cheat-sheet) if you just want a quick reminder of what symbol  to use for what when using Markdown formatting.

## Headings `#` and `##`

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

`#` for Heading 1

`##` for heading 2

_Note:_ I used backticks to escape the hash sign above!

Increase the number of # to reduce heading level (up to 6)

Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

Other type of heading format:  

"Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). "

- Any number of underlining = signs or - signs will work. 

> Heading 1
>`========`

looks like:

Heading 1 <!-- omit from toc --> {ignore=true}
========

AND then:

> Heading 2
> `--------`

looks like:

Heading 2 <!-- omit from toc --> {ignore=true}
--------

But how get heading 3 with this approach?

- You don't?

How many characters do we use so it knows the difference between a HR and a heading?

**NOTE: I use the # heading approach because it makes it easier to relevel headings and opens up level 3 headings.**

That becomes more relevant with long documents where a [TOC](#table-of-contents-1) is essential!

## Escape Symbol `\`

Symbols can be escaped with `\`

For example this guide depends on the ability to escape the various markdown symbols so that they can be presented in the document.

for example escape backtick: \` with ` \` `

and escape tilda with `\~`

Look through out this document in the markdown version for further examples.

## Bullets with `#`, `-` and `_`

can use standard * as list
* foo
* bar

and can nest with tabs or multiple spaces (Four?)

can also use `-` for bullets and lists

- bullet point
- and another

## Multi level list

Use tab or spaces to indent the additional levels of list.

* Item one
  * indented with tab.
  * another with tab.
* Shift tab to go back up a level
    * four spaces indented version.

## Numbered Lists `1.`

Numbered lists can just use repeated 1. or any number followed by a full stop repeated

for example:

>`1. foo`  
>`1. bar`

results in:

1. foo
1. bar

which makes auto/renumbering easier!

**NOTE:** it's the full stop after the number that activates the numbered list.  So use a backslash to escape the full stop e.g. `\.` to prevent numbered list 

## Bold  `**`

'**' for bold at start and end of text to be formatted bold.

`**This should be bold**`

Looks like this:

**This should be bold**

- You do need to to start the text straight after the double stars - i.e. no space.

## Italics  `_`

Use `_` (underscore) for italic at the start and end

for example: (see MD version)

`_this is italic_`

looks like this:

_this is italic_

**Can also use single `*` at start and end to format as italics.**

## Block Quote  `>`

Use `>` per line to have a block quote.

Block quote example:

`> Used for inset / quote style formatting`  
`> and to have your text indented.`  
`> I use double space after each line to force line breaks  ` 

looks like this:

> Used for inset / quote style formatting  
> and to have your text indented.  
> I use double space after each line to force line breaks  

Markdown allows you to be lazy and only put the > before the first line of a hard-wrapped paragraph:

## CODE  \`

use back tick ` to mark out code so can display HTML and symbols etc.

**NOTE:** This is not ' or " (i.e. not the ditto, or floating apostrophe keys) It's the shift \~ key on my keyboard.

or if want shell style code formatting:

` ```sh  

for code excerpts
like this

if else where for while

` ```

Looks like this:

```sh  

for code excerpts
like this 

if else where for while


```

### Other Code formats

> \`\`\`json

if you want the fenced code to be read as JSON format
 

## Alert/code


\` Back tick is the key to the left of 1 on my keyboard.

\` text inside single back tick is annotated\`

and looks like this:

`text inside single tick is annotated`

I use backtick to escape markdown formatting throughout this document.

I use backslash `\` to escape the backticks |:D 

Not sure how effective that is accross platforms? 

## Horizontal line `---`

How do I get the typical HTML horizontal rule? `<HR>`

Use 
`---` 
or
`***`
or
`- - - `
or `___` (underscore)

to get this:

---

which is equivalent to an HTML `<HR>`

## Manual line break


* end a line with two or more spaces 
* handy for code examples etc.

## Indent

- use four spaces
- or tab?


## Tables `|x|x|x|`

> `| Column 1  |  Col 2 |`  
> `| ------ | ------ |`  
> `| Row 1 | column 2 |`  
> `| Row 2 | column 2 |` `

looks like this:

| Column 1  |  Col 2 |
| ------ | ------ |
| Row 1 | column 2 |
| Row 2 | column 2 |

There are way more variations on this subject to be explored!

For example can I get background colour alternation?

Can I force background colours and borders?

## Table Text Alignment


> `| Left | Middle | Right |`  
> `| :---|:----:|---:|`  
> `| Left|Centered|Right|`  
> `| Aligned Left   | Aligned Middle| Aligned Right |`

looks like: 

| Left | Middle | Right |
| :---|:---:|---:|
| Left|Centered|Right|
| Aligned Left   | Aligned Middle| Aligned Right |


_Question:_ Altering the number of `-`  in the second formatting row results in what outcome? Does it increase column width?

- - -

## Links = `<>` or `[]()`

Some platforms will show a URL as a link just based on the format of the url for example:

https://github.com

which can be turned off with code backticks like this:

> \`https://github.com\`  

looks like this:

`https://github.com`

Can always just enclose in `< >` too.

> `<https://github.com>`

looks like:

<https://github.com>

**Markdown Link format:**

Otherwise the format for a link is:

> `[text label](URL)`

for example:


`[John's Website](https://daringfireball.net/projects/markdown/)`

looks like this:

[John's Website](https://daringfireball.net/projects/markdown/)

**NOTE:**  important that there are no space between square brackets and link in brackets!

Can have image links too.

Can add a URL hover title:

> `[text label](URL "title")`

[text label](URL "title")

_hover over the top to see the title text._

## Reference Style Links

Reference style label:

An `[example][id]`. Then, anywhere
else in the doc, define the link:

 `[id]: http://example.com/  "Title"`

_Question:_ How would I refer to content in a github sub folder for example? eg. relative rather than absolute URLs?

## Images `![]()`

`![alt text](/path/img.jpg "Title")`

or reference style

`![alt text][id]`

then later:
`[id]: /url/to/img.jpg "Title"`

-------------------------------

# CHAPTER ?: Extended Markdown Syntax

Source for most of this is the markdown guide Hacks page.

Extended syntax might not be supported on all platforms.

## Underlining

Not included because in HTML underlining normally was a way of indicating a URL / link.

## Text Alignment `<center>`

Can I center text for example?

**No.**

Use HTML instead.  
e.g. `<center>` tag which is depreciated.. so use css etc..

<center>Does this work?</center>

## Colour

Use HTML.

## Strikethrough `~~`

Use `~~`

An extended feature though so maybe not supported everywhere? 

An example of strikethrough:

>\~~Strike me!\~~

looks like:

> ~~Strike me!~~

## To Do List Checkboxes `- [x]`

to create a checkbox list on platforms that support the extended syntax:

>`- [x] Task that is checked`  
>`- [ ] Item that is not checked`  
>`- [ ] Item 3`

looks like this:

- [x] Task that is checked
- [ ] Item that is not checked
- [ ] Item 3
  

## Highlighting `<mark>`

Either use the double equals like this `==`

or the HTML `<mark>` tag

`==Highlighted text==`

looks like

==Highlighted text==

_Note:_ didn't work in VS Code.

**HTML Approach:**

`<mark>Marked Text</mark>`

looks like 

<mark>Marked Text</mark>

_Note:_ Worked in VS Code.

## Subscript

use the `~` just a single one instead of strike through.

>`H~2~O`

looks like this

H~2~O

_Note:_ Didn't work on VS Code

## Footnotes `[^1]`

Here's a sentence with a footnote. `[^1]`

`[^1]`: This is the footnote.

Looks like:

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

**Doesn't work in VS Code but does in Github.**

What about more than one with the same number (i.e. `[^1]`) as we wouldn't want to have to individually number each footnote.

Bad news there - you need to annotate with numbers unique to each one.

Another footnote - footnote 2 [^2]

[^2]: This is the second footnote.


## Table of Contents

### VS Code Extension approach

Use the VS Code All in one TOC creation from the command pallet (ctrl shift P)

Details on the command pallet from Microsoft:

[VS Code Command Pallet](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette)

and use this to ommit a heading from the TOC:

> `<!-- omit from toc -->`

Which is what I did for the headings in the Headings section 

### Another TOC Way

Problem with this approach is end up with the annotation in the heading if not supported?

Depends on extended syntax?

For example heading IDs:

[Heading IDs](https://www.markdownguide.org/extended-syntax/#heading-ids)

where you add the equivalent to the standard HTML anchor tag to your headings with curly braces.

`### My Great Heading {#custom-id}`

and then in the table:

`[Heading IDs](#heading-ids)`

## Comments `[//]: #`

Comments that aren't to be shown in the final result can be marked as this:

> `[comment]: #`

Can't be seen (look at the markdown version to see comment below)

[comment]: #

[another comment here]: #

If that doesn't work, alternatively this approach:

`[//]: # (Comment text in here)`

looks like:

[//]: # (Comment text in here)

# CHAPTER ?: Pandoc Conversion

Pandoc is the tool I use to convert Markdown into eBooks in the form of an ePub that I can then upload to Kindle.

There are multiple reasons to bypass Kindle Create and go straight to ePub format which I'll discuss elsewhere.

## ePub Conversion

With Pandoc installed you can generate an ePub from VSCode with the Markdown Preview Enhanced export option menu if have pandoc and Calibre installed.

You will need a cover image to test:

- Recommended dimensions: 1600 x 2400 pixels (1.5:1 ratio)
- Format: JPEG or PNG (but JPEG)
- Maximum file size: Under 4MB

Place the cover image in the same location as your markdown file. Call it cover.png for example. Make sure it is big enough of Kindle Preview will fail.

Optional step: configure an epub.css file with a style sheet for custom format configuration.

Setup a metadata.yaml file:
`--- title: My Fantastic Book author: Jane Doe
date: 2025-11-09 identifier: doi:10.123456789/mybook
lang: en-US
---`

Then use Pandoc to convert from markdown  to ePub:

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output.epub --standalone --metadata-file=metadata.yaml --epub-cover-image=cover.png`

Warning! This document currently fails the Kindle Preview import.

Testing in progress for compatibility corrections.

That testing is part of the purpose for the creation of this document.

## MS Word docx Conversion

Basic Markdown to docx conversion command in Pandocs:

> `pandoc input.md -o output.docx`

which for this document and github repo is:

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output.docx`

# CHAPTER 5: Conventions

Here are some example conventions for eTextbooks and the use of Markdown.

## Formatting

- I format chapter headings with all upper case so that I can see them during Kindle Create conversion testing.
- Avoid underlining.  That's for hyper links.
- Avoid comments in brackets - it breaks the flow and because we are focusing on Markdown brackets are used to indicate links and images.
- avoid colored text.  It won't show very well on grayscale eInk devices.
- Grayscale diagrams.  Same applies to pictures, figures and diagrams.  Plan for black and white.

## Language

If you are focused on Kindle publishing then you are probably focused on the US market. That means you should be using the English US dictionary as much as that might pain you.

# Chapter 6: Testing

How do we test this works?

- convert to a MS Word docx so you can feed into Kindle Create to get an idea of where the formatting issues are that require the use of ePub.
- test in Kindle preview.  You'll have to bug hunt your format if you start this testing with a complex format.  Best to start testing here early!  For example images and CSS issues.
- Convert to ePub with Pandoc
- Send to kindle as an ePub.
- Calibre for ePub viewing and editing is another option.
- Check Github it to see how Github converts.
- Read it on a range of devices with small and large screen dimensions.
- read on an eInk kindle that is not color.
- Increase and reduce font size
- Test Dark and Light mode on tablets and phones.

## Kindle Create Testing

The kindle create testing process used for this document is a two step process.

Pandoc is used to create a docx format version which is then imported into Kindle Create. 

No modifications are made in Word to that document. Although they could be, that would not be the point of using Markdown as our master format.

Kindle Create conversion has limitations as discussed below:

- Conversion of document structure below Heading 1 is introduced as all heading 1 level unless you unselect the lower level headings.  
- The table of contents creation option in Kindle Create doesn't support structure below Heading 1 style.
- Kindle strips monospace formatting out of word documents.
- Block quote format doesn't convert.

## Kindle Preview Testing

This document - v0.1 - fails test.  Kindle Preview doesn't import successfully as you can see from the conversion log.

Testing in progress.

# END Matter

This is the sort of content that Kindle Create with the addition of Resources and References headings and Appendix.

## About the Author

Harry Longworth is the author of this work. My author website can be found here:

<https://harrylongworth.com>

Please provide any feedback or raise issues on this work via my contact page.

Check my LinkedIn Profile for more information and my credentials:

<https://www.linkedin.com/in/harry-longworth-amhazing/>

`<Author Image>` required by Kindle Create so here's mine as an example:

[![Harry Longworth](media/harry-longworth.jpg)](https://harrylongworth.com "Harry Longworth")

## Resources and Links

### Markdown

Markdown creator's website:  
[John Gruber's Website](https://daringfireball.net/projects/markdown/) 

First Google search return result on Markdown guide:
[markdownguide.org](https://www.markdownguide.org/getting-started/)

### VS Code

VS Code Enhanced Markdown Preview Extension:
[Enhanced Markdown Preview on Github](https://shd101wyy.github.io/markdown-preview-enhanced)

## References

John Gruber's Syntax guide:  
[daringfireball.net](https://daringfireball.net/projects/markdown/syntax)

## Appendix A - Markdown Cheat Sheet

Markdown Cheat sheet provided as an example of an Appendix:

| Symbol  |  Result | Details
| ------ | ------ | ------ | 
| \# or \#\# | Heading | [Headings](#headings--and-) |
| \\ | Escape Symbols | [Escape](#escape-symbol-)|
| \* , \- , \+  | Bullet Lists | [Bullets](#bullets-with----and-_) |
| Tab or 4 spaces  | Multi level List | [Multi level list](#multi-level-list) |
| 1\. | Numbered List | [Numbered Lists](#numbered-lists-1) |
| \*\* | Bold | [Bold](#bold--) |
| \_  Underscore | Italics | [Italics](#italics--_) |
| \> | Block Quote | [Block Quote/Indent](#block-quote--) |
| \` Backtick | Code | [CODE](#code--) |
| `--- , * * * , ___` | HR | [Horizontal line - HR](#horizontal-line----) |
| space x 2 | Manual line break | [Manual line break](#manual-line-break) |
| tab | indent | [Indent](#indent) |
| `[text](url)` | Link | [Links](#links---or-) |
| `! [text](url)` | Image | [Images](#images-) |
| `<center>` | center | [Text Alignment](#text-alignment-center) |
| \~\~ | Strikethrough | [Strikethrough](#strikethrough-) |
| `- [x]` | Checkbox | [To Do List Checkboxes](#to-do-list-checkboxes---x) |
| `<mark>` | Highlight | [Highlighting](#highlighting-mark) |
| `[^1]` | Footnote | [Footnotes](#footnotes-1) |
| `[]: #` | Hidden comment | [Comments `[]: #`](#comments--) |

Markdownguide.org has a good cheat sheet too:

[https://www.markdownguide.org/cheat-sheet/](https://www.markdownguide.org/cheat-sheet/)

## Praise for the Author

Insert your positive reviews here

## Review This book please

Please review this book positively and widely if you liked it!  

That's one of the best ways you can thank me for the hard work that went into putting this guide together.  

Thank you for reading this far!

## Books by this Author

See the My1st.org website for current books in this series.

## Books in this Series

See the My1st.org website for current books in this series.



## Acknowledgement

Without the work of open source creators around the world this work would not have been possible! Thank you.

