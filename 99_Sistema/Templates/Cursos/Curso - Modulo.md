---
type: modulo
curso: <% tp.file.folder(true).split("/").slice(-2, -1)[0] %>
fecha: <% tp.date.now("YYYY-MM-DD") %>
estado: en-progreso
orden:
tags: [modulo]
---
# <% tp.file.title %>
Curso: [[<% tp.file.folder(true).split("/").slice(-2, -1)[0] %>]]

## Objetivo del módulo
 > ¿Qué vas a poder hacer / entender al terminar este módulo?

---
## Lecciones
```dataview

list

from ""

where type = "leccion" and contains(file.folder, this.file.folder)

sort file.name asc

```
---
 
## Estado
- **Estado actual:** en-progreso
- **Última revisión:** <% tp.date.now("YYYY-MM-DD") %>
---
## Conceptos clave a extraer
> Conocimiento que debe vivir luego en `01_Cuadernos`
- [[ ]]
- [[ ]]

---
## Aplicación práctica
- Proyecto relacionado → [[ ]]
- Casos de uso reales:
  -
---
## Notas generales