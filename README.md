# 🎨 Lista Interactiva con CSS Avanzado

## 📌 Descripción

Este proyecto consiste en el desarrollo de una interfaz visual tipo lista interactiva utilizando CSS. Se aplican técnicas modernas de diseño como animaciones, efectos hover y diseño responsive para mejorar la experiencia del usuario.

## 🛠️ Tecnologías utilizadas

* HTML (estructura base)
* CSS (estilos, animaciones y diseño visual)

## 🧱 Estructura del proyecto

El diseño está organizado en varias secciones principales:

* **Reset CSS:** Eliminación de márgenes y paddings por defecto, y configuración de `box-sizing`.
* **Estilos globales:** Definición de tipografía, colores y comportamiento general del `body`.
* **Contenedor principal (`.infographic-container`):** Maneja el ancho y espaciado del contenido.
* **Encabezado (`.header-info`):** Contiene el título y descripción principal.
* **Lista interactiva (`.interactive-list`):** Organiza los elementos en columna utilizando Flexbox.
* **Elementos individuales (`.list-item` y `.item-wrapper`):** Representan cada ítem con diseño tipo tarjeta.

## ✨ Funcionalidades

* Diseño en forma de tarjetas con sombra y bordes redondeados
* Uso de Flexbox para organización del contenido
* Efectos hover que mejoran la interacción visual
* Transiciones suaves en múltiples elementos

## 🎯 Efectos y animaciones

### 🔄 Animación de íconos

Se implementa un efecto visual mediante pseudoelementos (`::before` y `::after`) que simulan un círculo animado:

* Un semicírculo rota al hacer hover
* Se utiliza `transform: rotate()` y `transition`

### 🌊 Línea ondulada animada

Se añade una línea decorativa debajo del título:

* Construida con SVG en formato Base64
* Animada mediante `@keyframes`
* Se activa al pasar el cursor sobre el elemento

### 🎯 Efectos hover

Al interactuar con los elementos:

* Se desplazan ligeramente (`translateX`)
* Cambia el color del texto
* Se modifica la sombra (`box-shadow`)
* Se activan animaciones en íconos y decoraciones

## 📱 Diseño Responsive

El proyecto sigue un enfoque **Mobile First**, adaptándose a diferentes dispositivos mediante media queries:

* En pantallas grandes:

  * Se incrementan tamaños de texto
  * Se amplían los espacios
  * Se escalan los íconos

## 🚀 Uso

Para visualizar el proyecto:

1. Crear un archivo `index.html`
2. Vincular o incluir este CSS
3. Abrir el archivo en un navegador web

## 🎯 Objetivo

Aplicar conceptos avanzados de CSS como:

* Flexbox
* Animaciones y transiciones
* Pseudoelementos
* Diseño responsive

## 👤 Autor

[Tu nombre aquí]
