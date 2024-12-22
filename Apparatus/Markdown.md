---
title: "Markdown"
tags:
  - FOSS
  - open-standard
  - free
  - Markdown
---
![](XIMG/logos/Markdown-mark.svg)
# About 
Markdown (MD) is a open simple markup language for human-friendly writing. 
It was developed around 2004, and has grown very popular ever since. 
Markdown is used for a variety of applications, such as note-taking; technical documentation (e.g. GitHub, and Wikis), journaling, as well as [Zettelkasten](Zettelkasten.md) and [Bullet journaling](Bullet%20journaling.md) workflows. 
## Why write in Markdown 
1. It's a free and open standard 
3. It's a **plain-text document format** 
   You don't need a special software to create, open, or view such documents. 
	1. As follows, you don't need to pay for any software to create, open, or view MD files. 
1. You can chose from a variety of free and lightweight MD editors (software). 
	3. You have a *fully customizable user interface*.... (no more Word white background)
3. **Distraction free writing**  
4. Adaptable for different purposes and workflows such as academic writing, [Zettelkasten](Zettelkasten.md) and [Bullet journaling](Bullet%20journaling.md). 

The following provides some instructions about
- [#Writing in Markdown](#Writing%20in%20Markdown), 
- [#Publishing Markdown documents](#Publishing%20Markdown%20documents)

# Writing in Markdown 

The great thing about writing in Markdown is that it's made for humans--not for printers, not for paper, or anything, but humans. 

## Lines & Paragraphs

So to write a paragraph, just start writing. 
Each sentence can be a new line.
This makes it easier to track your text. 

To start a new paragraph just leave a new line. 
## Text formatting 

Markdown supports *italics*, **bold**, and ***bold italics***. 
These are formatted by enclosing text within single, double, or triple asterisks.  

Italics:  *some text inside asterisks*   
Bold: **some text inside double asterisks**
Bold-italics: ***some text inside triple asterisks***

How this looks in reality: 
```
Italics:  *some text inside asterisks*   
Bold: **some text inside double asterisks**
Bold-italics: ***some text inside triple asterisks***
```

## Additional MD syntax 

### Math 

Enclose math syntax within dollar signs: 

```
$x^2$
```

$x^2$ 


### Escape character 

Use a backslash (`\`) to prevent rendering any Markdown specific characters, for example \#  (which is used for headings). 

```
\# 
```

### Horizontal line 
Use 3 dashes to make a horizontal line. 
Note: leave an empty line before, otherwise the previous line will be rendered as a heading. 


```
---
```

---

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

example 
```
- some item 
- some other item
	- sub item 
```

### Checklists  

This is a checklist, for, let's say my tasks: 
1. [ ] Some task 
2. [ ] Some other task
3. [X] Learn  to write in Markdown

```
1. [ ] Some task 
2. [ ] Some other task
3. [X] Learn  to write in Markdown
```


## Tables 
| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | item 2   |
| item 3   | etc.     |

Formatting Markdown tables 
```
| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | item 2   |
| item 3   | etc.     |
```
Note that columns need not be visually aligned. For example, the following table is equivalent to the previous, albeit more difficult to read. 

```
| Column 1 |Column 2 |
| - | ---- |
| Item 1| item 2 |
| item 3| etc. |
```

### Table column alignment 

| Left aligned | Center aligned | Right Aligned |
| :----------- | :------------: | ------------: |
| 1            |       2        |             3 |
| 4            |       5        |             6 |

```
| Left aligned | Center aligned | Right Aligned |
| :----------- | :------------: | ------------: |
| 1            |       2        |             3 |
| 4            |       5        |             6 |

```

Markdown editors such as [Obsidian](Obsidian.md) provide autoformatting for tables (see [](Obsidian.md#Useful%20tips)). 
## Source code blocks 

Enclose code in backticks \` 
This will also ignore MD formatting. 
Example: 
`this is a single-line code block, all MD formatting is ignored like # ![]() etc.`

Multiline code blocks are enclosed in triple backticks 
```
this is 
a multiline 
code 
block 
```
## Block quotes 

To insert a blockquote prefix some text with `> My quote text`. 
For example: 

> This is a blockquote (which is supposed to be quote longer than 30 words or something like this), and usually is followed by a reference. (Author 2024)

In plain text this looks like: 

```
> This is a blockquote (which is supposed to be quote longer than 30 words or something like this), and usually is followed by a reference. (Author 2024)
```

# Links 

[Kaymakkin Workshop Github repository](https://github.com/cmiltiadis/kaymakkin)
```
[Kaymakkin Workshop Github repository](https://github.com/cmiltiadis/kaymakkin)
```

# Images 

![Description](XIMG/logos/Markdown-mark.svg)

```
![Description](images/markdown-mark.svg)
```

# Comments 

Markdown uses the HTML convention for notes. 

Example 
```
<!-- this is a comment; it will not be exported -->

<!-- 
comments can 
also be 
multi-line
-->
```


<!-- this is a comment; it will not be exported -->

<!-- 
comments can 
also be 
multi-line
-->

# Publishing Markdown documents 

Markdown is fully supported by [Pandoc](Pandoc.md),  the universal document converter. 
#  Notes 
- [Markdown guide](https://www.markdownguide.org/)
- [Markdown (wikipedia)](https://en.wikipedia.org/wiki/Markdown)
