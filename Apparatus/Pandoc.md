---
title: "Pandoc"
tags:
  - FOSS
  - command-line-tool
  - document-converter
  - software
  - bibliographic-referencing
---

# About 

[Pandoc](https://pandoc.org/) is a *free and open source software* (FOSS), universal document converter. 
In addition to converting documents, Pandoc can also render bibliographic citations. 

![Pandoc|250](XIMG/logos/pandoc.png)
# Usage 
 
1. Install Pandoc via the installer.  
2. Open a terminal 
3. Optionally, navigate to the directory of your document
4. Type a conversion command 

Basic Pandoc command to export to DOCX.  
```
pandoc -i mydocument.md -o mydocument.docx 
```

# Pandoc for academic documents 

See [Markdown-Article-Guide](Articles/Markdown-Article-Guide.md). 

# Notes 
- [Pandoc website](https://pandoc.org/)
- See also the Pandoc [citeproc](https://github.com/jgm/citeproc) library, responsible for generating citations and formatting bibliographies for Pandoc. 
- See also the MD editor [PanWriter](PanWriter.md), which provides a GUI for Pandoc. 