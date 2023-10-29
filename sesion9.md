<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

# Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

3. En el archivo CSS, agrega el siguiente código:
```CSS
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```

4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.

- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
```CSS
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border: Agrega un borde de 5 píxeles de color rojo.
```CSS
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border-radius: Agrega un radio de esquina de 10 píxeles.
```CSS
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
```CSS
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```

### Preguntas:
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado? 

## SOLUCIÓN

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento">PRUEBAS DE MARGEN</div>
  </div>

</body>
</html>
```

```CSS
body {
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.contenedor {
  background-color: aqua;
  width: 200px;
  height: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  width: 100px;
  height: 100px;
  margin: 10px;
}

```
1. Margin:
La propiedad margin en CSS se utiliza para definir el espacio entre los bordes de un elemento y los elementos adyacentes (otros elementos en el mismo documento). Puedes establecer márgenes para los cuatro lados (arriba, derecha, abajo e izquierda) individualmente o usar valores abreviados para definirlos simultáneamente.

2. Padding:
La propiedad padding en CSS se utiliza para definir el espacio entre el contenido de un elemento y su borde. Al igual que con margin, puedes establecer el relleno para los cuatro lados individualmente o usar valores abreviados.

3. Border:
La propiedad border en CSS se utiliza para definir el borde de un elemento. Puedes especificar el ancho, el estilo y el color del borde.

4. Border-Radius:
La propiedad border-radius en CSS se utiliza para establecer el radio de las esquinas de un elemento con borde. Esto se utiliza para hacer esquinas redondeadas.

5. Unidades de Medida para Propiedades de Espaciado:

- Pixels (px): Especifica un número de píxeles.
- Em: Relativo a la fuente del elemento.
- Porcentaje (%): Relativo al elemento padre.
- Rem: Relativo al tamaño de la fuente del elemento raíz (<html>).
- Viewport Width (vw): Relativo al 1% del ancho del viewport.
- Viewport Height (vh): Relativo al 1% de la altura del viewport.

Estas unidades se pueden utilizar tanto para margin como para padding.