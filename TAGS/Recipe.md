---
title: Recipe
summary: Map of Content (MOC) and TAG-note for Recipes 
tags: 
  - tag
  - MOC
---

This is an example of a *hardcoded tag*. 
Instead of setting tags via frontmatter properties, another way of grouping content in [Obsidian](Apparatus/Obsidian.md) is by using internal links to notes reserved as Tags.  

Initially these can be empty links. 
Eventually, we can populate such notes and use them as MOCs (map of content) to organize related entries. 
In this instance I created this tag-note is inside a folder named `TAGS`, to organize such tag-notes.
- For a discussion of this workflow see [Odysseas - Obsidian: The King of Learning Tools (FULL GUIDE + SETUP) (YouTube)](https://www.youtube.com/watch?v=hSTy_BInQs8) 

# Hardcoded MOC 

Main courses 
- [Pizza](Recipes/Pizza.md)
Condiments 
- [Ramen eggs](Recipes/Ramen%20eggs.md)
- [Tahini dip](Recipes/Tahini%20dip.md)
# MOC generated via the [Dataview](Additional/Dataview.md) plugin
Another way to generate dynamic MOC in [Obsidian](Apparatus/Obsidian.md) is via the [Dataview](Additional/Dataview.md) plugin, like below.   
## Condiments 
```dataview 
Table title as Title, tags, date as "Created on" 
FROM "Recipes" AND #condiment
```

## Not condiments 
```dataview 
Table title as Title, tags, date as "Created on" 
FROM "Recipes" AND !#condiment
```

# All 

```dataview 
table without id 
	file.link as Title,
    "**Summary**: " + summary as Summary

FROM "Recipes"
```