# Aplicación de gestión de productos para e-commerce

Este proyecto es una aplicación frontend desarrollada en **JavaScript** que consume una **API externa** para mostrar productos de manera dinámica y permitir la interacción del usuario mediante un carrito de compras. Fue creado como ejercicio práctico para **reforzar conceptos fundamentales de JavaScript moderno**, programación asíncrona, POO y manipulación del DOM.

## Objetivo

Construir una aplicación web que:

- Obtenga productos desde una API externa mediante fetch.

- Renderice dinámicamente cada producto en el DOM.

- Permita agregar y quitar productos del carrito.

- Mantenga una experiencia interactiva, fluida y sin recargas de página.

- Consolide el uso de JavaScript ES6+ en un proyecto real.

## Funcionalidades

- Consumo de API externa: carga de productos mediante fetch y manejo de datos asíncronos.

- Programación orientada a objetos (POO): modelado de productos a través de una clase Producto.

- Renderizado dinámico: creación de elementos HTML desde JavaScript.

- Carrito de compras:

  Agregar productos.

  Quitar productos.

  Actualización automática del contador.

- Manejo de errores: mensajes controlados en caso de fallas del API.

- Interfaz modular: separación clara entre lógica, clases, DOM y eventos.

## Tecnologías utilizadas

- HTML5

- CSS3

- JavaScript (ES6+)

- Fetch API

- Git & GitHub

## Estructura

```
📦 proyecto-ecommerce
├── index.html
├── script.js
├── styles.css
└── assets/
```

## Cómo probar la aplicación

1. Clonar el repositorio:

```
git clone https://github.com/Luciano-Oviedo/Fake-ecommerce.git
```

2. Abrir el archivo `index.html` en el navegador.

3. Interactuar con la aplicación:

   - Los productos se cargarán automáticamente desde la API.

   - Puedes agregar y quitar productos del carrito.

   - Puedes ver el contenido de tu carrito.

   - El contador mostrará cuántos artículos fueron añadidos.
