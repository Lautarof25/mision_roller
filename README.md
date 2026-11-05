# Misión Rollers

Sitio estático para las clases de rollers de Karen. No requiere dependencias ni un paso de compilación.

## Estructura

- `index.html`: contenido, metadatos y estructura semántica.
- `styles.css`: estilos y diseño adaptable.
- Imágenes y videos: recursos referenciados directamente desde el HTML.

## Vista local

Desde la carpeta del proyecto, ejecutá `python3 -m http.server 8000` y abrí `http://localhost:8000`.

Las imágenes fuera de la primera pantalla se cargan de forma diferida. Los videos usan `preload="none"` para evitar precargar contenido antes de que la persona elija reproducirlos.
