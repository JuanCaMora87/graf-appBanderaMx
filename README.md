<<<<<<< HEAD

# Instituto Tecnológico de Pachuca

## Materia: Graficación

## Tema: 1.4 Práctica Integradora – Bandera de México

## Autor: Juan Carlos Mora Cisneros

### Fecha: 19 de mayo de 2026

---

# Prompt 1 – Creación de la estructura principal

Desarrolla una aplicación web utilizando tres archivos separados:

* `index.html`
* `style.css`
* `script.js`

La aplicación debe mostrar la bandera de México utilizando tres franjas verticales con los colores:

* Verde
* Blanco
* Rojo

El diseño debe implementarse utilizando Flexbox para mantener la bandera centrada en la pantalla.

---

# Prompt 2 – Controles para manipular colores

Agregar dos controles deslizantes (`input type="range"`):

* Uno para modificar dinámicamente el color verde.
* Uno para modificar dinámicamente el color rojo.

Cada control debe actualizar el color en tiempo real mediante JavaScript y mostrar debajo el código hexadecimal correspondiente.

---

# Prompt 3 – Diseño visual con CSS

Aplicar estilos en `style.css` para:

* Centrar el contenido de la página.
* Definir el tamaño y proporciones de la bandera.
* Configurar los colores iniciales:

  * Verde
  * Blanco
  * Rojo
* Alinear los controles horizontalmente en la parte superior.
* Agregar un footer con el nombre del alumno y número de control debajo de la bandera.

---

# Prompt 4 – Incorporación del Escudo Nacional

Insertar el escudo nacional de México en la sección blanca utilizando una imagen local llamada:

`escudo.png`

La imagen debe mantenerse centrada vertical y horizontalmente utilizando Flexbox.

---

# Prompt 5 – Ajuste del tamaño del escudo

Para aumentar el tamaño del escudo sin perder su proporción, se puede utilizar la siguiente regla CSS:

```css
.blanco img {
    width: 220px;
    height: auto;
}
```
