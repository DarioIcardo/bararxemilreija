# ARXEMIL — Alta Cocina Gallega Contemporánea

Sitio web oficial y catálogo gastronómico editorial del restaurante **ARXEMIL**, situado en el centro histórico de Lugo (Galicia). Diseñado con estética editorial minimalista de alto impacto visual, tipografías clásicas y modernas (*EB Garamond* y *Manrope*), diseño 100% responsivo y optimizado para máxima velocidad y posicionamiento en buscadores (SEO).

---

## 🏛️ Características del Proyecto

- **Fidelidad al Sistema de Diseño (`DESIGN.md`):** Paleta tonal orgánica (*Warm Ivory, Dark Olive, Terracotta Copper*), bordes geométricos arquitectónicos puros (0px border-radius) y balance asimétrico editorial.
- **Estructura Semántica Completa:**
  - **Header interactivo:** Con navegación fluida a secciones y menú móvil adaptable.
  - **Hero Editorial:** Presentación y reserva directa.
  - **Identidad & Historia:** Relato de marca "Desde 2015" y pilares gastronómicos.
  - **Carta Gastronómica:** Entrantes, mariscos, lonja, carnes de pasto y repostería artesana.
  - **Selección ARXEMIL:** Platos emblemáticos con desglose de producto.
  - **Galería con Lightbox:** Visor interactivo a pantalla completa para apreciar los detalles de la sala, platos y coctelería.
  - **Ubicación & Contacto:** Mapa interactivo integrado de Lugo, horarios de cocina y enlace directo a Google Maps.
  - **Conversión Inmediata & Footer:** Botones de reserva telefónica directa y accesos rápidos.
- **Gestión Robusta de Imágenes:** Enlaces locales codificados con fallback automático a CDN (`onerror`) para garantizar que todas las imágenes carguen siempre sin errores.
- **SEO & Datos Estructurados:** Marcado enriquecido Schema.org (`Restaurant` JSON-LD) con datos de geolocalización, horarios, carta y contacto para indexación en Google.

---

## 📁 Estructura de Archivos

```text
bar moderno/
├── imagenes/                                  # Fotografías del restaurante y platos
│   ├── Gemini_Generated_Image_39jbjt39jbjt39jb.jfif
│   ├── Gemini_Generated_Image_39jbjt39jbjt39jb (1).jfif
│   ├── Gemini_Generated_Image_39jbjt39jbjt39jb (2).jfif
│   └── Gemini_Generated_Image_39jbjt39jbjt39jb (3).jfif
├── index.html                                 # Página web principal completa
├── vercel.json                                # Configuración de despliegue y caché en Vercel
├── .gitignore                                 # Exclusiones para control de versiones
├── DESIGN.md                                  # Tokens y guía de diseño del proyecto
├── screen.png                                 # Captura de referencia visual
└── README.md                                  # Documentación del proyecto
```

---

## 🚀 Guía de Despliegue en GitHub y Vercel

Sigue estos sencillos pasos para publicar tu web en internet en pocos minutos:

### Paso 1: Subir el proyecto a GitHub
1. Abre tu navegador y ve a [github.com](https://github.com). Inicia sesión con tu cuenta.
2. Haz clic en el botón verde **"New"** (o el icono `+` arriba a la derecha y selecciona **"New repository"**).
3. Escribe un nombre para tu repositorio (por ejemplo: `arxemil-restaurante`).
4. Déjalo en modo **Public** y pulsa en **"Create repository"**.
5. En la pantalla que aparece, puedes:
   - **Opción fácil desde el navegador:** Haz clic en el enlace **"uploading an existing file"**, arrastra todos los archivos de esta carpeta (`index.html`, carpeta `imagenes`, `vercel.json`, `.gitignore`, `README.md`) y pulsa **"Commit changes"**.
   - **O si usas la terminal / Git:**
     ```bash
     git init
     git add .
     git commit -m "Lanzamiento web ARXEMIL"
     git branch -M main
     git remote add origin https://github.com/TU_USUARIO/arxemil-restaurante.git
     git push -u origin main
     ```

---

### Paso 2: Desplegar en Vercel (1 clic)
1. Entra en [vercel.com](https://vercel.com) e inicia sesión (recomendado iniciar sesión con tu cuenta de GitHub).
2. En tu panel principal (*Dashboard*), haz clic en el botón **"Add New..."** > **"Project"**.
3. Verás una lista con tus repositorios de GitHub. Busca `arxemil-restaurante` y haz clic en **"Import"**.
4. En la pantalla de configuración, no necesitas cambiar nada (Vercel detectará automáticamente el archivo `vercel.json` y el sitio estático).
5. Haz clic en el botón azul **"Deploy"**.
6. En unos 15-30 segundos, tu página web estará 100% activa con un enlace público (por ejemplo: `https://arxemil-restaurante.vercel.app`) y certificado SSL (HTTPS) gratuito incluido.

---

© 2025 ARXEMIL • Todos los derechos reservados.
