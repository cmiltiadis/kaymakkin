---
title: Vault outline 
summary: A map of all content of this vault. 
author: Constantinos
date: 2024-12-14
tags: 
  - MOC
  - workshop
---

# Demo Vault for Kaymakkin Workshop December 2024 

![Kaymakkin|150](XIMG/kaymakkin.jpg)

# Workshop outline 
## Writing 
+ [[Obsidian]] -- free software for note-taking, knowledge organization & [[Zettelkasten]] , using an extended version of Markdown)
+ See also [[Logseq]], a FOSS for [[Bullet journaling|bullet journaling]] & [[Zettelkasten]] using Markdown) 
## Publishing

Document publishing
+ [[Pandoc]] -- FOSS, universal document converter (that fully supports MD)
	+ [[PanWriter]] -- FOSS [[Markdown|MD]] editor that provides a GUI for Pandoc  
Web publishing 
+ [[Hugo]] -- FOSS, static website builder (that uses [[Markdown|MD]] files)
## Library organization   
+ [[Calibre]] -- General purpose e-book management 
	+ [[Accorder]] -- Command line tool for creating portable libraries via [[Calibre]] 
+ [[Zotero]] -- Bibliographic reference management 

# Vault folder structure 
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

# Vault contents 

See [Contents (Hardcoded)](#Contents%20(Hardcoded)), or Vault Contents automated via the *Dataview* plugin (Prefixed DV). The latter only works in Obsidian using the Dataview plugin.[^dataview] 

[^dataview]:  To install the [[Obsidian]] *Dataview* plugin go to Settings/Community Plugins/Browse, and search for Dataview. For documentation and demonstration see: 
- [Dataview](https://blacksmithgu.github.io/obsidian-dataview/)
- [Nicole van der Hoeven - How to use the Obsidian Dataview plugin (YouTube)](https://www.youtube.com/watch?v=JTObSymEvWA)

## DV: Map of Content (MOC) notes  

```dataview
TABLE title as Title, summary
FROM #MOC 
```

## DV: Software apparatus  (/Apparatus)

```dataview 
TABLE tags
FROM "Apparatus"
```

## DV: Additional  (/Additional notes & /Open hardware) 

```dataview 
TABLE without id
	file.link as Title, tags
FROM "Additional notes" or "Open Hardware"
```
## DV: Templates (/XTRAS/TEMPLATES)
```dataview 
Table summary as Summary
FROM "XTRAS/TEMPLATES"
```

## DV: /Recipes ([[Recipe|Recipe tag]])

```dataview 
TABLE title,summary, tags,date FROM "Recipes"
```

--- 


# Contents (Hardcoded)
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
	- [[Guide for academic writing in Markdown]]
	- [[Productivity applications]]
	- [[Libraries]] --a list of online libraries
	- [[Mensajito]] --open hardware for radio streaming
	- [[Zettelkasten]]
	- [[Bullet journaling]]
