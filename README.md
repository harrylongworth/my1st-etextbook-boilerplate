# my1st-etextbook-boilerplate

My1st eTextbook Boilerplate in 2025 by Harry Longworth - Ebook Textbook Template, Boilerplate and Example Document Structuring using Pandoc and Github for Kindle Self Publishing

The actual book can be found in the repo here:

[Book](./book.md)

The master copy of this guide is a Markdown file.

Test conversions can be found in the dist folder.

[Dist for Distribution](dist/)

These conversions have been created using Pandoc:  <https://pandoc.org/>

Example conversions:

- MS Word .docx.
- ePub.
- Kindle .kcb.
- HTML.
- more soon.

---
## Build Process

Details below on Pandoc commands used to build output files from the master template file for extension.

**Markdown with Numbered TOC**

- If not using MS Word, Google Docs or VS Code Extension and need layered and numbered section navigation then do a conversion from Markdown to Markdown to generate the desired TOC

'insert here'

**ePub**
- for direct upload to KDP
- test with Kindle Preview first
- MOTE: that test currently fails

'insert here'

**docx**
- for either MS Word or Google Docs workflows as the basis of Kindle Create workflow.

'insert here'

---
## Test Process

- A seperate repo has been created and developed to resolve the Kindle Preview test failure as the test process requires rebuilding the format to see start from a working test document with minimal content.

[Kindle Preview test](https://github.com/harrylongworth/md-epub-kindle-test.git)

---
## Template Use

I use this template for eBook creation by cloning this repo.

If the book is just draft and not ready for sharing or will not be intended for sharing I make the repo a private repo.

I then:

1. Create a new git repo so my book always has an offsite backup!
1. Copy the template contents into that folder.
1. Delete the contents of the **dist** folder as those documents are not for this book.
1. Update the readme.md (not replace it!) as it has the build process guide and commands.
1. Update the metadata in either the book or the .yaml file depending on build process.
1. I remove the content section of the template.
1. Update the front and back matter as appropriate.
1. Replace images in the media folder
1. replace cover.png
1. test build to either epub, docx, LaTex or pdf depeding on intended usage.