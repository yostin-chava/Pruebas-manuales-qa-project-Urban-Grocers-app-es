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
  <!-- Distancia 0 -->
  <tr>
    <td rowspan="2">Distancia entre las direcciones</td>
    <td>distancia es 0</td>
    <td></td>
    <td>0</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>distancia no es 0</td>
    <td></td>
    <td>2,7</td>
    <td></td>
    <td></td>
  </tr>
  <!-- Primera hora -->
  <tr>
    <td rowspan="30">Hora de salida</td>
    <td rowspan="6">Hora entre 00:01 a 08:00</td>
    <td rowspan="6">00:01 a 08:00</td>
    <td rowspan="6">05:35</td>
    <td>00:01</td>
    <td rowspan="6">00:01<br>08:00<br>00:02<br>07:59</td>
  </tr>
  <tr>
    <td>08:00</td>
  </tr>
  <tr>
    <td>00:00</td>
  </tr>
  <tr>
    <td>08:01</td>
  </tr>
  <tr>
    <td>00:02</td>
  </tr>
  <tr>
    <td>07:59</td>
  </tr>
  <!-- Segunda hora -->
  <tr>
    <td rowspan="6">Hora entre 08:01 a 12:00</td>
    <td rowspan="6">08:01 a 12:00</td>
    <td rowspan="6">10:35</td>
    <td>08:01</td>
    <td rowspan="6">08:01<br>12:00<br>08:02<br>11:59</td>
  </tr>
  <tr>
    <td>12:00</td>
  </tr>
  <tr>
    <td>08:00</td>
  </tr>
  <tr>
    <td>12:01</td>
  </tr>
  <tr>
    <td>08:02</td>
  </tr>
  <tr>
    <td>11:59</td>
  </tr>
  <!-- Tercera hora -->
  <tr>
    <td rowspan="6">Hora entre 12:01 a 18:00</td>
    <td rowspan="6">12:01 a 18:00</td>
    <td rowspan="6">15:35</td>
    <td>12:01</td>
    <td rowspan="6">12:01<br>18:00<br>12:02<br>17:59</td>
  </tr>
  <tr>
    <td>18:00</td>
  </tr>
  <tr>
    <td>12:00</td>
  </tr>
  <tr>
    <td>18:01</td>
  </tr>
  <tr>
    <td>11:02</td>
  </tr>
  <tr>
    <td>17:59</td>
  </tr>
  <!-- Cuarta hora -->
  <tr>
    <td rowspan="6">Hora entre 18:01 a 22:00</td>
    <td rowspan="6">18:01 a 22:00</td>
    <td rowspan="6">20:35</td>
    <td>18:01</td>
    <td rowspan="6">18:01<br>22:00<br>18:02<br>21:59</td>
  </tr>
  <tr>
    <td>22:00</td>
  </tr>
  <tr>
    <td>18:00</td>
  </tr>
  <tr>
    <td>22:01</td>
  </tr>
  <tr>
    <td>18:02</td>
  </tr>
  <tr>
    <td>21:59</td>
  </tr>
  <!-- Quinta hora -->
  <tr>
    <td rowspan="6">Hora entre 22:01 a 00:00</td>
    <td rowspan="6">22:01 a 00:00</td>
    <td rowspan="6">23:35</td>
    <td>22:01</td>
    <td rowspan="6">22:01<br>00:00<br>22:02<br>23:59</td>
  </tr>
  <tr>
    <td>00:00</td>
  </tr>
  <tr>
    <td>22:00</td>
  </tr>
  <tr>
    <td>00:01</td>
  </tr>
  <tr>
    <td>22:02</td>
  </tr>
  <tr>
    <td>23:59</td>
  </tr>
