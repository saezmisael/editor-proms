# 📝 Editor Pro MS — README COMPLETO

> Versión mejorada con la función **Imagen + Texto al lado**
> Desarrollado como herramienta de edición de documentos HTML visual, todo en un solo archivo.
> **Este código pertenece a Misael Sáez — Todos los derechos reservados.**

---

## 📁 ARCHIVOS NECESARIOS

| Archivo | Descripción |
|---|---|
| `editor-pro.html` | El editor completo — Editor Pro MS (único archivo necesario) |

**No se necesita instalar nada.** Es un archivo HTML autocontenido. Solo ábrelo en tu navegador.

---

## 🚀 CÓMO ABRIRLO

1. Descarga el archivo `editor-pro.html` a tu computador.
2. Haz doble clic sobre él — se abrirá en tu navegador web.
3. ¡Listo! No necesita servidor, ni internet (excepto para cargar las fuentes de Google).

### Navegadores compatibles
- ✅ Google Chrome (recomendado)
- ✅ Microsoft Edge
- ✅ Firefox
- ✅ Safari (Mac)

---

## 🌐 REQUISITOS DE INTERNET

El editor funciona offline **excepto** para:
- Las fuentes tipográficas (Google Fonts): Inter, Poppins, Merriweather, Playfair Display, etc.
- Los íconos (Font Awesome CDN)

Si no tienes internet, el editor funcionará con fuentes del sistema.

---

## 🗂️ ESTRUCTURA DE LA INTERFAZ

```
┌─────────────────────────────────────────────────┐
│  SIDEBAR (izquierda)   │   ÁREA DE TRABAJO       │
│                        │                          │
│  Tabs:                 │  ┌─ Toolbar formato ──┐  │
│  • Bloques             │  │ B I U ─ ↑ ↓ ← → │  │
│  • Tipo (tipografía)   │  └─────────────────────┘  │
│  • Color               │                          │
│  • Emoji               │  ┌─ Canvas / Lienzo ───┐  │
│  • Media               │  │  Área de edición    │  │
│                        │  │  contenteditable    │  │
│  [Exportar HTML]       │  └─────────────────────┘  │
│  [Importar HTML]       │                          │
│  [Limpiar todo]        │                          │
└─────────────────────────────────────────────────┘
```

---

## 🧩 FUNCIONALIDADES DETALLADAS

### TAB 1 — BLOQUES
Inserta bloques al final del documento:

| Botón | Qué inserta |
|---|---|
| Título H1 | Encabezado principal grande |
| Título H2 | Subtítulo mediano |
| Título H3 | Encabezado menor |
| Párrafo | Bloque de texto normal |
| Lista con viñetas | `<ul>` con 3 elementos |
| Lista numerada | `<ol>` con 3 elementos |
| Línea separadora | `<hr>` divisor visual |
| Cuadro info | Caja azul con borde izquierdo |
| Cuadro alerta | Caja amarilla de advertencia |
| Cuadro éxito | Caja verde de confirmación |
| Cuadro error | Caja roja de error |
| Hipervínculo | Modal para crear enlaces |
| Botón con enlace | Modal para crear botones estilizados |

---

### TAB 2 — TIPOGRAFÍA

#### Fuentes disponibles:
- Inter (moderna, por defecto)
- Poppins (redonda, amigable)
- Lato (limpia, corporativa)
- Merriweather (serif, lectura)
- Playfair Display (elegante, editorial)
- Source Serif 4 (editorial moderna)
- JetBrains Mono (código/monoespaciado)
- Georgia (clásica serif)

#### Aplicar fuente / tamaño / formato / alineación a:
- **Selección** — solo el texto que seleccionaste
- **Línea** — toda la línea donde está el cursor
- **Párrafo** — el bloque/párrafo completo
- **Todo** — todo el documento

#### Tamaños disponibles: 12px, 14px, 16px, 18px, 20px, 24px, 28px

#### Formatos: Negrita, Cursiva, Subrayado, Tachado

#### Alineaciones: Izquierda, Centro, Derecha, Justificado

---

### TAB 3 — COLOR

- **Color de texto**: 20 colores predefinidos + selector personalizado
- **Color de fondo (highlight)**: 10 colores pastel predefinidos + selector personalizado
- Ambos se aplican al texto seleccionado en el canvas

---

### TAB 4 — EMOJIS

- Buscador de emojis por categoría o nombre
- Categorías: Caras, Gestos, Animales, Comida, Viajes, Objetos, Símbolos, Actividades
- Clic en emoji → se inserta en la posición del cursor

