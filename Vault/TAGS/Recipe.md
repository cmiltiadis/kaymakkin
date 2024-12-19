---
title: Recipe
summary: Map of Content (MOC) and TAG-note for Recipes 
tags: 
  - tag
  - MOC
---

This is an example of a '*hardcoded*' tag. 
Instead of setting tags through frontmatter properties, another way of grouping content is by using internal links to notes reserved as Tags.  
In this case, this note is inside the folder `TAGS`. 

See also [Odysseas - Obsidian: The King of Learning Tools (FULL GUIDE + SETUP) (YouTube)](https://www.youtube.com/watch?v=hSTy_BInQs8) 

--- 


# Condiments 
```dataview 
Table title as Title, tags, date as "Created on" 
FROM "Recipes" AND #condiment
```

# Not condiments 
```dataview 
Table title as Title, tags, date as "Created on" 
FROM "Recipes" AND !#condiment
```

# Test 

```dataview 
table without id 
	file.link as Title,
    "**Summary**:" + summary as Summary

FROM "Recipes"
```