# Champion Academy · App de rutinas

## Archivos
- `index.html` — la app que ven los clientes.
- `rutina.json` — rutina que se muestra cuando el enlace no trae `?u=` (hoy: Alfredo Castillo).
- `rutinas/` — una rutina por persona, por ejemplo `rutinas/alfredo-castillo.json`. Se abre con `?u=alfredo-castillo`.
- `catalogo.json` — videos y texto de técnica por ejercicio (se busca por el nombre del ejercicio).
- `frases/` — imágenes de frases para el resumen. Rosa y morado para mujeres; dorado y plata para hombres.
- `admin.html` — solo para ti: convierte el Excel de un cliente en su archivo `.json`. No lo compartas con clientes.

## Agregar o actualizar a un cliente
1. Abre `admin.html` y descarga la plantilla de Excel.
2. Llena la hoja Cliente (incluye Género: Mujer u Hombre) y la hoja Rutina.
3. Súbela en el paso 2 de `admin.html`, revisa el resumen y descarga el `.json`.
4. Sube el `.json` a la carpeta `rutinas/` de GitHub. El enlace es `https://TU-USUARIO.github.io/TU-REPO/?u=nombre`.

## Agregar técnica de un ejercicio
Edita `catalogo.json` y copia un bloque: nombre exacto del ejercicio, enlace de YouTube (o GIF, foto o mp4 subido al repositorio) y un texto corto.
También puedes poner el enlace en la columna Media del Excel; tiene prioridad sobre el catálogo.

## Agregar frases de otro color (azul, verde…)
Sube los archivos a `frases/` con el mismo formato de nombre (`Frase-X1.webp`) y pide que se agregue el código de color a la app.
