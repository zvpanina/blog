---
title: Markdown
summary: Markdown language and its use 
date: 2025-02-27

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
  
authors:
  - admin
tags:
  - Academic
---

{{< toc mobile_only=true is_open=true >}}

## Markup language
In the IT sphere, a markup language is a certain set of symbols and their sequences, embedded in the text in order to convey information about the structure of this document and its final form. As a result, the text document looks like a text with all punctuation marks, supplemented by code with information about the structure of this text.
Markdown is a lightweight markup language that converts text into structured HTML. It can be opened and edited in any text editor. It is widely used for writing documentation and README files.

[//]: # ([![The template is mobile first with a responsive design to ensure that your site looks stunning on every device.]&#40;https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/starters/academic/preview.png&#41;]&#40;https://hugoblox.com&#41;)

## Basic Markdown Commands

To create a heading, use the ( # ) sign.
To make text bold, enclose it in double asterisks.
To make text italic, enclose it in single asterisks.
To make text bold and italic, enclose it in triple asterisks.
Blockquotes are created using the > symbol.
An unordered (bulleted) list can be formatted using asterisks or dashes.
To nest one list within another, indent the child list items.
An ordered list can be formatted using the appropriate numbers.
To nest one list within another, indent the child list items.
The Markdown syntax for an inline link consists of a [link text] part, which is the hyperlink text, and a (file-name.md) part, which is the URL or file name of the file being linked to.
Markdown supports both embedding code fragments in a sentence and placing them between sentences as separate fenced blocks. Fenced code blocks are an easy way to highlight the syntax for code fragments.
Inline formulas are made similar to LaTeX formulas.
We will use Pandoc to process files in Markdown format. Specifically, we will need the pandoc program,
pandoc-citeproc https://github.com/jgm/pandoc/releases, pandoc-crossref
https://github.com/lierdakil/pandoc-crossref/releases.
You can transform the README.md file as follows:
1 pandoc README.md -o README.pdf
or like this
1 pandoc README.md -o README.docx
You can use the following Makefile
1 FILES = $(patsubst %.md, %.docx, $(wildcard *.md))
2 FILES += $(patsubst %.md, %.pdf, $(wildcard *.md))

## Summary

The Markdown markup language is widely used on the web. It is used to write readme files and documentation, and its operating principles are used to format messages and publications in instant messengers and social networks.
Markdown is easily converted to HTML, opens in all text editors and is easy to read even in the form of source code. At the same time, it is much easier to write in it than in other markup languages: HTML, XML, TeX, and so on.
---










