---
title: Calibre
tags:
  - FOSS
  - software
  - library-management
  - cross-platform
---
![](Calibre_logo.png)

# About
[Calibre](https://calibre-ebook.com/) is a *free & open source software* (FOSS) for e-book management & library organization. 
Calibre also allows 
- editing e-books, 
- converting e-books from one type to another, 
- synchronizing e-books with mobile devices (see Calibre Sync for iOS and Android). 
## Supported formats 

> _Input Formats:_ AZW, AZW3, AZW4, CBZ, CBR, CB7, CBC, CHM, DJVU, DOCX, EPUB, FB2, FBZ, HTML, HTMLZ, LIT, LRF, MOBI, ODT, PDF, PRC, PDB, PML, RB, RTF, SNB, TCR, TXT, TXTZ
> 
>_Output Formats:_ AZW3, EPUB, DOCX, FB2, HTMLZ, OEB, LIT, LRF, MOBI, PDB, PMLZ, RB, PDF, RTF, SNB, TCR, TXT, TXTZ, ZIP[^formats]

[^formats]: https://manual.calibre-ebook.com/faq.html
# Basic use 
2. To **add e-books** simply drag and drop your e-books (PDFs, epub, mobi, etc. see [[#Supported formats]])
3. To **add/edit metadata** per item, select a file, and go to *Edit Metadata* (or press E). There multiple ways to add metadata. 
	2. Manually: fill in the details manually.  
	3. go to IDs and add for example `isbn:123-1456-1235-25` and select *Download Metadata* (ore press D), or 
4. **Add book cover** 
	1. Download automatically with *Download Metadata*,
	2. Browse, to select local image file, or 
	3. Generate automatically from title and author 


*Edit metadata* dialog

1. Enter ISBN number in the IDs field in the form `isbn:123-4567-8910` 
   ![img1](calibre-metadata.png)

2. Press D or click Download Metadata (Zotero will try to get the bibliographic data of this item based on the provided ISBN) 
3. Select from possibly multiple matches that could potentially provide a cover image, and a text description, and select OK. 
   ![img2](calibre-metadata-download.png)
3. In the next dialog, select from available book cover images
   ![img3](calibre-metadata-cover.png)
4. Finally, review the item's metadata, and click OK to save 
   ![img4](calibre-metadata-review.png)
