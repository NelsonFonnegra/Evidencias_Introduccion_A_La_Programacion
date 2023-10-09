<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 

# Actividad: Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
-  Nombre del producto
-  Cantidad
-  Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

## SOLUCIÓN

```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Pedido</title>
</head>

<body>
    <h1>Formulario de Pedido</h1>

    <form action="#" method="post">

        <label for="producto">Nombre del Producto:</label>
        <input type="text" id="producto" name="producto" required><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br>

        <label for="precioUnitario">Precio Unitario:</label>
        <input type="number" id="precioUnitario" name="precioUnitario" required><br>

        <label for="precioTotal">Precio Total:</label>
        <input type="number" id="precioTotal" name="precioTotal" readonly><br>

        <label for="direccion">Dirección de Envío:</label>
        <input type="text" id="direccion" name="direccion" required><br>

        <label for="nombre">Nombre de Contacto:</label>
        <input type="text" id="nombre" name="nombre" required><br>

        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="telefono">Número de Teléfono:</label>
        <input type="tel" id="telefono" name="telefono" required><br>

        <label for="metodoPago">Método de Pago:</label>
        <select id="metodoPago" name="metodoPago" required>
            <option value="tarjeta">Tarjeta de Crédito</option>
            <option value="paypal">PayPal</option>
            <option value="efectivo">Efectivo</option>
        </select><br>

        <label for="fechaEntrega">Fecha de Entrega:</label>
        <input type="date" id="fechaEntrega" name="fechaEntrega" required><br>

        <label for="comentarios">Comentarios:</label><br>
        <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>

</body>

</html>
```