---

### TAB 5 — MEDIA

#### Insertar imagen sola:
1. Selecciona tamaño: Completo (100%), Grande (75%), Mediano (50%), Pequeño (35%), 200px, o personalizado
2. Selecciona alineación: Centrada, Izquierda, Derecha
3. **Desde archivo**: botón "Subir imagen / GIF" → selecciona archivo local (JPG, PNG, GIF, WEBP)
4. **Desde URL**: botón "Imagen / GIF / Video" → ingresa URL (también acepta YouTube y Vimeo)

#### ⭐ NUEVA FUNCIÓN: Insertar Imagen + Texto al lado
(Ver sección completa más abajo)

---

## ⭐ NUEVA FUNCIÓN: IMAGEN + TEXTO AL LADO

Esta es la mejora principal de esta versión.

### ¿Cómo usarla?

1. Ve al tab **Media** en el sidebar
2. Haz clic en el botón morado **"Insertar Imagen + Texto"**
3. Se abrirá un modal con opciones:

#### Opciones del modal:

| Opción | Descripción |
|---|---|
| **Fuente de imagen** | Elige "Desde archivo" (sube una imagen de tu PC) o "Desde URL" (pega un enlace) |
| **Ancho de la imagen** | 200px / 250px / 300px / 40% / 50% del ancho del documento |
| **Disposición** | 🖼️📝 Imagen izquierda + Texto derecha, o 📝🖼️ Texto izquierda + Imagen derecha |
| **Alineación vertical** | El texto queda alineado arriba / centro / abajo respecto a la imagen |
| **Texto inicial** | Escribe el texto que aparecerá al lado de la imagen (también puedes editarlo después) |

4. Haz clic en **"Insertar bloque"**

#### Resultado en el documento:
```
┌─────────────────────────────────────────────┐
│  ┌──────────┐  ┌───────────────────────────┐ │
│  │  IMAGEN  │  │  Cuadro de texto editable │ │
│  │          │  │  con borde azul al hacer  │ │
│  │          │  │  clic. Puedes escribir    │ │
│  └──────────┘  │  libremente aquí.         │ │
│                └───────────────────────────┘ │
└─────────────────────────────────────────────┘
```

El bloque completo tiene:
- Fondo gris muy suave con borde punteado (para identificarlo como bloque)
- La imagen en su columna con el ancho configurado
- El cuadro de texto es **directamente editable** — haz clic y escribe
- El cuadro tiene bordes que se resaltan en azul al editar

#### Exportación:
Al exportar a HTML, el bloque imagen+texto se exporta correctamente con el mismo layout.
- Los estilos del bloque son **100% inline** → no dependen de clases externas
- El `contenteditable` se elimina automáticamente del HTML exportado
- El bloque es **responsive**: en pantallas ≤600px la imagen y el texto se apilan verticalmente de forma automática

---

## 🔧 TOOLBAR DE FORMATO RÁPIDO

La barra superior del canvas permite:

| Botón | Función |
|---|---|
| **B** | Negrita |
| *I* | Cursiva |
| U̲ | Subrayado |
| ~~S~~ | Tachado |
| ← ↔ → | Alinear izquierda / centro / derecha |
| • / 1. | Lista viñetas / numerada |
| ↩ / ↪ | Deshacer / Rehacer |
| 🔗 | Insertar hipervínculo |
| 🔗✗ | Quitar enlace |

---

## 📤 EXPORTAR HTML

Botón **"Exportar HTML"** (sidebar inferior):
- Genera un archivo `.html` con todo el contenido del documento
- El archivo es autocontenido y funciona en cualquier navegador
- Incluye todas las fuentes, estilos, imágenes en base64 y bloques
- Nombre automático: `documento-{timestamp}.html`

---

## 📥 IMPORTAR HTML

Botón **"Importar HTML"** (sidebar inferior):
- Acepta archivos `.html` previamente exportados por el editor
- Recupera el contenido y, si es posible, la tipografía
- También puedes importar HTML de otras fuentes (puede que algunos estilos no apliquen)

---

## 🗑️ LIMPIAR TODO

Botón **"Limpiar todo"** (sidebar inferior):
- Pide confirmación antes de borrar
- Resetea el canvas a su estado inicial
- **Esta acción no se puede deshacer** (usa Ctrl+Z antes si fue un error)

---

## ⌨️ ATAJOS DE TECLADO

Dentro del canvas (área de edición):

