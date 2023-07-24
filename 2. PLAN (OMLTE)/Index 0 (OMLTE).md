---
autor: Yan
tipo: index
alias:
tags: 
fecha: 2023-07-23
---



```dataview
TABLE autor, tipo, tags
WHERE contains(file.folder, this.file.folder) 
SORT tipo asc
SORT tags asc
```




