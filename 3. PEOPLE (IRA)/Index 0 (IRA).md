---
autor: Yan
tipo: index
alias:
tags: 
fecha: 2023-07-24
---
```dataview
TABLE autor, tags
WHERE contains(file.folder, this.file.folder) AND tipo = persona
```
