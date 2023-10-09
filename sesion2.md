<!-- No borrar o modificar -->
[Inicio](./index.md)

# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

1. Index o página de inicio
2. Acerca
3. Contacto

## Solución

### 1. Página de Inicio

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<title>MI PRIMER SITIO WEB</title>
<head>
<body>
    <header>
        <h1> APRENDE MÚSICA CON NELSON</h1>
    </header>
    <nav>
        <a href="ACERCA.HTML">ACERCA</a>
        <a href="CONTACTO.HTML">CONTACTO</a>
    </nav>

<main>
    <P>Bienvenidos a mi sitio sobre música y tecnología.</P>
    <p>Aquí encontraran información sobre nuestra academia y las nuevas tendencias sobre tecnología y música.</p>
</main>

<footer>
    <p>Copyright 2023 - Nelson Fonnegra</p>
    <p>nelsonfonnegra@hotmail.com</p>
</footer>
</body>
</html>
```
### 2. Acerca
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SOBRE NOSOTROS</title>
</head>

<body>

    <header>
        <h1>Nuestra Academia Musical</h1>
    </header>

    <nav>
        <a href="PÁGINA DE INICIO.html">INICIO</a>
        <a href="CONTACTO.HTML">CONTACTO</a>
    </nav>

    <section>
        <h2>Historia</h2>
        <p>Fundada en 2023...</p>
        <article>
            <h3>Misión y Visión</h3>
            <p>Nuestra Misión es ...</p>
        </article>
    </section>

<footer>
    <p>Copyright 2023 - Nelson Fonnegra</p>
</footer>
    
</body>
</html>
```
### 3. Contacto
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACTO</title>
</head>

<body>
    <HEader>
        <H1>CONTACTO</H1>
    </HEader>

    <NAv>
        <a href="PÁGINA DE INICIO.html">INICIO</a>
        <a href="ACERCA.HTML">ACERCA</a>
    </NAv>
    <main>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" <br>

            <label for="email">Email:</label>
            <input type="email" id="email" <br>

            <label for="mensaje">Mensaje:</label>
            <input type="mensaje"></textarea><br>

            <input type="submit" value="Enviar">
        </form>

        <aside>
            <h3>Ubicación</h3>
            <p>Calle 41 # 59 BB 35</p>
        </aside>
    </main>

    <footer>
        <p>Copyright 2023 - Nelson Fonnegra</p>
    </footer>
</body>

</htm



