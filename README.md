# 🎌 Plan de Aprendizaje: De Cero a Maestro del Desarrollo de Software

> *"El camino del ninja del código comienza con un solo `<tag>`"* 🥷

## 📋 Estructura General del Plan

- **Audiencia:** Adolescentes fans del anime japonés
- **Nivel inicial:** Cero experiencia
- **Objetivo final:** Nivel maestro/gurú en desarrollo de software
- **Idioma:** Español
- **Filosofía:** Aprender como un protagonista de shonen — cada capítulo es un nuevo arco argumental 💪

## 🗺️ Mapa del Camino (Roadmap)

**GitHub → HTML → CSS → JavaScript → TypeScript → Backend → Bases de Datos → DevOps → Maestría**

Cada etapa = un arco del anime con su propio villano (concepto difícil) y recompensa (habilidad nueva) 🏆

---

## ⚔️ ARCO 1 — GitHub: El Pergamino del Ninja

### 🎯 Objetivo

Aprender a guardar, versionar y compartir tu código como un verdadero shinobi.

### 📖 Teoría

**¿Qué es Git y GitHub?** Git es como el Sharingan de Sasuke — te permite ver y recordar cada versión de tu código. GitHub es la aldea donde guardas y compartes tus jutsu (proyectos).

**Conceptos clave:**

- **Repositorio (repo):** Tu carpeta de jutsu secretos
- **Commit:** Una foto del estado de tu código "guardé mi progreso como en un videojuego"
- **Branch (rama):** Una línea alterna de la historia, como en Steins;Gate ⏳
- **Merge:** Fusionar dos ramas, como la fusión de Goku y Vegeta en Dragon Ball
- **Pull Request (PR):** Pedir permiso para fusionar tu código al proyecto principal
- **Clone / Fork:** Copiar un repositorio para trabajar en él

**Flujo básico de trabajo:**

```bash
git init              # Crear un repositorio nuevo
git add .             # Preparar archivos para guardar
git commit -m "mensaje"  # Guardar con descripción
git push              # Subir a GitHub
git pull              # Descargar cambios
```

### 🛠️ Ejercicios Prácticos

- **Misión 1 — Crea tu cuenta:** Regístrate en GitHub con un nombre épico de anime
- **Misión 2 — Tu primer repo:** Crea un repositorio llamado `mi-primer-jutsu`
- **Misión 3 — Primer commit:** Crea un archivo `README.md` que diga quién eres y tu anime favorito
- **Misión 4 — Ramas paralelas:** Crea una rama llamada `feature/nueva-tecnica` y agrega contenido
- **Misión 5 — Fusión:** Haz merge de tu rama al main

### 🔗 Recursos

