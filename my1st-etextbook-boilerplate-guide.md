---
title: "My1st eTextbook Boilerplate"
author: Harry Longworth
date: 12 Nov 2025
layout: eBook
tags:
  - markdown
  - yaml
  - metadata
---
# FRONT MATTER {.unnumbered}

Front matter included below as suggested by Kindle Create for template purposes.

<center>
## Title Page {.unnumbered}

**My1st eTextbook Boilerplate in 2025:**

Ebook Textbook Template, Boilerplate and Example Document Structuring using Markdown, VSCode, Pandoc and Github for Kindle Self Publishing

v0.1.3 Edition (Alpha Testing)

Status: DRAFT

by Harry Longworth

Publisher

![Publisher](media/publisher.png)
</center>

## Copyright {.unnumbered}

My1st eTextbook Boilerplate in 2025

Copyright © 2025 Harry Longworth. All rights reserved.

In this case see refer to the Creative Commons license file in the git.

**Kindle Create version:**

Below is an example of the copyright text suggested when you use Kindle Create:

---

All rights reserved.

The characters and events portrayed in this book are fictitious. Any similarity to real persons, living or dead, is coincidental and not intended by the author.

No part of this book may be reproduced, or stored in a retrieval system, or transmitted in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without express written permission of the publisher.

ISBN-13: TBA
ISBN-10: TBA

Cover design by: Harry Longworth
Library of Congress Control Number: TBA
Printed in the United States of America

---

You might also want to add other legal content here. For example:

**Legal Disclaimer:** All care taken, but no responsibility.  You use the information and advice in this document at your own risk!

## Feedback {.unnumbered}

Please provide and feedback or issues encountered with this work via the contact form on the author's website:

