<!-- No borrar o modificar -->
[Inicio](./index.md)

# Actividad: Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

![Tabla](https://firebasestorage.googleapis.com/v0/b/desarrollo-software-nelson.appspot.com/o/tabla%20ejemplo.jpg?alt=media&token=ebc69b5d-9d49-4735-8512-159f11c29743&_gl=1*12g1w0g*_ga*MTcwMTI3Mzk1MS4xNjk2MzQ2MTUy*_ga_CW55HF8NVT*MTY5Njc0MTgzMi42LjEuMTY5Njc0MTg4MC4xMi4wLjA.)

## SOLUCIÓN
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body>
  <table border="1" cellpadding="5" cellspacing="10">
    <thead>
      <tr>
        <th>CÓDIGO</th>
        <th>NOMBRE</th>
        <th>DESCRIPCIÓN</th>
        <th>PRECIO</th>
        <th>STOCK</th>
        <th>FECHA DE CREACIÓN</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">001</td>
        <td rowspan="2">BUÑUELOS</td>
        <td> CON BOCADILLO </td>
        <td>$1500</td>
        <td>50</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>CON QUESO MOZZARELLA</td>
        <td>$1000</td>
      </tr>

      <tr>
        <td rowspan="2">002</td>
        <td rowspan="2">PASTELES</td>
        <td> HAWAIANO </td>
        <td>$3500</td>
        <td>30</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>CON JAMÓN Y QUESO</td>
        <td>$1000</td>
      </tr>

      <tr>
        <td rowspan="2">003</td>
        <td rowspan="2">PAN GRANDE</td>
        <td> QUESO </td>
        <td>$12000</td>
        <td>30</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>ALIÑADO</td>
        <td>$11000</td>
      </tr>

      <tr>
        <td rowspan="2">004</td>
        <td rowspan="2">PANDEQUESO</td>
        <td> GRANDE </td>
        <td>$2000</td>
        <td>30</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>PEQUEÑO</td>
        <td>$5000</td>
      </tr>

      <tr>
        <td rowspan="2">005</td>
        <td rowspan="2">TORTAS DE CARNE</td>
        <td> GRANDE </td>
        <td>$8000</td>
        <td>15</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>PESECADO</td>
        <td>$6000</td>
      </tr>

      <tr>
        <td rowspan="2">006</td>
        <td rowspan="2">PAPAS RELLENAS GRANDES</td>
        <td> GRANDE </td>
        <td>$3000</td>
        <td>40</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>PEQUEÑAS</td>
        <td>$1500</td>
      </tr>

      <tr>
        <td rowspan="2">007</td>
        <td rowspan="2">EMPANADAS</td>
        <td> PAPA Y CARNE </td>
        <td>$3000</td>
        <td>40</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>ARROZ Y CARNE</td>
        <td>$2500</td>
      </tr>

      <tr>
        <td rowspan="2">008</td>
        <td rowspan="2">DESAYUNO TRADICIONAL</td>
        <td> PAPA Y CARNE </td>
        <td>$12000</td>
        <td>25</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>CALENTADO</td>
        <td>$15000</td>
      </tr>

      <tr>
        <td rowspan="2">009</td>
        <td rowspan="2">DESAYUNO TRADICIONAL</td>
        <td> PAPA Y CARNE </td>
        <td>$12000</td>
        <td>25</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>CALENTADO</td>
        <td>$15000</td>
      </tr>

      <tr>
        <td rowspan="2">010</td>
        <td rowspan="2">ALMUERZOS</td>
        <td> BANDEJA PAISA</td>
        <td>$20000</td>
        <td>25</td>
        <td>28 de Agosto</td>
      </tr>

      <tr>
        <td>EJECUTIVO</td>
        <td>$17000</td>
      </tr>


    </tbody>
  </table>
</body>

</html>
```






