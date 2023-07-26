---
autor:
tipo: index
alias:
tags: 
fecha: 2023-07-25
---

```dataview
TABLE autor, tags
WHERE contains(file.folder, this.file.folder) AND tipo = "index"
```
