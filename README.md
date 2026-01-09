# Nexus - Brand Kit

![Nexus Banner](IDENTIDAD%20NEXUSAPP/ESLOGAN/EsloganNexusOscuro.png)

## 📋 Índice
- [Visión General](#visión-general)
- [Lema de Marca](#lema-de-marca)
- [Sistema de Logo](#sistema-de-logo)
- [Paleta de Colores](#paleta-de-colores)
- [Tipografía](#tipografía)
- [Espaciado y Construcción](#espaciado-y-construcción)
- [Aplicaciones Visuales](#aplicaciones-visuales)
- [Guías de Uso](#guías-de-uso)
- [Recursos Descargables](#recursos-descargables)
- [Código para Desarrollo](#código-de-colores-para-desarrollo)
- [Contacto](#contacto-y-aprobaciones)

---

## 🎯 Visión General

Nexus es una marca moderna que encarna la conexión, el descubrimiento y el valor a través de su sofisticada identidad visual. La marca utiliza una estética de degradado contemporánea con enfoque en tonos púrpura y rosa, creando una presencia premium y accesible.

### Valores de Marca
- **Unificación**: Consolidar y simplificar procesos complejos
- **Descubrimiento**: Revelar información valiosa
- **Conexión**: Crear vínculos significativos
- **Innovación**: Soluciones modernas y tecnológicas

---

## 💬 Lema de Marca
```
Unifica tu búsqueda. Descubre el valor.
```

Este lema refleja la propuesta de valor central de Nexus: consolidar procesos de búsqueda y revelar información valiosa para el usuario.

---

## 🎨 Sistema de Logo

### Variaciones del Logo

#### 1. **Ícono Solo**
- Uso: Favicon, apps móviles, redes sociales
- Tamaño mínimo: 32px (digital), 8mm (impreso)
- Archivo: `nexus-icon.svg` / `nexus-icon.png`

#### 2. **Logotipo Completo - Fondo Claro**
- Uso: Encabezados web, documentos, presentaciones
- Fondo: Blanco o colores claros (#FFFFFF, #F8F8F8)
- Archivo: `nexus-logo-light.svg` / `nexus-logo-light.png`

#### 3. **Logotipo Completo - Fondo Oscuro**
- Uso: Hero sections, materiales premium, landing pages
- Fondo: Negro o colores oscuros (#000000)
- Archivo: `nexus-logo-dark.svg` / `nexus-logo-dark.png`
- **Recomendación**: Esta versión crea el mayor impacto visual

#### 4. **Ícono - Fondo Oscuro**
- Uso: Aplicaciones con tema oscuro, apps móviles modo nocturno
- Mayor contraste y visibilidad
- Archivo: `nexus-icon-dark.png`

#### 5. **Logo con Tagline**
- Uso: Presentaciones corporativas, landing pages principales
- Incluye lema completo debajo del logo
- Archivo: `nexus-full-tagline.svg`
- Composición: Logo + "Unifica tu búsqueda. Descubre el valor."

#### 6. **Logo Transparente**
- Uso: Superposiciones, marcas de agua, overlays
- Formato: PNG con canal alpha
- Archivo: `nexus-logo-transparent.png`

### Geometría del Logo
```
Características del Ícono "N":
├── Corte diagonal atravesando la letra de izquierda superior a derecha inferior
├── Bordes angulares con esquinas sutilmente redondeadas
├── Diseño asimétrico con flujo visual dinámico
├── Barra vertical derecha más delgada que la izquierda
├── Espacios negativos como parte integral del diseño
└── Forma que sugiere conexión y movimiento
```

**Proporciones del Sistema:**
- Relación Ícono:Logotipo → 1:3.5
- Relación Logo:Tagline → 1:0.2 (altura)
- Espaciado entre logo y tagline → 15% de la altura del logo

### Anatomía del Logotipo "Nexus."

**Características clave:**
- Primera letra mayúscula: "N"
- Resto en minúsculas: "exus"
- El punto final "." es OBLIGATORIO y parte integral del logo
- Tratamiento tipográfico: Bold, geométrico, moderno
- Kerning óptico ajustado entre caracteres

---

## 🎨 Paleta de Colores

### Degradado Principal

El degradado característico de Nexus fluye de izquierda a derecha (90°) o de arriba hacia abajo (180°):

**Degradado Horizontal (preferido):**
```css
background: linear-gradient(90deg, #A8B4FF 0%, #CDB0E8 50%, #FF91D5 100%);
```

**Degradado Vertical:**
```css
background: linear-gradient(180deg, #A8B4FF 0%, #CDB0E8 50%, #FF91D5 100%);
```

**Degradado Diagonal (alternativo):**
```css
background: linear-gradient(135deg, #A8B4FF 0%, #CDB0E8 50%, #FF91D5 100%);
```

### Colores Primarios

| Color | Nombre | HEX | RGB | HSL | Uso Principal |
|-------|--------|-----|-----|-----|---------------|
| 🔵 | **Periwinkle Blue** | `#A8B4FF` | `rgb(168, 180, 255)` | `hsl(232, 100%, 83%)` | Inicio del degradado, acentos fríos |
| 💜 | **Lavanda** | `#CDB0E8` | `rgb(205, 176, 232)` | `hsl(271, 54%, 80%)` | Punto medio del degradado |
| 💗 | **Rosa Brillante** | `#FF91D5` | `rgb(255, 145, 213)` | `hsl(323, 100%, 78%)` | Final del degradado, acentos cálidos |
| 🌸 | **Rosa Vibrante** | `#FF69B4` | `rgb(255, 105, 180)` | `hsl(330, 100%, 71%)` | Highlights, CTAs, elementos interactivos |

### Colores de Fondo

| Contexto | Color | HEX | RGB | Uso |
|----------|-------|-----|-----|-----|
| **Fondo Claro Principal** | Blanco humo | `#F8F8F8` | `rgb(248, 248, 248)` | Páginas web, documentos, fondos neutros |
| **Fondo Blanco Puro** | Blanco | `#FFFFFF` | `rgb(255, 255, 255)` | Tarjetas, modales, secciones destacadas |
| **Fondo Oscuro** | Negro puro | `#000000` | `rgb(0, 0, 0)` | Hero sections, materiales premium |
| **Fondo Oscuro Suave** | Gris muy oscuro | `#0A0A0A` | `rgb(10, 10, 10)` | Alternativa suave al negro puro |

### Colores de Texto

| Contexto | Color | HEX | RGB | Contraste |
|----------|-------|-----|-----|-----------|
| **Texto sobre fondo claro** | Gris oscuro | `#333333` | `rgb(51, 51, 51)` | AAA |
| **Texto secundario claro** | Gris medio | `#666666` | `rgb(102, 102, 102)` | AA |
| **Texto sobre fondo oscuro** | Gris claro | `#E0E0E0` | `rgb(224, 224, 224)` | AAA |
| **Texto sobre negro** | Blanco | `#FFFFFF` | `rgb(255, 255, 255)` | AAA |

### Aplicación de Colores

#### ✅ Uso Correcto

**Fondos Claros:**
```css
/* Logo con degradado sobre fondo claro */
.hero-light {
  background: #FFFFFF;
}
.logo {
  background: linear-gradient(90deg, #A8B4FF, #CDB0E8, #FF91D5);
}
```

**Fondos Oscuros (RECOMENDADO para máximo impacto):**
```css
/* Logo con degradado sobre fondo negro */
.hero-dark {
  background: #000000;
}
.logo {
  background: linear-gradient(90deg, #A8B4FF, #CDB0E8, #FF91D5);
  /* El contraste crea un efecto premium y dramático */
}
```

**Elementos Interactivos:**
```css
/* Botones y CTAs */
.button-primary {
  background: linear-gradient(90deg, #A8B4FF, #FF91D5);
  color: #FFFFFF;
  transition: transform 0.3s ease;
}

.button-primary:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 24px rgba(168, 180, 255, 0.4);
}
```

**Texto con Degradado:**
```css
.gradient-text {
  background: linear-gradient(90deg, #A8B4FF 0%, #CDB0E8 50%, #FF91D5 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-weight: 700;
}
```

#### ❌ Evitar

- ❌ No usar el logo sobre fondos de color medio (grises #808080, tonos pastel)
- ❌ No invertir los colores del degradado (rosa → azul)
- ❌ No usar un solo color sólido del degradado para el logo completo
- ❌ No aplicar el degradado en dirección invertida sin autorización
- ❌ No colocar el logo sobre imágenes sin capa de overlay con contraste adecuado
- ❌ No usar colores del degradado con opacidad reducida para el logo principal

### Paleta Extendida (Usos Secundarios)

| Color | HEX | Uso |
|-------|-----|-----|
| **Azul claro suave** | `#B4BFFF` | Fondos sutiles, tarjetas hover |
| **Lavanda claro** | `#E0D4F0` | Fondos de secciones alternativas |
| **Rosa pastel** | `#FFB3E0` | Elementos decorativos, ilustraciones |
| **Azul oscuro** | `#5566CC` | Texto sobre fondos claros (accesibilidad) |
| **Púrpura oscuro** | `#8866BB` | Enlaces, elementos interactivos |

---

## ✍️ Tipografía

### Fuente Principal

**Familia Tipográfica**: Sans-serif geométrica moderna

**Fuentes de referencia similares:**
- Outfit (recomendada)
- Space Grotesk
- Satoshi
- Inter
- DM Sans
- Manrope

**Características Tipográficas:**
```
├── Estilo: Geométrico, limpio, moderno, humanista
├── Clasificación: Neo-grotesca geométrica
├── Peso para Logo: Bold (700) / Extra Bold (800)
├── Peso para Tagline: Regular (400) / Medium (500)
├── X-height: Alto (mejora legibilidad digital)
├── Stroke: Grosor casi uniforme con ligera variación óptica
├── Terminales: Redondeadas en algunos caracteres
├── Aperturas: Abiertas para mejor legibilidad
├── Números: Tabulares para alineación
└── Soporte: Multiidioma, caracteres especiales
```

### Especificaciones del Logotipo

**Wordmark "Nexus.":**
```css
.nexus-wordmark {
  font-family: 'Outfit', 'Space Grotesk', sans-serif;
  font-weight: 700; /* Bold */
  text-transform: none; /* "Nexus" - Primera letra mayúscula */
  letter-spacing: -0.02em; /* Kerning ajustado ópticamente */
  font-size: 48px; /* Tamaño base de referencia */
}

/* El punto es obligatorio */
.nexus-wordmark::after {
  content: '.';
  /* Mismo peso y color que el texto */
}
```

**Características específicas:**
- La "N" mayúscula tiene el mismo peso visual que las minúsculas
- Espaciado entre "N" y "e": ligeramente reducido
- El punto "." mantiene el mismo grosor que las letras
- Altura del punto: alineado con la altura x de las minúsculas

### Especificaciones del Tagline

**"Unifica tu búsqueda. Descubre el valor.":**
```css
.nexus-tagline {
  font-family: 'Outfit', sans-serif;
  font-weight: 400; /* Regular */
  font-size: 0.2em; /* 20% de la altura del logo */
  letter-spacing: 0.01em;
  line-height: 1.4;
  text-align: center;
  
  /* Colores según contexto */
  color: #FFFFFF; /* Sobre fondos oscuros */
  color: #666666; /* Sobre fondos claros */
  
  /* Espaciado desde el logo */
  margin-top: 15%; /* 15% de la altura del logo */
}
```

### Jerarquía Tipográfica Web

#### Títulos y Encabezados

**H1 - Hero Headlines:**
```css
h1, .h1 {
  font-size: clamp(48px, 8vw, 96px); /* Responsivo */
  font-weight: 700; /* Bold */
  line-height: 1.1;
  letter-spacing: -0.02em;
  margin-bottom: 1.5rem;
  
  /* Opción con degradado */
  background: linear-gradient(90deg, #A8B4FF, #FF91D5);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

**H2 - Encabezados de Sección:**
```css
h2, .h2 {
  font-size: clamp(36px, 6vw, 64px);
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -0.01em;
  margin-bottom: 1.25rem;
  color: #333333; /* Fondo claro */
  color: #FFFFFF; /* Fondo oscuro */
}
```

**H3 - Subsecciones:**
```css
h3, .h3 {
  font-size: clamp(28px, 4vw, 40px);
  font-weight: 600; /* Semi-Bold */
  line-height: 1.3;
  letter-spacing: -0.005em;
  margin-bottom: 1rem;
}
```

**H4 - Títulos Menores:**
```css
h4, .h4 {
  font-size: clamp(22px, 3vw, 28px);
  font-weight: 600;
  line-height: 1.4;
  margin-bottom: 0.875rem;
}
```

**H5 y H6:**
```css
h5, .h5 {
  font-size: 20px;
  font-weight: 500; /* Medium */
  line-height: 1.5;
}

h6, .h6 {
  font-size: 18px;
  font-weight: 500;
  line-height: 1.5;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
```

#### Texto de Cuerpo

**Body Copy - Tamaño Base:**
```css
body, p, .body-text {
  font-size: 16px;
  font-weight: 400; /* Regular */
  line-height: 1.6;
  color: #333333; /* Fondo claro */
  margin-bottom: 1rem;
}

/* Tamaño grande para lectura destacada */
.body-large {
  font-size: 18px;
  line-height: 1.7;
}

/* Tamaño pequeño */
.body-small, small {
  font-size: 14px;
  line-height: 1.5;
}

/* Caption / Pie de foto */
.caption {
  font-size: 12px;
  line-height: 1.4;
  color: #666666;
  font-style: italic;
}
```

**Texto sobre fondo oscuro:**
```css
.dark-theme p,
.dark-bg .body-text {
  color: #E0E0E0;
}

.dark-theme small {
  color: #AAAAAA;
}
```

#### Elementos Especiales

**Lead Paragraph (Introducción destacada):**
```css
.lead {
  font-size: 20px;
  font-weight: 400;
  line-height: 1.7;
  color: #555555;
  margin-bottom: 2rem;
}
```

**Citas (Blockquote):**
```css
blockquote {
  font-size: 20px;
  font-weight: 500;
  line-height: 1.6;
  font-style: italic;
  padding-left: 2rem;
  border-left: 4px solid;
  border-image: linear-gradient(180deg, #A8B4FF, #FF91D5) 1;
  margin: 2rem 0;
  color: #555555;
}
```

**Código y Monoespaciado:**
```css
code, pre {
  font-family: 'Fira Code', 'Monaco', 'Consolas', monospace;
  font-size: 14px;
  background: #F5F5F5;
  padding: 0.2em 0.4em;
  border-radius: 4px;
}

pre {
  padding: 1rem;
  overflow-x: auto;
  line-height: 1.5;
}
```

### Pesos de Fuente Disponibles

| Peso | Valor | Uso Recomendado |
|------|-------|-----------------|
| **Light** | 300 | Evitar en tamaños pequeños |
| **Regular** | 400 | Texto de cuerpo, párrafos |
| **Medium** | 500 | Subtítulos, énfasis suave |
| **Semi-Bold** | 600 | Encabezados H3-H4, navegación |
| **Bold** | 700 | Logo, H1-H2, CTAs |
| **Extra-Bold** | 800 | Uso especial, títulos hero |

### Aplicación de Degradado en Texto

**Títulos con degradado Nexus:**
```css
.gradient-text {
  background: linear-gradient(90deg, #A8B4FF 0%, #CDB0E8 50%, #FF91D5 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  
  /* Fallback para navegadores sin soporte */
  color: #A8B4FF;
}

/* Animación opcional */
@keyframes gradient-shift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.gradient-text-animated {
  background: linear-gradient(90deg, #A8B4FF, #CDB0E8, #FF91D5, #CDB0E8, #A8B4FF);
  background-size: 200% auto;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient-shift 3s ease infinite;
}
```

### Escala Tipográfica Responsiva
```css
/* Mobile First */
:root {
  --font-base: 16px;
  --font-h1: 2.5rem; /* 40px */
  --font-h2: 2rem;   /* 32px */
  --font-h3: 1.5rem; /* 24px */
}

/* Tablet */
@media (min-width: 768px) {
  :root {
    --font-h1: 3.5rem; /* 56px */
    --font-h2: 2.75rem; /* 44px */
    --font-h3: 2rem; /* 32px */
  }
}

/* Desktop */
@media (min-width: 1024px) {
  :root {
    --font-h1: 4.5rem; /* 72px */
    --font-h2: 3.5rem; /* 56px */
    --font-h3: 2.5rem; /* 40px */
  }
}

/* Large Desktop */
@media (min-width: 1440px) {
  :root {
    --font-h1: 6rem; /* 96px */
    --font-h2: 4rem; /* 64px */
    --font-h3: 2.75rem; /* 44px */
  }
}
```

---

## 📏 Espaciado y Construcción

### Espacio de Seguridad (Clear Space)

Mantener un espacio mínimo alrededor del logo equivalente a la **altura del ícono "N"**.
```
Representación visual del espacio de seguridad:

┌─────────────────────────────────────────────┐
│                                             │
│                                             │
│         ┌───────────────────────┐          │
│         │                       │          │
│    X    │    [Nexus Logo]       │    X     │  ← X = Altura del ícono "N"
│         │                       │          │
│         └───────────────────────┘          │
│                                             │
│                                             │
└─────────────────────────────────────────────┘

X = Unidad de medida base (altura del ícono)
```

**Regla de oro:** Ningún elemento (texto, imagen, borde) debe estar más cerca del logo que la distancia X.

### Tamaños Mínimos

#### Digital (Pantalla)

| Variante | Ancho Mínimo | Altura Mínima | Uso |
|----------|--------------|---------------|-----|
| **Ícono solo** | 32px | 32px | Favicon, thumbnails |
| **Ícono (recomendado)** | 48px | 48px | Apps móviles, iconos |
| **Logo completo** | 120px | ~34px | Navegación móvil |
| **Logo recomendado** | 160px | ~46px | Navegación desktop |
| **Logo + tagline** | 180px | ~65px | Headers, footers |
| **Logo hero** | 240px+ | ~69px+ | Landing pages |

#### Impreso (Print)

| Variante | Ancho Mínimo | Altura Mínima | Uso |
|----------|--------------|---------------|-----|
| **Ícono solo** | 8mm | 8mm | Pequeñas aplicaciones |
| **Logo completo** | 25mm | ~7mm | Tarjetas de visita |
| **Logo recomendado** | 35mm | ~10mm | Documentos estándar |
| **Logo + tagline** | 50mm | ~18mm | Material corporativo |

**Nota:** Cualquier tamaño por debajo de estos mínimos compromete la legibilidad y debe evitarse.

### Proporciones de Escalado

#### Logo Completo (Solo "Nexus.")
```
Proporciones:
├── Ancho: 100% (referencia)
├── Alto: ~28.5% del ancho (mantener ratio)
├── Aspect Ratio: 3.5:1 (aproximado)
└── Escalar siempre proporcionalmente
```

**Ejemplo de cálculo:**
- Si ancho = 350px → Alto = 100px
- Si ancho = 200px → Alto = 57px
- Si ancho = 140px → Alto = 40px

#### Logo con Tagline
```
Composición:
├── Logo (Nexus.): 100% ancho
├── Espacio vertical: 15% de la altura del logo
├── Tagline: 100% ancho del logo
├── Altura tagline: 20% de la altura del logo
└── Alto total: ~150% de la altura del logo base
```

**Ejemplo de composición:**
```
┌─────────────────────┐
│     Nexus.          │ ← 100% (40px ejemplo)
├─────────────────────┤
│                     │ ← 15% espacio (6px)
├─────────────────────┤
│ Unifica tu búsqueda │ ← 20% (8px)
│ Descubre el valor.  │
└─────────────────────┘
Total: ~54px altura
```

### Grilla y Alineación

#### Sistema de Grid para el Ícono "N"

El ícono está construido sobre una grilla de proporciones áureas:
```
Grid Base: 100 x 100 unidades
├── Ancho de barras verticales: 
│   ├── Izquierda: 22 unidades
│   └── Derecha: 18 unidades
├── Diagonal: 
│   ├── Grosor: 24 unidades
│   └── Ángulo: ~45-50 grados
└── Espacios negativos: Calculados proporcionalmente
```

#### Alineación del Logo

**Horizontal:**
- Centro: Para headers, heros, materiales corporativos
- Izquierda: Para navegación, documentos
- Derecha: Casos especiales, firmas

**Vertical:**
- Centro vertical: Navegación, tarjetas
- Alineación superior: Headers fijos
- Baseline: Junto a otros elementos de texto

### Espaciado con Otros Elementos

**Logo + Texto descriptivo:**
```css
.logo-container {
  display: flex;
  align-items: center;
  gap: 2rem; /* 2x la altura del logo mínimo */
}
```

**Logo + Navegación:**
```css
.header {
  display: flex;
  justify-content: space-between;
  padding: 1.5rem 2rem;
}

.logo {
  margin-right: 3rem; /* Espacio generoso */
}
```

**Logo en footer:**
```css
.footer-logo {
  margin-bottom: 2rem;
  opacity: 0.9;
}
```

### Restricciones de Construcción

#### ✅ Permitido
- Escalar proporcionalmente manteniendo aspect ratio
- Centrar en espacios disponibles
- Alinear a grid de la interfaz
- Usar versiones pre-definidas del logo

#### ❌ Prohibido
- Estirar horizontal o verticalmente
- Rotar o inclinar el logo
- Distorsionar proporciones
- Cambiar espaciado entre letras
- Modificar grosor de líneas
- Separar elementos del logo
- Recrear el logo desde cero

---

## 🖼️ Aplicaciones Visuales

### Uso en Diferentes Contextos

#### Web y Digital

**Hero Section (Fondo Oscuro - RECOMENDADO):**
```html
<section class="hero-dark">
  <div class="hero-content">
    <img src="nexus-logo-dark.svg" alt="Nexus" class="hero-logo" />
    <h1 class="gradient-text">Unifica tu búsqueda. Descubre el valor.</h1>
    <p class="hero-description">
      Conecta, descubre y encuentra lo que realmente importa con Nexus.
    </p>
    <button class="cta-button">Comenzar</button>
  </div>
</section>

<style>
.hero-dark {
  background: #000000;
  padding: 8rem 2rem;
  text-align: center;
}

.hero-logo {
  width: 280px;
  margin-bottom: 3rem;
}

.gradient-text {
  font-size: 3.5rem;
  font-weight: 700;
  line-height: 1.2;
  margin-bottom: 1.5rem;
  background: linear-gradient(90deg, #A8B4FF, #CDB0E8, #FF91D5);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.hero-description {
  font-size: 1.25rem;
  color: #E0E0E0;
  max-width: 600px;
  margin: 0 auto 2.5rem;
}

.cta-button {
  background: linear-gradient(90deg, #A8B4FF, #FF91D5);
  color: white;
  padding: 1rem 2.5rem;
  font-size: 1.125rem;
  font-weight: 600;
  border: none;
  border-radius: 50px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.cta-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 32px rgba(168, 180, 255, 0.4);
}
</style>
```

**Header Navigation (Fondo Claro):**
```html
<header class="main-header">
  <nav class="navbar">
    <a href="/" class="logo-link">
      <img src="nexus-logo-light.svg" alt="Nexus" class="nav-logo" />
    </a>
    <ul class="nav-menu">
      <li><a href="#productos">Productos</a></li>
      <li><a href="#soluciones">Soluciones</a></li>
      <li><a href="#recursos">Recursos</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
    <button class="nav-cta">Comenzar</button>
  </nav>
</header>

<style>
.main-header {
  background: #FFFFFF;
  border-bottom: 1px solid #E8E8E8;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 2rem;
  max-width: 1400px;
  margin: 0 auto;
}

.nav-logo {
  height: 32px;
  width: auto;
}

.nav-menu {
  display: flex;
  gap: 2rem;
  list-style: none;
