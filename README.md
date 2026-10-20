# 📖 Progresivo — Ejercicio: la misma página con y sin CSS

Proyecto de **aprendizaje** que muestra **la misma página web en dos etapas** para entender qué aporta el CSS:

- **Pagina1.html** — la página **sin ningún CSS**: el HTML crudo, tal como lo dibuja el navegador con sus valores por defecto (texto negro sobre blanco, todo apilado en una columna, enlaces azules subrayados). Se ve "cruda"... pero tiene toda la estructura.
- **Pagina2.html** — **exactamente el mismo HTML**, con el mismo `<body>` byte a byte. La única diferencia con la Página 1 es **una sola línea** en el `<head>`: `<link rel="stylesheet" href="estilos.css">`. Gracias a esa línea, la página se ve diseñada: cabecera oscura, menú en fila, secciones con aire y separación, y pie de página.

> 💡 **La enseñanza del ejercicio:** el HTML es el **contenido y la estructura**; el CSS es el **diseño**. Las dos páginas comparten el mismo cuerpo y aun así se ven completamente distinto. Comparalas una al lado de la otra.

> ⚠️ Es material de estudio, no un producto terminado.

## Características

- **Estructura semántica compartida** por las dos páginas: `header` con un `h1`, `nav` con una lista de 3 enlaces (Inicio, Servicios, Contacto), `main` con 3 `section` (Destinos, Paquetes y Consejos) y `footer` con el copyright. Es la maqueta de un supuesto sitio de viajes.
- **estilos.css** — hoja de estilos externa que usa solo la Página 2. Selecciona las etiquetas por su nombre (`header`, `nav ul`, `nav a`, `section`, `footer`).
- **Archivos `.comentado`** (`Pagina1.comentado.html`, `Pagina2.comentado.html`, `estilos.comentado.css`) — versiones de estudio, comentadas línea por línea en español. Están excluidos de git: son solo para leer, nunca se cargan en el navegador.

## Demo

🌐 [https://cuutii.github.io/Progresivo/](https://cuutii.github.io/Progresivo/)

## Tecnologías

- HTML5
- CSS3

## Cómo usarlo

Descargá el repositorio y abrí `Pagina1.html` y `Pagina2.html` en tu navegador (doble clic en cada uno). Comparalas: vas a ver la misma página vestida y desnuda. `index.html` es el menú del ejercicio, y los archivos `.comentado` explican cada línea para estudiar.

## Autor

**Maximo Sanabria** — GitHub [@cuutii](https://github.com/cuutii)
