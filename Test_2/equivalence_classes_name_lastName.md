# Clases de equivalencia: horario de solicitud de taxi para la identificación de la velocidad (parámetro necesario para el cálculo de la duración y el costo del viaje)

<table>
  <tr>
    <th>Grupo de comprobaciones</th>
    <th>Nombre de la clase</th>
    <th>Límites</th>
    <th>Datos de prueba dentro de la clase</th>
    <th>Datos de prueba en los límites</th>
    <th>Clarificación y optimización</th>
  </tr>
  <!-- Nombre -->
  <!--  -->
  <tr>
    <td rowspan="17">Nombre</td>
    <td rowspan="3">Longitud del texto de 0 a 1 carácter</td>
    <td rowspan="3">0-1</td>
    <td rowspan="3"></td>
    <td>0 -> String vacio</td>
    <td rowspan="3">0 -> String vacio<br>1 -> S</td>
  </tr>
  <tr>
    <td>1 -> S</td>
  </tr>
  <tr>
    <td>2 -> Sa</td>
  </tr>
  <!--  -->
  <tr>
    <td rowspan="6">Longitud del texto de 2 a 14 caracteres</td>
    <td rowspan="6">2-14</td>
    <td rowspan="6">10 -> Sam Albert</td>
    <td>2 -> Sa</td>
    <td rowspan="6">2 -> Sa<br>14 -> Sam Albertosca<br>3-> Sam<br>13-> Sam Albertosc</td>
  </tr>
  <tr>
    <td>14 -> Sam Albertosca</td>
  </tr>
  <tr>
    <td>1 -> S</td>
  </tr>
  <tr>
    <td>15 -> Sam Albertoscas</td>
  </tr>
  <tr>
    <td>3-> Sam</td>
  </tr>
  <tr>
    <td>13-> Sam Albertosc</td>
  </tr>
  <!--  -->
  <tr>
    <td rowspan="3">Longitud del texto de 15 a más caracteres</td>
    <td rowspan="3">15 - +oo</td>
    <td rowspan="3">20 -> Sam Albertoscassssss</td>
    <td>15-> Sam Albertoscas</td>
    <td rowspan="3">15-> Sam Albertoscas<br>16-> Sam Albertoscass</td>
  </tr>
  <tr>
    <td>14 -> Sam Albertosca</td>
  </tr>
  <tr>
    <td>16-> Sam Albertoscass</td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio en el medio</td>
    <td></td>
    <td>Sam Albert</td>
    <td></td>
    <td></td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio al inicio</td>
    <td></td>
    <td>_Sam</td>
    <td></td>
    <td>_Sam</td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio al final</td>
    <td></td>
    <td>Sam_</td>
    <td></td>
    <td>Sam_</td>
  </tr>
  <!--  -->
  <tr>
    <td>Guiones</td>
    <td></td>
    <td>Sam-Albert</td>
    <td></td>
    <td>Sam-Albert</td>
  </tr>
  <!--  -->
  <tr>
    <td>Caracteres de otro idioma</td>
    <td></td>
    <td>山姆</td>
    <td></td>
    <td>山姆</td>
  </tr>
  <!-- Intermedio -->
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <!-- Apellido -->
  <!--  -->
  <tr>
    <td rowspan="17">Apellido</td>
    <td rowspan="3">Longitud del texto de 0 a 1 carácter</td>
    <td rowspan="3">0-1</td>
    <td rowspan="3"></td>
    <td>0 -> String vacio</td>
    <td rowspan="3">0 -> String vacio<br>1 -> S</td>
  </tr>
  <tr>
    <td>1 -> S</td>
  </tr>
  <tr>
    <td>2 -> Sa</td>
  </tr>
  <!--  -->
  <tr>
    <td rowspan="6">Longitud del texto de 2 a 14 caracteres</td>
    <td rowspan="6">2-14</td>
    <td rowspan="6">10 -> Sam Albert</td>
    <td>2 -> Sa</td>
    <td rowspan="6">2 -> Sa<br>14 -> Sam Albertosca<br>3-> Sam<br>13-> Sam Albertosc</td>
  </tr>
  <tr>
    <td>14 -> Sam Albertosca</td>
  </tr>
  <tr>
    <td>1 -> S</td>
  </tr>
  <tr>
    <td>15 -> Sam Albertoscas</td>
  </tr>
  <tr>
    <td>3-> Sam</td>
  </tr>
  <tr>
    <td>13-> Sam Albertosc</td>
  </tr>
  <!--  -->
  <tr>
    <td rowspan="3">Longitud del texto de 15 a más caracteres</td>
    <td rowspan="3">15 - +oo</td>
    <td rowspan="3">20 -> Sam Albertoscassssss</td>
    <td>15-> Sam Albertoscas</td>
    <td rowspan="3">15-> Sam Albertoscas<br>16-> Sam Albertoscass</td>
  </tr>
  <tr>
    <td>14 -> Sam Albertosca</td>
  </tr>
  <tr>
    <td>16-> Sam Albertoscass</td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio en el medio</td>
    <td></td>
    <td>Sam Albert</td>
    <td></td>
    <td></td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio al inicio</td>
    <td></td>
    <td>_Sam</td>
    <td></td>
    <td>_Sam</td>
  </tr>
  <!--  -->
  <tr>
    <td>Espacio al final</td>
    <td></td>
    <td>Sam_</td>
    <td></td>
    <td>Sam_</td>
  </tr>
  <!--  -->
  <tr>
    <td>Guiones</td>
    <td></td>
    <td>Sam-Albert</td>
    <td></td>
    <td>Sam-Albert</td>
  </tr>
  <!--  -->
  <tr>
    <td>Caracteres de otro idioma</td>
    <td></td>
    <td>山姆</td>
    <td></td>
    <td>山姆</td>
  </tr>
 
 
 