| Atajo | Acción |
|---|---|
| `Ctrl + B` | Negrita |
| `Ctrl + I` | Cursiva |
| `Ctrl + U` | Subrayado |
| `Ctrl + Z` | Deshacer |
| `Ctrl + Y` | Rehacer |
| `Ctrl + A` | Seleccionar todo el contenido |

---

## 🎨 PERSONALIZACIÓN

### Cambiar colores del sidebar
En el `<style>` del HTML, busca `:root` y modifica:
```css
:root {
    --accent: #4f8ef7;   /* Color principal (azul) */
    --accent2: #a259f7;  /* Color secundario (morado) */
    --sidebar-bg: #1a1d23; /* Fondo sidebar */
}
```

### Cambiar ancho del sidebar
El sidebar tiene actualmente **310px** de ancho. Para modificarlo busca en `:root`:
```css
--sidebar-width: 310px;
```

### Cambiar ancho del canvas
```css
#canvas {
    max-width: 820px; /* Aumenta o disminuye el ancho máximo */
}
```

### Agregar nuevas fuentes
1. Agrega el import en el `<head>`: `@import url('https://fonts.googleapis.com/...')`
2. Agrega la opción en `<select id="fontSelector">`:
   ```html
   <option value="'TuFuente', sans-serif">Nombre de la fuente</option>
   ```

---

## 🐛 SOLUCIÓN DE PROBLEMAS

| Problema | Solución |
|---|---|
| Las fuentes no cargan | Verifica tu conexión a internet. El editor usa Google Fonts CDN. |
| La imagen no se muestra desde URL | Verifica que la URL sea directa a una imagen (termina en .jpg, .png, .gif, etc.) |
| Al exportar, las imágenes no aparecen | Usa "Desde archivo" en vez de URL para que se incruste en base64 |
| El texto del cuadro imagen+texto no se puede editar | Haz clic directamente dentro del cuadro de texto (el área con borde) |
| El bloque imagen+texto no se exporta con el estilo | El CSS del bloque está inline, debe exportarse correctamente |
| El bloque imagen+texto se deforma al exportar | Actualiza al archivo v1.4. Los estilos ahora son inline y el export incluye el CSS del bloque. |
| Las imágenes o videos se salen del marco al exportar | Corregido en v1.4. Todos los elementos tienen `max-width:100%` y `box-sizing:border-box`. |
| El texto de las listas se desborda horizontalmente | Corregido en v1.4. `overflow-wrap:break-word` y `word-break:break-word` en todos los elementos de texto. |
| El editor no funciona en Internet Explorer | IE no es compatible. Usa Chrome, Edge, Firefox o Safari |

---

## 📋 NOTAS TÉCNICAS

- **Tecnologías usadas**: HTML5, CSS3 Vanilla, JavaScript Vanilla (sin frameworks)
- **Dependencias externas**: Font Awesome 6.4 (CDN), Google Fonts (CDN)
- **Almacenamiento**: No se guarda automáticamente. Exporta frecuentemente.
- **Edición del canvas**: Usa la API nativa `contenteditable` del navegador
- **Imágenes desde archivo**: Se convierten a base64 y se embeben en el HTML
- **Compatibilidad de `execCommand`**: Algunos navegadores modernos han deprecado esta API, pero Chrome/Edge la siguen soportando correctamente.

---

## 🔄 HISTORIAL DE VERSIONES

| Versión | Cambios |
|---|---|
| v1.0 | Versión original — bloques, tipografía, color, emojis, media |
| v1.1 | ✅ Nueva función: **Imagen + Texto al lado** con cuadro editable |
| v1.2 | ✅ Título actualizado a **Editor Pro MS**, comentario de autoría (Misael Sáez), sidebar ampliado a 310px |
| v1.3 | ✅ **Fix exportación**: bloque Imagen+Texto ahora mantiene el layout al exportar; estilos 100% inline; responsive en móviles; `contenteditable` se limpia en el export |
| v1.4 (actual) | ✅ **Fix contención global**: imágenes, videos y listas ya no se salen del marco — ni en el editor ni en el HTML exportado. CSS `overflow-wrap`, `word-break`, `max-width:100%` y `box-sizing:border-box` aplicados en todos los elementos. Videos con wrapper responsivo 16:9. Responsive móvil mejorado (float eliminado en ≤600px). |

---

## 👨‍💻 AUTORÍA

**Este código pertenece a Misael Sáez**  
Desarrollado con RC Tech Software  
Herramienta de edición de documentos HTML visual — Editor Pro MS

---

*Cualquier mejora adicional, consultar con el equipo de desarrollo.*