- [Documentación oficial de Git](https://git-scm.com/doc)
- [GitHub Skills (cursos interactivos)](https://skills.github.com)
- [Video tutorial en español](https://www.youtube.com/watch?v=mBYSUUnMt9M)
- [Visualizador interactivo de Git](https://learngitbranching.js.org/?locale=es_ES)
- [VS Code](https://www.youtube.com/watch?v=eurOEmEnwyg&list=PLg9145ptuAih53bphkhVmoCBECkkI-86R&index=3)

### 📊 Evaluación del Arco 1

| Criterio | Descripción | ✅ |
| --- | --- | --- |
| Cuenta GitHub creada | Perfil completo con foto/bio | ☐ |
| Repo creado | `mi-primer-jutsu` existe y es público | ☐ |
| README.md | Tiene contenido personal y anime favorito | ☐ |
| Commits realizados | Mínimo 3 commits con mensajes descriptivos | ☐ |
| Branch + Merge | Una rama creada y fusionada exitosamente | ☐ |

🏆 **Rango obtenido al completar: Genin del Código** 🍃

---

## 🌐 ARCO 2 — HTML: Los Cimientos del Mundo Digital

### 🎯 Objetivo

Construir la estructura de páginas web, como arquitecto de un mundo isekai.

### 📖 Teoría

**¿Qué es HTML?** HTML (HyperText Markup Language) es el esqueleto de toda página web. Piénsalo como el mundo de Sword Art Online — antes de tener gráficos y magia, alguien tuvo que construir la estructura del mundo.

**Estructura básica:**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Mundo Anime</title>
  </head>
  <body>
    <h1>¡Bienvenido a mi aldea ninja!</h1>
    <p>Este es mi primer jutsu HTML</p>
  </body>
</html>
```

**Etiquetas esenciales:**

| Etiqueta | Uso | Ejemplo anime |
| --- | --- | --- |
| `<h1>` a `<h6>` | Títulos | Nombre del arco argumental |
| `<p>` | Párrafos | Descripción del personaje |
| `<img>` | Imágenes | Foto del protagonista |
| `<a>` | Enlaces | Link al siguiente episodio |
| `<ul>` / `<ol>` | Listas | Lista de poderes especiales |
| `<div>` | Contenedor genérico | Sección del mundo |
| `<form>` | Formularios | Registro en la academia ninja |
| `<table>` | Tablas | Ranking de ninjas |
| `<nav>` | Navegación | Menú principal |
| `<header>` / `<footer>` | Cabecera y pie | Inicio y fin de episodio |

**HTML Semántico** — Usar las etiquetas correctas importa, como usar el jutsu correcto en el momento correcto:

```html
<article>   <!-- Un episodio completo -->
<section>   <!-- Una escena del episodio -->
<aside>     <!-- Información extra (como el narrador) -->
<main>      <!-- El contenido principal -->
```

**Formularios** — El sistema de registro de la academia:

```html
<form action="/registro" method="POST">
  <label for="nombre">Nombre del ninja:</label>
  <input type="text" id="nombre" name="nombre" required>

  <label for="aldea">Aldea:</label>
  <select id="aldea" name="aldea">
    <option value="konoha">Konoha</option>
    <option value="suna">Suna</option>
  </select>

  <button type="submit">¡Inscribirse!</button>
</form>
```

### 🛠️ Ejercicios Prácticos

- **Misión 1:** Crea una página `index.html` con tu anime favorito como tema
- **Misión 2:** Agrega una lista de tus 5 personajes favoritos con descripción
- **Misión 3:** Inserta imágenes de personajes usando `<img>` con alt descriptivo
- **Misión 4:** Crea una tabla con el ranking de los personajes más fuertes
- **Misión 5 (Boss):** Construye un sitio de 3 páginas enlazadas entre sí:
  - `index.html` — Página principal
  - `personajes.html` — Lista de personajes
  - `contacto.html` — Formulario de contacto
- **Misión 6:** Sube todo al repositorio de GitHub creado en el Arco 1

### 🔗 Recursos

- [MDN Web Docs HTML (español)](https://developer.mozilla.org/es/docs/Web/HTML)
- [W3Schools HTML](https://www.w3schools.com/html/)
- [HTML y CSS (video)](https://www.youtube.com/watch?v=XqFR2lqBYPs)
- [Validador de HTML](https://validator.w3.org)

### 📊 Evaluación del Arco 2

| Criterio | Descripción | ✅ |
| --- | --- | --- |
| Estructura básica | DOCTYPE, html, head, body correctos | ☐ |
| Semántica | Uso correcto de header, main, footer, etc. | ☐ |
| Multimedia | Al menos 3 imágenes con atributo alt | ☐ |
| Navegación | Menú con links entre páginas | ☐ |
| Formulario | Formulario funcional con validación básica | ☐ |
| GitHub | Proyecto subido al repositorio | ☐ |
| Completar tutorial [html](https://www.w3schools.com/html/html_intro.asp) | Crear cuenta y mostrar progreso | ☐ |


🏆 **Rango obtenido al completar: Arquitecto del Mundo Digital** 🏗️

---

## 🎨 ARCO 3 — CSS: El Arte del Estilo y el Poder Visual

### 🎯 Objetivo

Dar vida visual a tus páginas web, como un artista de anime que colorea los storyboards.

### 📖 Teoría

**¿Qué es CSS?** CSS (Cascading Style Sheets) es el estilo visual de tu página. Si HTML es el esqueleto, CSS es la ropa, el color de cabello y el aura de poder de tu personaje — como diseñar a tu propio protagonista de anime ✨

**Formas de aplicar CSS:**

```html
<!-- 1. Inline (no recomendado, como gritar jutsu en voz alta) -->
<p style="color: red;">Texto rojo</p>

<!-- 2. Internal (en el <head>) -->
<style>
  p { color: blue; }
</style>

<!-- 3. External (la forma correcta, como un grimorio separado) -->
<link rel="stylesheet" href="styles.css">
```

**Selectores** — Cómo apuntar a tus objetivos:

```css
/* Por etiqueta */
h1 { color: orange; }

/* Por clase (.) — como un clan ninja */
.personaje { font-size: 18px; }

/* Por ID (#) — único como el protagonista */
#naruto { background-color: yellow; }

/* Combinados */
.tarjeta:hover { transform: scale(1.05); }
```

**El Modelo de Caja (Box Model)** — El cuerpo de tu elemento:

```css
.caja {
  width: 200px;         /* Ancho */
  height: 100px;        /* Alto */
  padding: 10px;        /* Espacio interno (como el chakra interior) */
  border: 2px solid black; /* Borde (el aura visible) */
  margin: 20px;         /* Espacio externo (distancia entre personajes) */
}
```

**Flexbox** — El jutsu de alineación:

```css
.contenedor {
  display: flex;
  justify-content: center;   /* Alinear horizontalmente */
  align-items: center;       /* Alinear verticalmente */
  gap: 20px;                 /* Espacio entre elementos */
  flex-wrap: wrap;           /* Saltar a la siguiente línea si no caben */
}
```

**CSS Grid** — El jutsu de cuadrícula:

```css
.grid-aldea {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 columnas iguales */
  grid-gap: 15px;
}
```

**Animaciones** — Los efectos especiales del anime:

```css
@keyframes poder-especial {
  0%   { transform: scale(1); opacity: 1; }
  50%  { transform: scale(1.2); opacity: 0.8; }
  100% { transform: scale(1); opacity: 1; }
}

.boton-jutsu {
  animation: poder-especial 2s infinite;
}
```

**Diseño Responsivo** — Tu página en cualquier pantalla:

```css
/* Mobile first */
.tarjeta { width: 100%; }

/* Tablet */
@media (min-width: 768px) {
  .tarjeta { width: 50%; }
}

/* Desktop */
@media (min-width: 1024px) {
  .tarjeta { width: 33%; }
}
```

### 🛠️ Ejercicios Prácticos

- **Misión 1:** Aplica colores y tipografías al proyecto del Arco 2 usando Google Fonts
- **Misión 2:** Crea tarjetas de personajes usando Flexbox
- **Misión 3:** Diseña un layout de 3 columnas con CSS Grid para el ranking
- **Misión 4:** Agrega animaciones a los botones y hover effects a las tarjetas
- **Misión 5:** Haz el sitio completamente responsivo (mobile, tablet, desktop)
- **Misión 6 (Boss):** Crea una página de perfil de personaje estilo anime con:
  - Header con imagen de fondo y efecto parallax
  - Tarjetas de habilidades animadas
  - Barra de estadísticas (como en los RPG de anime)
  - Totalmente responsiva

### 🔗 Recursos

- [MDN CSS (español)](https://developer.mozilla.org/es/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com)
- [Flexbox Froggy (juego)](https://flexboxfroggy.com/#es)
- [Grid Garden (juego)](https://cssgridgarden.com/#es)
- [Google Fonts](https://fonts.google.com)
- [Animista (generador de animaciones)](https://animista.net)
- [Flexbox](https://www.youtube.com/watch?v=iwFEc6I8wSA)

### 📊 Evaluación del Arco 3

| Criterio | Descripción | ✅ |
| --- | --- | --- |
| Selectores | Uso correcto de clases, IDs y selectores combinados | ☐ |
| Box Model | Padding, margin y border aplicados correctamente | ☐ |
| Flexbox | Layout con Flexbox funcional | ☐ |
| Grid | Al menos una sección con CSS Grid | ☐ |
| Animaciones | Mínimo 2 animaciones CSS | ☐ |
| Responsivo | Se ve bien en móvil y desktop | ☐ |
|Completar Flexbox Froggy (juego)| Todos los pasos| ☐ |
|Grid Garden (juego)| Todos los pasos| ☐ |


🏆 **Rango obtenido al completar: Artista del Chakra Visual** 🎨

