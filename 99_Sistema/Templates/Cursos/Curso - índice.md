---
type: curso  
estado: en-progreso # en-progreso | pausado | completado  
creado: <% tp.date.now("YYYY-MM-DD") %>  
plataforma:  
area:  
nivel:  
tags: [curso]
---
#  <% tp.file.folder(true).split("/").pop() %>
Curso: [[<% tp.file.folder(true).split("/").pop() %>]]

##  Objetivo del curso

> ¿Para qué sirve este curso en tu vida real?

---

##  Módulos / Lecciones

```dataview
list
from ""
where type = "leccion" and contains(file.folder, this.file.folder)
sort file.name asc
```

---

##  Estado

- **Estado actual:** en-progreso
- **Última revisión:** <% tp.date.now("YYYY-MM-DD") %>

---

##  Conceptos clave a extraer

> Conocimiento que debe vivir luego en `01_Cuadernos`

- [[ ]]
    
- [[ ]]
    

---

## Relación con otros temas

- Área principal → [[ ]]
    
- Conecta con → [[ ]]
    

---

## Aplicación práctica

- Proyecto relacionado → [[ ]]
- ## Casos de uso reales:

---

## Notas generales