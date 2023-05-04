---
layout: default
title: File signatures
nav_order: 2
parent: Content Carving
has_children: false
---

# File signatures

|File Extension|File Description|HEX signature|Offset|File Trailer|
|-|-|-|-|-|
|JPEG|Generic JPEG image file|`FF D8 FF`||`FF D9`|
|GIF87a|Graphics interchange format file |`47 49 46 38 37 61`||`00 3B`|
|GIF89a|Graphics interchange format file | `47 49 46 38 39 61`||`00 3B`|
|BMP|Microsoft bitmap image| `42 4D`|||
|PNG|Portable Network Graphics file|`89 50 4E 47 0D 0A 1A 0A`|||
|PST|Personal Storage Table, Microsoft Outlook|`21 42 44 4E`|||
|DOCX|Microsoft Office Word Document|`50 4B 03 04 14 00 06 00`||`50 4B 05 06`|
|PPTX|Microsoft Office PowerPoint Document|`50 4B 03 04 14 00 06 00`|| `50 4B 05 06`|
|XLSX|Microsoft Office Excel Document|`50 4B 03 04 14 00 06 00`||`50 4B 05 06`|
|PDF|Adobe Portable Document Format|`25 50 44 46`||`0A 25 25 45 4F 46`|
|ZIP|Archive file|`50 4B 03 04`|||
|RTF|Rich text format|`7B 5C 72 74 66`||`7D`|
