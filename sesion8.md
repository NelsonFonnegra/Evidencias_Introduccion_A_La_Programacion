<!-- No borrar o modificar -->
[Inicio](./index.md)

# SESIÓN 8

## Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

### Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado ```<header>```
- Tres párrafos ```<p>```
- Una imagen ```<img>```
- Un pie de página ```<footer>```

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados ```<h1>```
- Color azul a los párrafos ```<p>```
- Borde grueso negro a la imagen ```<img>```

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un ```<div>```
- Centrar el contenido de la sección ```<section>```

## SOLUCIÓN`



HTML:

```html

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad de Estilos CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Desarrolladores de Software</h1>
    </header>

    <section>
        <p>Un desarrollador de software juega un papel fundamental en la era digital actual por varias razones cruciales. En primer lugar, su importancia radica en su capacidad para traducir ideas y necesidades humanas en aplicaciones y programas informáticos. Vivimos en un mundo impulsado por la tecnología, donde las aplicaciones móviles, el software empresarial y las plataformas en línea son esenciales para nuestras vidas diarias y el funcionamiento de las empresas. Los desarrolladores de software son los arquitectos detrás de estas soluciones, creando productos que mejoran la eficiencia, automatizan tareas y permiten la comunicación y la colaboración en todo el mundo.</p>
        <p>En segundo lugar, la demanda constante de desarrolladores de software se debe a la naturaleza siempre cambiante y evolutiva de la tecnología. Los avances en inteligencia artificial, computación en la nube, Internet de las cosas y otras áreas requieren mentes creativas y habilidades técnicas para aprovechar estas innovaciones y desarrollar aplicaciones que aprovechen al máximo sus capacidades. Un desarrollador competente no solo tiene habilidades en lenguajes de programación y tecnologías, sino también la capacidad de aprender continuamente y adaptarse a nuevos desafíos tecnológicos.</p>
        <p>En tercer lugar, la seguridad digital es una preocupación creciente en la era digital, y los desarrolladores de software desempeñan un papel crucial en este campo. Es vital que los programas y aplicaciones sean seguros y estén protegidos contra amenazas cibernéticas. Los desarrolladores deben escribir código resistente y estar al tanto de las mejores prácticas de seguridad para garantizar que los sistemas informáticos sean robustos y protegidos contra posibles ataques.</p>
        <div>
            <p>En resumen, la importancia de un desarrollador de software radica en su capacidad para crear soluciones tecnológicas innovadoras, adaptarse a los cambios tecnológicos rápidos y garantizar la seguridad digital en un mundo cada vez más digitalizado y dependiente de la tecnología. Su habilidad para transformar ideas en realidad digital hace que sean esenciales en nuestra sociedad moderna.</p>
        </div>
    </section>

    <img src="https://firebasestorage.googleapis.com/v0/b/desarrollo-software-nelson.appspot.com/o/metodolog%C3%ADas-de-desarrollo-de-software.jpeg?alt=media&token=60069a60-0997-4998-9a5d-480de169fe9e&_gl=1*1rjr2go*_ga*MTcwMTI3Mzk1MS4xNjk2MzQ2MTUy*_ga_CW55HF8NVT*MTY5Njg4Mzc2OC44LjEuMTY5Njg4NDI4OS40My4wLjA" alt="Descripción de la imagen">

    <footer>
        <p>Nelson Fonnegra</p>
    </footer>
</body>

</html>
```
CSS:

```CSS

/* Estilos usando selectores de etiqueta */
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 2px solid black;
}

/* Estilos usando selectores de clase */
.destacado {
    color: green;
}

.grande {
    font-size: 18px;
}

/* Estilos usando selectores de ID */
#principal {
    color: yellow;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

#sombras {
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

/* Estilos usando selectores descendientes */
section div p {
    color: gray;
}

section {
    text-align: center;
}
```



