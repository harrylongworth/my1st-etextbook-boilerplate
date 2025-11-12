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

# Contents

[//]: # (Use VS Code extension to generate TOC - e.g. Enhanced Markdown Preview)

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Contents](#contents)
- [Front Matter](#front-matter)
  - [Title Page](#title-page)
  - [Copyright](#copyright)
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
- [Chapter 1: Start with the End in Mind](#chapter-1-start-with-the-end-in-mind)
- [Chapter 2: Markdown?](#chapter-2-markdown)
- [Pandoc](#pandoc)
- [Conventions](#conventions)
  - [Formatting](#formatting)
  - [Language](#language)
- [Testing](#testing)
- [End Matter](#end-matter)
  - [Resources and Links](#resources-and-links)
    - [Markdown](#markdown)
    - [VS Code](#vs-code)
  - [References](#references)
  - [Appendix A](#appendix-a)
  - [Praise for the Author](#praise-for-the-author)
  - [Review This book please](#review-this-book-please)
  - [Books by this Author](#books-by-this-author)
  - [Books in this Series](#books-in-this-series)
  - [About the Author](#about-the-author)
  - [Acknowledgement](#acknowledgement)

<!-- /code_chunk_output -->

Table of Tables

Table of Figures

Table of Equations

Table of Symbols

# Front Matter

Front matter content as suggested by Kindle Create.

## Title Page

**My1st eTextbook Boilerplate in 2025:**

Ebook Textbook Template, Boilerplate and Example Document Structuring using Markdown, VSCode, Pandoc and Github for Kindle Self Publishing

First Edition

by Harry Longworth

Amhazing Pty Ltd

`<Logo Image>`

## Copyright

My1st.org eBook Textbook Boilerplate in 2025

Copyright © 2025 Harry Longworth. All rights reserved.

**Kindle Create version:**

Example of content suggested by Kindle Create for his section:

All rights reserved.

The characters and events portrayed in this book are fictitious. Any similarity to real persons, living or dead, is coincidental and not intended by the author.

No part of this book may be reproduced, or stored in a retrieval system, or transmitted in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, without express written permission of the publisher.

ISBN-13: TBA
ISBN-10: TBA

Cover design by: Harry Longworth
Library of Congress Control Number: TBA
Printed in the United States of America

END Kindle Create suggestion.

You might also want to add other legal content here. For example:

Legal Disclaimer: All care taken, but no responsibility.  You use the information and advice in this document at your own risk!

## Dedication

To our family! Thank you for supporting us in the creation of this work.

## Foreword

Why you wrote this book. I wrote this because I have a wide range of technical content to publish and this is the logical place to start with go live for all that work.  

By sharing this simple outline and guide and then polishing it over time I, and thus you, don't start my tech how to guides and textbooks with an empty page!

It helps me get my boilerplate checklist of content out of the road and provides a checklist of format.

I hope it serves you well!

Harry Longworth

## Preface

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

# Chapter 1: Start with the End in Mind

What should every eTextbook contain?

To answer this question I reviewed a whole bunch of physical and "virtual" textbooks from a range of publishers. 

For example my go to guides for quick start have been the Dummies series by Wiley and idiot guides.  

I also referenced a number of open source documents on GitHub.  The Godot game engine project for example.

You can look at their project  documentation as an example online at:

<https://docs.godotengine.org/en/stable/>

Historically textbooks were in paper.  And that format had different requirements which bled into the first digital version.  But the requirements for an online, digital, text book are different to what we had back in the old days.  

Now we expect to be able to read our technical content on small screens and ALSO big screens.  We switch between devices depending on the time of the day and our current needs. 

That usage provides a challenge.  That challenge is mostly met by the use the ePub format.

So when we consider the options for the configuration, structure and formatting of an eTextbook we need to consider the constraints of the epub format.

Then from a commercial perspective we need to factor in Amazon Kindle eBook use and the restrictions grayscale eInk devices place on our format. 

For example if you want to maximize compatibility then you should drop the use of colored text.  Seems obvious but lots of historical content that was migrated use it.

One of the other key expectations of screen reading content is shorter, sharper content.  We avoid large blocks of text!

# Chapter 2: Markdown?

ePub is basically HTML and CSS.  But no one wants to think about writing HTML and CSS whilst trying to brain dump.

That often leads us to using editors like MS Word.  But then the problem is we start to have too many options and get distracted into adding color to fonts for example.

If you are a technical writer in the software development space you're then you will be using git.  And then because of that possibly GitHub.

In that case the very first file you are expected to create is a Readme.md for your project.

So in that space Markdown is the the go to text formatting convention.

And you can also use it to create content for website generation and more.

So to that end I focus on the use of Markdown for text content formatting and then in turn the challenges of conversion of that with Pandoc.

You can grab the Markdown version of this document / template from the GitHub for this project.  See resources section at the end for the link.

# Pandoc

Pandoc is the tool I use to convert Markdown into eBooks in the form of an ePub that I can then upload to Kindle.


# Conventions

Here are some example conventions for eTextbooks and the use of Markdown.

## Formatting

- Avoid underlining.  That's for hyper links.
- Avoid comments in brackets - it breaks the flow and because we are focusing on Markdown brackets are used to indicate links and images.
- avoid colored text.  It won't show very well on grayscale eInk devices.
- Grayscale diagrams.  Same applies to pictures, figures and diagrams.  Plan for black and white.

## Language

If you are focused on Kindle publishing then you are probably focused on the US market. That means you should be using the English US dictionary as much as that might pain you.

# Testing

How do we test this works?

- convert to a MS Word docx so you can feed into Kindle Create to get an idea of where the formatting issues are that require the use of ePub.
- test in Kindle preview.  You'll have to bug hunt your format if you start this testing with a complex format.  Best to start testing here early!  For example images and CSS issues.
- Convert to ePub with Pandoc
- Send to kindle as an ePub.
- Github it to see how Github converts.
- Read on a range of devices with small and large screen dimensions.
- read on an eInk kindle that is not color.
- Increase and reduce font size
- Test Dark and Light mode on tablets and phones.

# End Matter

This is the sort of content that Kindle Create with the addition of Resources and References headings and Appendix.

## Resources and Links

### Markdown

[https://www.markdownguide.org/getting-started/](https://www.markdownguide.org/getting-started/)

Markdown creator's site:  
[John's Website](https://daringfireball.net/projects/markdown/) 

John's Syntax guide:  
[John's syntax reference](https://daringfireball.net/projects/markdown/syntax)

Extended markdown:  
[Hacks](https://www.markdownguide.org/hacks/ "hacks")

### VS Code

Enhanced Markdown Preview:
[Support website](https://shd101wyy.github.io/markdown-preview-enhanced)

## References



## Appendix A

Cheat sheet as an example:


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

## About the Author

Harry Longworth

Blurb

`<Author Image>`

## Acknowledgement

Without the work of open source creators around the world this work would not have been possible! Thank you.

