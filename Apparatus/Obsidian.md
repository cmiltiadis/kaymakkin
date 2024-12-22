---
title: Obsidian
tags:
  - free-software
  - Markdown
  - Zettelkasten
  - software
  - cross-platform
  - knowledge-organization
img: obsidian-logo-old.png
---

![obsidian-logo-old](XIMG/logos/obsidian-logo-old.png)
# About 

[Obsidian](https://obsidian.md/) is a free cross-platform software for knowledge organization. 
It uses [Markdown](Markdown.md) files (called Notes), organized in custom folders, within a Vault (a master folder).  
Obsidian provides a user-friendly interface for Markdown formatting. 
Moreover, it uses its own [extended Markdown syntax](#Obsidian-specific%20syntax). 

Obsidian is free to use.
However, it's not open source.
Nevertheless, all content created with Obsidian is stored locally, and is thus safe. 
A paid subscription is only required for syncing vaults with the Obsidian cloud.

Go to: 
- [#Interface](#Interface), 
- [#Obsidian-specific syntax](#Obsidian-specific%20syntax), 
- [#Plugins](#Plugins), 
- [#Note Templates](#Note%20Templates), 
- [#Useful tips](#Useful%20tips)
- [#Useful shortcuts](#Useful%20shortcuts)
- [#Notes](#Notes)

# Interface 

- Top toolbar: Tabs with open notes 
- Bottom right: Document word/character/backlinks counter 

Panes: 
- The left pane
	- Files 
	- Search vault 
	- Bookmarks 
	- Vertical icons: Quick switcher; Graph view; New Canvas; Daily Note; Command palette; (potential plugins)
	- Bottom section 
		- Vault selection 
		- Settings 
		- Help 
- The right Pane
	- Outgoing links 
	- Tags
	- Outline (of document)

# Obsidian-specific syntax 

Obsidian makes use of [Markdown](Markdown.md) files and Markdown syntax, however, it features its own extended syntax, most notably the use of double square brackets used for links.
## Internal Hyperlinks
Create hyperlinks by enclosing the name of a Note inside double square brackets: 
```
[Some note](Some%20note)
```

This will create a hyperlink to "*Some note*", which will appear in the graph, regardless of whether a file named "Something.md" exists. 
This is useful, particularly for making links for notes to be populated later. 
### Hyperlinks to subsections 

Similarly to link to a subsection of a note do: 

```
[](Some%20Note#Subsection%20title)
```

Upon opening two square brackets, for creating a hyperlink, Obsidian will pop up a searchable list of available notes. Similarly, it will pop up a list of available subsections, immediately after pressing the hashtag key.

### Custom hyperlink labels

By default the text of a hyperlink to some Note or Note section, is the same to the filename of the Note or title of section. 

To customize the label of the link, add some custom text after a pipe character: 

```
[Custom label](Some%20note)
```

## Quote content Note

To quote the contents of a Note, or a note subsection, add an exclamation point before an internal hyperlink or hyperlink to a subsection.  

```
![Note to quote](Note%20to%20quote)
![](Notes#Sub%20section%20to%20quote)
```
## Image & file links  

Instead of the  [](Markdown.md#Images|Markdown%20convention%20for%20images), Obsidian uses it's own convention that does not require referencing the full path of an image. 
For example: 
```
![2023_Obsidian_logo.svg](2023_Obsidian_logo.svg)
```
## Comments
In addition to the hyperlink-format comment supported by [Markdown](Markdown.md),  Obsidian uses its own convention for comments: 

```
<!-- This is a Markdown line comment  -->

<!-- 
this is a Markdown 
multiline comment
-->
%% This is an Obsidian-syntax comment %%
```

The shortcut for Obsidian comments is Ctrl/Cmd+/

Both comment styles work in Obsidian -- both comment convention will disappear in View mode (Ctrl/Cmd+E), like the examples below. 
<!-- 
this is a Markdown 
multiline comment
-->
%% This is an Obsidian comment %%

# Note Templates 

These are useful for creating notes Notes according to predefined templates, instead of starting with empty documents. 
To use Templates: 

1. Create a new directory to store your templates, ideally titled Templates (which can be a subdirectory inside, for example, Extras)
2. Make sure Settings/Core Plugins/Templates is enabled. 
3. Go to the Templates plugin settings, and set your Templates directory.
4. Inside your Templates directory create a new note, and name it accordingly (e.g. `Template, general`).
5. Add content to the template, e.g. headings, and frontmatter properties.  

Here is an example template, that will set properties for date (to today's date), title (according to filename), author, description, and tags.   
```
---
title: "{{title}}"
date: "{{date}}"
author: Jane Doe  
description: Placeholder description...
tags: 
  - draft
---
# Introduction 

# Notes 
```
6. Apply a template to a new Note with the Apply Template command (from the Command palette). 

For advanced Template use see the *Templater* community plugin. 

See also [Dann Berg - How to create a template in Obsidian (Beginner's Tutorial) (YouTube)](https://www.youtube.com/watch?v=91H_0ii4S-A)
# Useful tips 

- Without highlighting any text, copy and cut, operates on a whole line of text. 
- Copying and pasting a text from a browser, for example, will carry over formatting including links. 
	- To paste in plain text do Cmd/Ctrl+Shift+V 
- The font, font-size, dark/light appearance of the Obsidian editor can be changed in the settings. 
- All Obsidian commands are accessible via Ctrl/Cmd+P, and can be assigned to custom keyboard shortcuts. 
- Obsidian vaults can be backed up, synchronized, and versioned using [Git](Git.md).  
- Obsidian can also be used as a straight-forward Markdown editor--by ignoring its features. 
- Obsidian can convert and export PDFs (from individual Notes), however, by default it doesn't use the [Markdown](Markdown.md) line and paragraph conventions (see [](Markdown.md#Lines%20&%20Paragraphs)). 
- To insert a table in Obsidian, right click Insert/Table.
- Obsidian also provides a mouse-interface for deleting and adding rows and columns.  
- Alternatively, start creating a table manually, and Obsidian will generate a visually aligned table automatically. For example 
	```
	|Column 1|Column 2|
	|-| 
	```
- Use Tab and Shift-Tab to navigate between table cells.   
# Useful shortcuts 

| Shortcut                   | Description              |
| -------------------------- | ------------------------ |
| Ctrl/Cmd-click (over link) | Go to link destination   |
| Ctrl/Cmd-c                 | copy line (or selection) |
| Ctrl/Cmd-x                 | cut line (or selection)  |
| Ctrl/Cmd-o                 | Find/create note         |
| Ctrl/Cmd-p                 | Command palette search   |
| Ctrl/Cmd-f                 | Search current file      |
| Ctrl/Cmd-Shift-F           | Search vault             |
| Ctrl/Cmd-E                 | Edit/View mode           |
| Ctrl/Cmd-,                 | Settings                 |

# Plugins 
Obsidian features multiple plugins that extend its functionality. These are either:
- Core plugins -- created by the company behind Obsidian, and 
- Community plugins (contributed by the community). 

Browse and install plugins at Setting/Core plugins, and Settings/Community plugins.
Community plugins need to be enabled first. 

For Community Plugins, the *Browse plugins* page shows how many times each plugin has been installed. Selecting a plugin will show a description, installation and use instructions.  

After a Community plugin is installed, it appears at the bottom of the settings list. 
Remember to enable each plugin after installing it. 
## Notable community plugins 
- [Templater](https://github.com/SilentVoid13/Templater) -- a plugin for advanced template configurations. 
- Pandoc -- an interface for [Pandoc](Pandoc.md) 
- Zotero Integration -- an interface for[Zotero](Zotero.md)
- Git -- an interface for [Git](Git.md) versioning
- [Dataview](https://blacksmithgu.github.io/obsidian-dataview/), for dynamically creating lists or tables from Vault content.  
# Notes 
- https://obsidian.md/
## Workflow presentations and demonstrations of Obsidian 
- [No Boilerplate - Hack your brain with Obsidian.md (YouTube)](https://www.youtube.com/watch?v=DbsAQSIKQXk)
- [Odysseas - Obsidian: The King of Learning Tools (FULL GUIDE + SETUP) (YouTube)](https://www.youtube.com/watch?v=hSTy_BInQs8) 
- [Dann Berg - How to create a template in Obsidian (Beginner's Tutorial) (YouTube)](https://www.youtube.com/watch?v=91H_0ii4S-A) 
- [Nicole van der Hoeven - How to use the Obsidian Dataview plugin (YouTube)](https://www.youtube.com/watch?v=JTObSymEvWA)
