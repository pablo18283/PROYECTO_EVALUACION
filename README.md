# Sitio Web Estático - HTML5 y CSS3

## Descripción del Proyecto

Este proyecto es un sitio web estático moderno construido con **HTML5 semántico** y **CSS3 avanzado**. Implementa un diseño oscuro profesional con tema corporativo, utilizando **Flexbox** para un layout responsivo y bien estructurado.

### Características principales:
- ✅ HTML5 con etiquetas semánticas
- ✅ Diseño responsive con Flexbox
- ✅ Tema oscuro moderno (#2c3e50)
- ✅ Formulario de contacto funcional
- ✅ Navegación intuitiva
- ✅ Estilos CSS3 con transiciones y efectos hover

---

## Estructura de Carpetas

```
PROYECTO_EVALUACION/
│
├── index.html                 # Página principal (HTML5 semántico)
├── README.md                  # Este archivo
│
├── css/
│   └── styles.css            # Estilos CSS3 (Flexbox, diseño oscuro)
│
└── images/                    # Carpeta para imágenes del proyecto
    └── (imágenes aquí)
```

### Descripción de archivos:

- **index.html**: Archivo HTML principal con estructura semántica incluyendo:
  - Header con título
  - Navegación con 3 enlaces
  - Main con 2 sections (información e imagen, formulario de contacto)
  - Footer con copyright

- **css/styles.css**: Archivo de estilos CSS3 que incluye:
  - Flexbox en nav, main y formulario
  - Diseño oscuro con color #2c3e50
  - Tipografía Arial
  - Efectos hover y transiciones
  - Responsividad

- **images/**: Carpeta destinada a almacenar todas las imágenes del sitio

---

## Cómo Usar

1. **Clonar o descargar** el proyecto
2. **Abrir `index.html`** en un navegador web
3. **Personalizar** contenido y estilos según necesidades

### Requisitos:
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación de dependencias

---

## Prompts Utilizados

### 1️⃣ Prompt: Crear HTML5 Semántico Estructurado

**Solicitud:**
```
Crea un archivo index.html con HTML5 semántico que incluya: header con título, nav con 3 enlaces, 
main con 2 sections (una con texto e imagen, otra con formulario de contacto con nombre email y mensaje), 
y footer. Enlaza un archivo css/styles.css externo.
```

**Propósito:** 
Este prompt se utilizó para generar la estructura base del proyecto con elementos semánticos HTML5. Permitió crear una página web con una arquitectura clara y accesible, siguiendo las mejores prácticas de HTML moderno.

**Resultado:**
- Creación de index.html con estructura completa y semántica
- Inclusión de formulario de contacto con validación de campos
- Enlaces organizados en navegación clara
- Integración con archivo CSS externo

---

### 2️⃣ Prompt: Diseño Oscuro con Flexbox Avanzado

**Solicitud:**
```
Crea el archivo css/styles.css para el index.html anterior. Usa Flexbox en el nav (justify-content center, gap), 
en el main (flex-direction column, align-items center) y en el formulario (flex-direction column). Diseño oscuro 
con color #2c3e50, tipografía Arial, estilos para header, nav, main, section, form, inputs, button y footer.
```

**Propósito:**
Este prompt fue usado para implementar estilos CSS3 profesionales con Flexbox. Permitió crear un diseño moderno, 
responsivo y visualmente atractivo con tema oscuro corporativo.

**Resultado:**
- Implementación de Flexbox en componentes clave (nav, main, formulario)
- Diseño oscuro cohesivo con paleta de colores profesionales
- Tipografía Arial consistente en todo el sitio
- Efectos hover, transiciones y estilos para inputs interactivos
- Sombras y bordes redondeados modernos

---

### 3️⃣ Prompt: Crear Documentación del Proyecto

**Solicitud:**
```
Crea un archivo README.md para un proyecto de sitio web estático con HTML5 y CSS3. Incluye: descripción del proyecto, 
estructura de carpetas (index.html, css/styles.css, images/), y una sección llamada "Prompts utilizados" 
con 3 prompts de ejemplo explicando para qué se usó cada uno.
```

**Propósito:**
Este prompt se utilizó para crear documentación completa del proyecto. Facilita la comprensión de la estructura, 
propósito y componentes del sitio web para desarrolladores presentes y futuros.

**Resultado:**
- Documentación clara y profesional en formato Markdown
- Descripción detallada de la estructura de carpetas
- Registro de prompts utilizados con explicaciones
- Instrucciones de uso y requisitos del proyecto

---

## Personalización

### Cambiar colores:
Edita `css/styles.css` y modifica las variables de color:
```css
background-color: #2c3e50;  /* Color de fondo oscuro */
color: #3498db;             /* Color de acentos */
```

### Agregar nuevas secciones:
Añade nuevos elementos `<section>` en `index.html` dentro de `<main>` y aplica los estilos existentes.

### Optimización de imágenes:
Coloca imágenes en la carpeta `images/` y referéncialas en el HTML:
```html
<img src="images/foto.jpg" alt="Descripción">
```

---

## Navegadores Soportados

- ✅ Chrome (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Edge (v90+)

---

## Licencia

Este proyecto está disponible para uso libre y personal.

---

## Autor

Proyecto creado con asistencia de GitHub Copilot

**Fecha:** Abril 2026
