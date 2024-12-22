---
title: Readme & Vault outline 
author: Constantinos 
date: 2024-12-12
description: Resources on FOSS tools, put together for a workshop at Social Space Kaymakkin, Nicosia, in December 2024, assembled as an Obsidian vault. 
tags: 
  - MOC
  - workshop
---

# Description 
This repository is a resource on free and open source software (FOSS) and workflows, put together for a set of workshops organized at Social Space Kaymakkin, in Nicosia, in December 2024 (Sunday 15.12.2024; and Saturday 21.12.2024).  

The repository was put together as an [Obsidian](Apparatus/Obsidian.md) vault, and contains multiple [Markdown](Apparatus/Markdown.md) with extensive information on components of the workshop. 

![Kaymakkin|150](XIMG/logos/kaymakkin.jpg)

# Outline 
- [Workshop software & links](#Workshop%20software%20&%20links)
- [Workshop structure](#Workshop%20structure)
- [Vault folder structure](#Vault%20folder%20structure)
- [Vault contents](#Vault%20contents)
- See also the [Guide for academic writing in Markdown](My%20Articles/Guide%20for%20academic%20writing%20in%20Markdown.md)
# Workshop software & links 

| name      | Vault entry                         | URL                            | Description                                                                             |
| --------- | ----------------------------------- | ------------------------------ | --------------------------------------------------------------------------------------- |
| Markdown  | [Markdown](Apparatus/Markdown.md)   | https://www.markdownguide.org/ | lightweight markup language                                                             |
| Calibre   | [Calibre](Apparatus/Calibre.md)     | https://calibre-ebook.com/<br> | e-book management                                                                       |
| Zotero    | [Zotero](Apparatus/Zotero.md)       | https://www.zotero.org/        | bibliography management                                                                 |
| Pandoc    | [Pandoc](Apparatus/Pandoc.md)       | https://pandoc.org/            | document converter                                                                      |
| PanWriter | [PanWriter](Apparatus/PanWriter.md) | https://panwriter.com/         | [Markdown](Apparatus/Markdown.md) editor with [Pandoc](Apparatus/Pandoc.md) integration |
| Obsidian  | [Obsidian](Apparatus/Obsidian.md)   | https://obsidian.md/           | (Free) [Markdown](Apparatus/Markdown.md) editor for knowledge organization              |
| Hugo      | [Hugo](Apparatus/Hugo.md)           | https://gohugo.io/             | Static website builder                                                                  |

# Vault folder structure 

Content 
- Apparatus 
- Additional notes 
- Open Hardware 
- My Articles 

Additional directories  
- XTRAS
	- BIB (for bib files)
	- CSL (for citation style files)
	- TEMPLATES (for Obsidian Note templates)
- XPORTS (for documents exported via Pandoc)
- XIMG (for images)
- WIP 
  For work-in-progress notes
- TAGS 
  For Notes that serve as MOCs

# Workshop structure 

Writing 
+ [[Obsidian]] -- free software for note-taking, knowledge organization & [[Zettelkasten]] , using an extended version of Markdown)
+ See also [[Logseq]], a FOSS for [[Bullet journaling|bullet journaling]] & [[Zettelkasten]] using Markdown) 

Document publishing
+ [[Pandoc]] -- FOSS, universal document converter (that fully supports MD)
	+ [[PanWriter]] -- FOSS [[Markdown|MD]] editor that provides a GUI for Pandoc  

Web publishing 
+ [[Hugo]] -- FOSS, static website builder (that uses [[Markdown|MD]] files)

Library organization   
+ [[Calibre]] -- General purpose e-book management 
	+ [[Accorder]] -- Command line tool for creating portable libraries via [[Calibre]] 
+ [[Zotero]] -- Bibliographic reference management. 

# Vault contents 

See
- [Contents (Hardcoded)](#Contents%20(Hardcoded)), or 
- [Vault contents via Obsidian Dataview](#Vault%20contents%20via%20Obsidian%20Dataview) (which requires opening this vault in Obsidian with the Dataview plugin installed[^dataview]). 

[^dataview]:  To install the [[Obsidian]] *Dataview* plugin go to Settings/Community Plugins/Browse, and search for Dataview. For documentation and demonstration see: 
- [Dataview](https://blacksmithgu.github.io/obsidian-dataview/)
- [Nicole van der Hoeven - How to use the Obsidian Dataview plugin (YouTube)](https://www.youtube.com/watch?v=JTObSymEvWA)

## Contents (Hardcoded)
- [[Recipe|Recipes]]
- Software & tool apparatus:  
	- [[Markdown]]
	- [[Obsidian]]
	- [[Calibre]]
		- See also [[Accorder]]
	- [[Zotero]]
	- [[Pandoc]]
		- [[PanWriter]] --FOSS Markdown editor and GUI interface for Pandoc. 
	- [[Git]] --versioning system
	- [[Hugo]] --static website builder that uses [[Markdown|MD]] files 
- Additional tools & Notes 
	- [[My Articles/Guide for academic writing in Markdown]]
	- [[Productivity applications]]
	- [[Libraries]] --a list of online libraries
	- [[Mensajito]] --open hardware for radio streaming
	- [[Zettelkasten]]
	- [[Bullet journaling]]


## Vault contents via Obsidian Dataview 
### DV: Map of Content (MOC) notes  

```dataview
TABLE title as Title, summary
FROM #MOC 
```

## DV: Software apparatus  (/Apparatus)

```dataview 
TABLE tags
FROM "Apparatus"
```

### DV: Additional  (/Additional notes & /Open hardware) 

```dataview 
TABLE without id
	file.link as Title, tags
FROM "Additional notes" or "Open Hardware"
```
### DV: Templates (/XTRAS/TEMPLATES)
```dataview 
Table summary as Summary
FROM "XTRAS/TEMPLATES"
```

### DV: /Recipes ([[Recipe|Recipe tag]])

```dataview 
TABLE title,summary, tags,date FROM "Recipes"
```

--- 

