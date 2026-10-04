# CSS-CHEATSHEET
Cheat sheet of css
# Cheat Sheet de CSS

## 1. Sintaxis básica

```css
selector {
    propiedad: valor;
}
```

Ejemplo:

```css
h1 {
    color: blue;
    font-size: 32px;
}
```

---

# 2. Selectores

### Etiqueta

```css
p {
    color: red;
}
```

### Clase

```css
.texto {
    color: green;
}
```

```html
<p class="texto">Hola</p>
```

### ID

```css
#titulo {
    color: blue;
}
```

```html
<h1 id="titulo">Título</h1>
```

### Universal

```css
* {
    margin: 0;
    padding: 0;
}
```

### Descendiente

```css
div p {
    color: purple;
}
```

### Hijo directo

```css
div > p {
    color: orange;
}
```

### Múltiples selectores

```css
h1, h2, h3 {
    font-family: Arial;
}
```

---

# 3. Colores

```css
color: red;
color: #ff0000;
color: rgb(255,0,0);
color: rgba(255,0,0,0.5);
```

---

# 4. Texto

```css
color: black;
font-size: 18px;
font-family: Arial, sans-serif;
font-weight: bold;
font-style: italic;
text-align: center;
text-decoration: underline;
line-height: 1.5;
letter-spacing: 2px;
```

---

# 5. Fondo

```css
background-color: lightblue;
background-image: url("imagen.jpg");
background-repeat: no-repeat;
background-size: cover;
background-position: center;
```

---

# 6. Tamaños

```css
width: 300px;
height: 200px;

max-width: 100%;
min-height: 100px;
```

Unidades comunes:

```css
px
%
vw
vh
em
rem
```

---

# 7. Margin y Padding

```css
margin: 20px;
padding: 20px;
```

### Direcciones

```css
margin-top: 10px;
margin-right: 20px;
margin-bottom: 10px;
margin-left: 20px;
```

### Atajo

```css
margin: 10px 20px 30px 40px;
```

Orden:

```text
arriba derecha abajo izquierda
```

---

# 8. Bordes

```css
border: 2px solid black;
border-radius: 10px;
```

Tipos:

```css
solid
dashed
dotted
double
```

---

# 9. Display

```css
display: block;
display: inline;
display: inline-block;
display: flex;
display: grid;
display: none;
```

---

# 10. Position

```css
position: static;
position: relative;
position: absolute;
position: fixed;
position: sticky;
```

Ejemplo:

```css
position: absolute;
top: 20px;
left: 50px;
```

---

# 11. Flexbox

Contenedor:

```css
display: flex;
```

Dirección:

```css
flex-direction: row;
flex-direction: column;
```

Alineación:

```css
justify-content: center;
align-items: center;
```

Espaciado:

```css
gap: 20px;
```

Ejemplo:

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

---

# 12. CSS Grid

```css
display: grid;
grid-template-columns: 1fr 1fr 1fr;
gap: 20px;
```

Ejemplo:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

---

# 13. Pseudoclases

Hover:

```css
button:hover {
    background: red;
}
```

Focus:

```css
input:focus {
    border: 2px solid blue;
}
```

Primer hijo:

```css
li:first-child {
    color: red;
}
```

Último hijo:

```css
li:last-child {
    color: blue;
}
```

---

# 14. Transiciones

```css
transition: all 0.3s ease;
```

Ejemplo:

```css
button {
    transition: 0.3s;
}

button:hover {
    transform: scale(1.1);
}
```

---

# 15. Transformaciones

```css
transform: scale(1.2);
transform: rotate(45deg);
transform: translateX(100px);
transform: translateY(50px);
```

---

# 16. Sombras

### Texto

```css
text-shadow: 2px 2px 4px gray;
```

### Caja

```css
box-shadow: 0 0 10px gray;
```

---

# 17. Overflow

```css
overflow: hidden;
overflow: scroll;
overflow: auto;
```

---

# 18. Z-Index

```css
position: relative;
z-index: 100;
```

Mayor número = más arriba.

---

# 19. Media Queries (Responsive)

```css
@media (max-width: 768px) {
    body {
        background: lightgray;
    }
}
```

---

# 20. Variables CSS

```css
:root {
    --color-principal: blue;
}
```

Uso:

```css
h1 {
    color: var(--color-principal);
}
```

---

# 21. Animaciones

```css
@keyframes mover {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(100px);
    }
}
```

Uso:

```css
div {
    animation: mover 2s infinite;
}
```

---

# 22. Centrar un elemento (muy usado)

### Con Flexbox

```css
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
```

### Con Grid

```css
display: grid;
place-items: center;
height: 100vh;
```

---

# 23. Reset CSS básico

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

---

# 24. Propiedades que más usan los programadores profesionales

```css
display
position
flex
grid
gap
padding
margin
width
height
max-width
color
background
border-radius
box-shadow
font-size
font-weight
transition
transform
overflow
z-index
```
