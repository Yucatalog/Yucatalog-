# Yucatalog — Catálogo Web

Catálogo web responsivo de accesorios listo para publicarse de forma gratuita en **GitHub Pages**.

## Estructura del proyecto

```text
yucatalog/
├── index.html      # Página principal con catálogo, filtros, carrusel y WhatsApp
├── .nojekyll       # Evita procesamiento innecesario en GitHub Pages
├── README.md       # Esta guía
└── img/            # Carpeta para subir tus fotografías reales (.jpg, .png, .webp)
```

## Cómo subirlo a GitHub y publicarlo gratis (sin usar comandos)

1. Crea una cuenta o inicia sesión en [GitHub](https://github.com).
2. Haz clic en **New** (Nuevo repositorio), ponle nombre (por ejemplo `yucatalog`), déjalo como **Public** y haz clic en **Create repository**.
3. En la pantalla del repositorio nuevo, haz clic en el enlace **uploading an existing file**.
4. Descomprime el archivo `.zip` en tu computadora y arrastra **todos los archivos y la carpeta `img`** hacia GitHub.
5. Baja y haz clic en el botón verde **Commit changes**.
6. Para activar tu página web pública:
   - Ve a **Settings** (Configuración) > **Pages** (en el menú izquierdo).
   - En **Build and deployment > Branch**, selecciona `main` y la carpeta `/ (root)`.
   - Haz clic en **Save**.
7. En 1 a 2 minutos aparecerá tu enlace público (ejemplo: `https://tu-usuario.github.io/yucatalog/`).

## Cómo agregar tus fotos reales

1. Coloca tus imágenes dentro de la carpeta `img/` (por ejemplo: `img/funda-llave-1.jpg`).
2. Abre `index.html` y busca la sección `PRODUCTOS`.
3. En cada imagen, escribe la ruta dentro de `url`:

```js
url: "img/funda-llave-1.jpg",
```

Mientras `url` esté vacío (`""`), la página mostrará automáticamente la ilustración vectorial de respaldo.

## Configuración actual

- **Tienda:** Yucatalog
- **Subtítulo:** Catálogo
- **WhatsApp:** `5215540130621`

Puedes editar estos datos en cualquier momento dentro del objeto `CONFIG` en `index.html`.
