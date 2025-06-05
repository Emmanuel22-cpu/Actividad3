
#  Proyecto: Formulario de Registro 

##  Descripción General

Este proyecto es una página web desarrollada en **HTML, CSS y JavaScript** que presenta un formulario de registro completo. Fue diseñado como una práctica o ejemplo educativo para aprender el uso de múltiples tipos de entradas (`input`, `select`, `textarea`, etc.) y aplicar estilos personalizados con CSS puro, sin usar frameworks externos.


### 1. `index.html`

Este archivo contiene:

- Un **formulario HTML** con los siguientes campos:
  - Texto (nombre)
  - Correo electrónico
  - Número (edad)
  - Selección desplegable (ciudad)
  - Radio buttons (nivel de experiencia)
  - Checkbox (aceptar términos)
  - Área de texto (comentarios)
  - Campos avanzados (`password`, `color`, `date`, `datetime-local`, `time`, `month`, `week`, `url`, `file`, `search`, `range`)
  - Campo oculto (`hidden`)

- **Estilos CSS** embebidos en el `<head>` para mejorar la apariencia del formulario, incluyendo diseño responsivo, colores personalizados, gradientes y sombras.

- **JavaScript básico**:
  - Muestra una alerta cuando el formulario se envía correctamente.
  - Restaura estilos y valores predeterminados al hacer clic en el botón “Limpiar”.

### 2. `settings.json`

Archivo de configuración de Live Server, indicando que el servidor debe correr en el puerto `5501`. Es útil para desarrolladores que están probando la página localmente con una extensión como **Live Server en Visual Studio Code**.

---

##  ¿Qué se aprende con este código?

- Cómo usar los distintos tipos de entradas de formulario en HTML5.
- Validaciones simples con atributos HTML (`required`, `pattern`, `min`, `max`).
- Uso de `CSS` para personalizar formularios.
- Agregar interactividad mínima con `JavaScript`.
- Cómo estructurar un proyecto web básico y amigable para el usuario.

---

##  ¿Qué puedes hacer con este código?

- Adaptarlo para cualquier formulario real (registro de usuarios, encuestas, etc.).
- Integrarlo con bases de datos o backend en el futuro.
- Usarlo como base para aprender más sobre eventos, validaciones y manipulación del DOM con JavaScript.

---

##  Requisitos para probarlo localmente

1. Instalar la extensión **Live Server** en Visual Studio Code.
2. Abrir el proyecto y ejecutar con Live Server en el puerto 5501 (ya configurado).
3. También puedes abrir directamente `index.html` en tu navegador.
