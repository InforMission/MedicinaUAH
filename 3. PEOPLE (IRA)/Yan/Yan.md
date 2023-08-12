---
autor: Yan
tipo: persona
alias:
tags: 4
fecha: 2023-07-24
---


# Information
- - -
- UAH student 4º
- Caballero Alférez Cadete 1º CIA ACD Medicina Sin Titulación
- IX Promoción
![[IMG_20230628_132715_531.jpg|200]]

# Rol
- - -

```dataview
LIST
WHERE contains(file.folder, this.file.folder)
```

# Availability
- - -
## Doing 
```dataview
TASK
WHERE contains(text, this.file.name) AND !completed
```
## Done
```dataview
TASK
WHERE contains(text, this.file.name) AND completed
```