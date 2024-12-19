---
title: Vault outline 
summary: A map of all content of this vault 
tags: 
  - MOC
---

See [[#Contents (Hardcoded)]] below. 

# Obsidian Vault Contents automated via the *Dataview* plugin[^dataview]

[^dataview]:  To install the [[Obsidian]] *Dataview* plugin go to Settings/Community Plugins/Browse, and search for Dataview. For documentation and demonstration see: 
- [Dataview](https://blacksmithgu.github.io/obsidian-dataview/)
- [Nicole van der Hoeven - How to use the Obsidian Dataview plugin (YouTube)](https://www.youtube.com/watch?v=JTObSymEvWA)

## Map of Content (MOC) notes 

```dataview
TABLE title as Title, summary
FROM #MOC 
```

## Software apparatus  (/Apparatus)
Code block: 
``` 
[add the term dataview next to triple ticks above]
TABLE tags
FROM "Apparatus"
```

Rendered: 

```dataview 
TABLE tags
FROM "Apparatus"
```

## From /Additional notes 

```dataview 
TABLE without id
	file.link as Title, tags
FROM "Additional notes"
```
## Templates (/XTRAS/TEMPLATES)
```dataview 
Table summary as Summary
FROM "XTRAS/TEMPLATES"
```

## From /Recipes ([[Recipe|Recipe tag]])

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
