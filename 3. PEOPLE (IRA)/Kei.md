---
autor:
lugar:
alias:
categoria: persona
fecha: {{date}}
---

## Information
- - -
Developer 
Ingeniería Informática UCM

## Rol
- - -
CTO

### Availability
```dataview
LIST
FROM #OMLTE or #ABCDE
WHERE filter(file.tasks, (t) => !t.completed) AND contains(file, this.file.name)
```

