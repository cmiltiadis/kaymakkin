---
tags:
  - FOSS
  - open-standard
---
![](images/markdown-mark.svg)
# About 
Markdown (MD) is a open simple markup language for human-friendly writing. 
It was developed around 2004, and has grown very popular ever since. 
Markdown is used for a variety of applications, such as note-taking; technical documentation (e.g. GitHub, and Wikis), journaling, as well as [[Zettelkasten]] and [[Bullet Journaling]] workflows. 
## Why write in Markdown 
1. It's a free and open standard 
3. It's a **plain-text document format** 
   You don't need a special software to create, open, or view such documents. 
	1. As follows, you don't need to pay for any software to create, open, or view MD files. 
1. You can chose from a variety of free and lightweight MD editors (software). 
	3. You have a *fully customizable user interface*.... (no more Word white background)
3. **Distraction free writing**  
2. You can use it for a variety of workflows such as [[Zettelkasten]] and [[Bullet Journaling]]. 
4. Adaptable for different purposes, also academic writing. 


The following provides some instructions about
- [[#Writing in Markdown]], 
- [[#Publishing Markdown documents]]

# Publishing Markdown documents 

Markdown is fully supported by [[Pandoc]],  the universal document converter. 

# Writing in Markdown 

The great thing about writing in Markdown is that it's make for humans. 
Not for printers, not for paper, or anything, but humans. 

So to write a paragraph, just start writing. 
Each sentence can be a new line.
This makes it easier to track your text. 

To start a new paragraph just leave a new line. 
## Text formatting 

Markdown supports *italics*, **bold**, and ***bold italics***. 

Italics:  *some text inside asterisks*   
Bold: **some text inside double asterisks**
Bold-italics: ***some text inside triple asterisks***

How this looks in reality: 
```
Italics:  *some text inside asterisks*   
Bold: **some text inside double asterisks**
Bold-italics: ***some text inside triple asterisks***
```

## Lists 

### Ordered lists 
This is an ordered/numbered list: 
1. Type `1. Something` to start a list. 
2. Press to create a new item)
	1. Tab for indented sub-item 
4. Shift-Tab to  outdent 
5. Double enter to exit list 


A simple ordered list looks like this 
```
1. one 
2. two 
	1. two-one

```
### Unordered lists 
This is an unordered list: 
- Type `- Something` to start a list
- Enter to create a new item 
	- Tab to indent 
- Shift-tab to outdent 
- Double enter to exit 
### Checklists  

This is a checklist, for, let's say my tasks: 
1. [ ] Some task 
3. [ ] Some other task
4. [ ] Learn [[#Writing in markdown]]
## Tables 

To insert a table in Obsidian, just right-click Insert/Table. 
Alternatively, do 

```
|1|2|
|-| 
```


Use Tab and Shift-tab to navigate between cells.  

| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | item 2   |
| item 3   | etc.     |

This looks like this 
```
| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | item 2   |
| item 3   | etc.     |

```

## Source code & verbatim 

Use backticks for code 

 
# Block quotes 

To insert a blockquote prefix some text with `> `. 
For example: 

> This is a blockquote (which is supposed to be quote longer than 30 words or something like this), and usually is followed by a reference. (Author 2024)

In plain text this looks like: 

```
> This is a blockquote (which is supposed to be quote longer than 30 words or something like this), and usually is followed by a reference. (Author 2024)
```


#  Notes 
- [Markdown guide](https://www.markdownguide.org/)
- [Markdown (wikipedia)](https://en.wikipedia.org/wiki/Markdown)