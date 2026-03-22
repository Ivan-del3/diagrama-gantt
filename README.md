# DIAGRAMA DE GANTT

Un **diagrama de Gantt simple, ligero y editable en el navegador**, construido únicamente con **HTML, CSS y JavaScript puro**.

Este proyecto está pensado como una herramienta mínima para **planificar tareas en el tiempo** sin dependencias externas.


🌐 Demo (GitHub Pages):  
https://ivan-del3.github.io/diagrama-gantt/

Repositorio:  
https://github.com/Ivan-del3/diagrama-gantt



---

# Características

- Edición directa en el navegador
- Sin dependencias externas
- Código muy simple (ideal para aprender o modificar)
- Descarga del proyecto completo desde la propia página
- Interfaz clara y ligera
- Selección visual de filas y columnas activas

### Funcionalidades

Crear tareas (filas)  
Eliminar tareas activas  
Crear bloques de tiempo (columnas)  
Eliminar columnas activas  
Activar fila o columna con un click  
Marcar bloques de tiempo en el Gantt  
Descargar el documento completo como HTML

---

# Cómo funciona

Cada celda del diagrama representa si una **tarea ocupa un bloque de tiempo**.

- Al **hacer click en una celda**, se crea o elimina un bloque.
- Al **hacer click en el encabezado**, se activa una columna.
- Al **hacer click en el nombre de una tarea**, se activa la fila.

Las operaciones de borrado actúan sobre el elemento activo.

Ejemplo:

```

Click en "Semana 3" → columna activa
Click en "- Semana" → elimina esa columna

```

---

# Uso

Simplemente abre el archivo:

```

index.html

```

en cualquier navegador moderno.

No requiere instalación ni servidor.

---

# Descargar el documento

El botón **"Descargar HTML"** genera un archivo que contiene:

- HTML
- CSS
- JavaScript

Todo en un único documento listo para guardarse o compartirse.


---

# Posibles mejoras futuras

Algunas ideas que podrían añadirse:

- exportar a JSON
- exportar a imagen
- drag para extender tareas
- dependencias entre tareas
- zoom temporal (días / semanas / meses)



---

# Licencia

 GNU GENERAL PUBLIC LICENSE

Puedes usar, modificar y reutilizar este proyecto libremente.

---