[Harry Longworth](https://harrylongworth.com)

## Dedication {.unnumbered}

To our family! Thank you for supporting us in the creation of this work.

## Foreword {.unnumbered}

A foreword should be written by someone other than the Author.  

As this is a brand new project no such someone exists.  If you would like to volunteer to be that person drop me a line.

## Preface {.unnumbered}

Why you wrote this book. I wrote this because I have a wide range of technical content to publish and this is the logical place to start with go live for all that work.  

By sharing this simple outline and guide and then polishing it over time I, and thus you, don't start my tech how to guides and textbooks with an empty page!

It helps me get my boilerplate checklist of content out of the road and provides a checklist of format.

I hope it serves you well!

Harry Longworth

As I write this, thousands of authors around the world are creating content to share with others and make the world a better place.  The focus of this guide is technical content rather than fiction, but it can still apply to fiction if you choose.

## Introduction {.unnumbered}

Kindle Create suggests the use of an Introduction for non fiction books in the front matter as separate from the content.  Not sure why but lets give it a go.

### Who and Why? {.unnumbered}

Start with your audience in mind, and the problem they have that would compel them to pay to read your book.

For instance this guide is for technical writers, not fiction writers.  i.e. you are working on a textbook or how to guide, not a romance novel.

### In Scope {.unnumbered}

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

### Out of Scope {.unnumbered}

What won't your book cover! Just as important.

This document will not cover:

- The HTML format.
- the ePub format.
- LaTex format.
- PDF format.
- How to use MS Word.
- how to use Pandoc.
- how to use Kindle Create or Preview.
- Installation of tools.
- Kindle publishing.

### Prerequisites {.unnumbered}

What do you expect your reader to already know.  

I expect readers of this guide to have a technical background.

### Outline {.unnumbered}

Provide a quick outline of your book content.  This content should align with your TOC.

# START HERE

"Start with the End in Mind"

What should every eTextbook contain?

## Boilerplate

What is boilerplate? It's a technical writer term for the sort of content that every document should, or needs, to have in it.  It is the difference between a quick jotted how to guide and a polished professional document - that hopefully - you expect to get paid for.

To quote Google Gemini:

>The term "boilerplate" generally refers to standardized, reusable text, language, or code that can be used in various documents or applications with little or no change

If you come from a programming background, you can consider this my "abstract class" or interface definition. It doesn't instantiate the actual working classes, it provides a high level definition of the interface that I expect most of my textbooks to meet.

This template is the starting point document I use for my eBook textbooks.

I expect it to evolve over time. So stay tuned for version updates!

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

In contrast if we were heading towards a physical print document, then maybe you would consider PDF format as the goal, and content formatting and editing with a platform like LaTeX.

So what are the format capabilities we expect for modern electronic reflow textbooks?

Lets start by exploring the use of Markdown.

# PANDOC CONVERSION

Pandoc is the tool I use to convert Markdown into eBooks in the form of an ePub that I can then upload to Kindle.

There are multiple reasons to bypass Kindle Create and go straight to ePub format which I'll discuss elsewhere.

## Pandoc version of Markdown

Pandoc uses a slightly modified version of Markdown as explained here:

<https://pandoc.org/MANUAL.html#pandocs-markdown>

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

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output.epub --standalone --epub-cover-image=cover.png`

Warning! This document currently fails the Kindle Preview import.

Testing in progress for compatibility corrections.

That testing is part of the purpose for the creation of this document.

## MS Word docx Conversion

Basic Markdown to docx conversion command in Pandocs:

> `pandoc input.md -o output.docx`

which for this document and github repo is:

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output.docx`

## Auto Section Numbering

One of the pain points encountered during testing of this document was auto Chapter numbering.

There is a facility in pandoc to do auto section numbering with the addition of this text to the command:

> `--number-sections`

which for this document results in the word conversion like this:

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-numbered.docx --number-sections`

This gives us a great tiered numbering format for headings so we can clearly illustrate heading depth to the reader.

I would recommend doing this.

Leads to the question of how we skip headings for the front matter though and to what depth of heading?

As a result of the adoption of this approach the word Chapter was removed from headings.

### Heading Depth

You can control the depth of heading with the addition of this command to the prompt:

> `--toc-depth=2`

In this case explore a depth of four with an update to our prompt:
> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-numbered-4.docx --number-sections --toc-depth=4`

ePub version of this export:

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-depth4.epub --standalone  --epub-cover-image=cover.png --number-sections --toc-depth=4`

### Skip Numbering

To prevent numbering of the Front and End Matter add the tag:

> `{.unnumbered}`

or perhaps

>`{-}`

to the headings as done in this document for front and back matter.

Pandoc recommend the `{-}` version of the tag.

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-depth4.epub --standalone --epub-cover-image=cover.png --number-sections --toc-depth=4`

### Pandoc Generated TOC

add the command --toc to the conversion command.

MS Word

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-numbered-toc.docx --standalone --number-sections --toc --toc-depth=4`

ePub

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-depth-toc.epub --standalone --epub-cover-image=cover.png --number-sections --toc --toc-depth=4`

But now the TOC has page numbers which we don't want for eBooks.

So have to do an intermediate .md file creation!

> `pandoc my1st-etextbook-boilerplate-guide.md -o dist/output-md-toc.md --standalone --number-sections --toc --toc-depth=4`

and then commands above without the toc components



# TESTING

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

# END MATTER {-}

This is the sort of content that Kindle Create with the addition of Resources and References headings and Appendix.

## About the Author {-}

Harry Longworth is the author of this work. My author website can be found here:

<https://harrylongworth.com>

Please provide any feedback or raise issues on this work via my contact page.

Check my LinkedIn Profile for more information and my credentials:

<https://www.linkedin.com/in/harry-longworth-amhazing/>

[Author](media/author.png)

## Resources and Links {-}

### Markdown {-}

Markdown creator's website:  
[John Gruber's Website](https://daringfireball.net/projects/markdown/)

First Google search return result on Markdown guide:
[markdownguide.org](https://www.markdownguide.org/getting-started/)

Pandoc version of Markdown:
[Pandoc on Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown)

### VS Code {-}

VS Code Enhanced Markdown Preview Extension:
[Enhanced Markdown Preview on Github](https://shd101wyy.github.io/markdown-preview-enhanced)

## References {-}

John Gruber's Syntax guide:  
[daringfireball.net](https://daringfireball.net/projects/markdown/syntax)

## Praise for the Author {-}

Insert your positive reviews here

## Review This book please {-}

Please review this book positively and widely if you liked it!  

That's one of the best ways you can thank me for the hard work that went into putting this guide together.  

Thank you for reading this far!

## Books by this Author {-}

See the My1st.org website for current books in this series.

## Books in this Series {-}

See the My1st.org website for current books in this series.

## Acknowledgement {-}

Without the work of open source creators around the world this work would not have been possible! Thank you.

# APPENDIX A - Pandoc Cheat Sheet {-}