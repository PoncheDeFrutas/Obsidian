# Cursos Activos
```dataview
table estado, plataforma, creado
from "02_Cursos"
where type = "curso" and estado = "en-progreso"
sort creado desc
```

# Cursos Pausados 
```dataview
table estado, plataforma
from "02_Cursos"
where type = "curso" and estado = "pausado"
sort creado desc
```

# Cursos Completados
```dataview
table plataforma, creado
from "02_Cursos"
where type = "curso" and estado = "completado"
sort creado desc
```