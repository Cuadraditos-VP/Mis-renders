# Renders Gallery

Galería simple y moderna para organizar tus renders en carpetas.

Archivo único (`renders-gallery.html`). Funciona 100% en el navegador, sin servidor.

## Cómo usarlo

1. Descarga o clona este repositorio
2. Abre `renders-gallery.html` en tu navegador (Chrome, Firefox, Edge, Safari…)
3. Crea carpetas, sube imágenes y organízalas

También puedes arrastrar las imágenes directamente a la ventana.

## Funciones

- Crear, renombrar y eliminar carpetas
- Subir renders (botón o drag & drop)
- Vista en grilla
- Vista previa a pantalla completa
- Navegar entre imágenes con las flechas ← →
- Buscar por nombre
- Descargar todo en un ZIP (botón **↓ ZIP**)

## Importante sobre las imágenes

Las imágenes **no se guardan** de forma permanente dentro del HTML.  
Solo permanecen mientras la pestaña del navegador esté abierta.

Las carpetas sí se recuerdan (se guardan en el navegador con `localStorage`).

**Recomendación:** usa el botón **↓ ZIP** para descargar todas tus imágenes organizadas en carpetas y guardarlas en tu PC o en este repositorio de GitHub.

## Estructura del ZIP exportado

Cuando uses el botón **↓ ZIP**, se genera un archivo con esta estructura:

```
renders-YYYY-MM-DD.zip
├── Nombre de carpeta 1/
│   ├── render1.png
│   └── render2.jpg
├── Nombre de carpeta 2/
│   └── ...
└── carpetas.json
```

## Cómo poner este proyecto en GitHub

### Opción rápida (desde la web)
1. Entra a [github.com/new](https://github.com/new)
2. Crea un repositorio nuevo (puede ser público o privado)
3. Sube el archivo `renders-gallery.html` y este `README.md`

### Opción con Git (terminal)
```bash
git clone https://github.com/TU-USUARIO/TU-REPO.git
cd TU-REPO
# Copia renders-gallery.html y README.md aquí
git add .
git commit -m "Add Renders Gallery"
git push
```

## Personalización

El archivo es autocontenido. Puedes editarlo con cualquier editor de texto para cambiar colores, textos o añadir funciones.

## Licencia

Uso libre. Haz lo que quieras con él.
