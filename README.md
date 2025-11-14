# 🚀 Proyecto Flexbox

¡Bienvenido/a a este repositorio dedicado a **Flexbox** en CSS! Aquí aprenderás los conceptos fundamentales de Flexbox y cómo aplicarlos para crear diseños web modernos, flexibles y responsivos. 

## 📦 ¿Qué es Flexbox?

Flexbox (Flexible Box) es un módulo de CSS que facilita la creación de layouts (diseños) unidimensionales, permitiendo distribuir el espacio entre los elementos de una interfaz y alinear el contenido de manera eficiente, incluso cuando su tamaño es desconocido o dinámico.

## 🎯 Objetivo del repositorio

El objetivo de este repositorio es mostrar, mediante ejemplos prácticos, cómo utilizar Flexbox para organizar y alinear elementos en una página web. Aquí encontrarás un ejemplo de una galería de tarjetas alineadas y distribuidas usando Flexbox.

## 🗂️ Estructura del repositorio

- `index.html`: Contiene la estructura HTML de la página y los elementos a organizar.
- `css/style.css`: Incluye los estilos CSS, donde se aplican las propiedades de Flexbox.

## 🧑‍💻 Principales propiedades de Flexbox

Las propiedades más importantes que se utilizan en este proyecto son:

- `display: flex;` — Activa el contexto Flexbox en el contenedor.
- `flex-direction` / `flex-flow` — Define la dirección de los elementos (fila, columna, o ambas con wrap).
- `justify-content` — Alinea los elementos horizontalmente (inicio, centro, fin, espacio entre, etc.).
- `align-items` — Alinea los elementos verticalmente.
- `gap` — Espacio entre los elementos.
- `flex` — Permite que los elementos crezcan, encojan y tengan un tamaño base.

## 📝 Ejemplo aplicado en este repositorio

```css
.container {
  display: flex;
  flex-flow: row wrap;
  gap: 5px;
  justify-content: space-evenly;
  border: red solid 1px;
  width: 100%;
  max-width: 1000px;
}

.item {
  flex: 1 1 150px;
  background: #09f;
  /* ...otros estilos... */
}
```

- `.container` es el contenedor flex que organiza las tarjetas en filas y permite que se ajusten automáticamente al espacio disponible.
- Cada `.item` es un elemento flexible que puede crecer o reducirse según el espacio.

## 👀 Visualización

El resultado es una galería de tarjetas que se adapta automáticamente al tamaño de la pantalla, manteniendo el espacio y la alineación entre ellas.

## 📚 Recursos recomendados

- [Guía de Flexbox en MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [Flexbox Froggy (juego interactivo)](https://flexboxfroggy.com/#es)

---

¡Explora el código, experimenta con las propiedades y domina Flexbox! 💪🎨
