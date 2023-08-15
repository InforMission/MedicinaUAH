---
autor: Yan
tipo: index
alias:
tags: 4, PME, DIG
fecha: 2023-08-15
---

```dataview
LIST
WHERE contains(file.folder, this.file.folder)
SORT file.name asc
```
