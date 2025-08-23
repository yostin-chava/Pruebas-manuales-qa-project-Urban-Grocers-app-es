# Tabla casos de prueba y pruebas: la lógica del botón "Reservar"

<table>
  <tr>
    <th>ID</th>
    <th>Título</th>
    <th>Condición previa</th>
    <th>Pasos</th>
    <th>Descripción de los pasos</th>
    <th>Resultado esperado</th>
    <th>Version</th>
    <th>Estado</th>
    <th>Enlace a los informes de errores</th>
    <th>Comentarios</th>
  </tr>
  <!-- Caso 1 -->
  <tr>
    <td rowspan="3">cp3-1</td>
    <td rowspan="3">Comprobación de la lógica del botón de reserva al completar todos los campos y direcciones obligatorias del formulario de reserva.</td>
    <td rowspan="3"><pre>1. Ir al banco de pruebas<br>2. Ingresar ""1917 Bay St"" en el campo Desde<br>3. Ingresar ""615 S Broadway"" en el campo Hasta<br>4. Elegir el modo Personal<br>5. Elegir Automóvil compartido como el tipo de transporte<br>6. Hacer clic en el botón Reservar</pre></td>
    <td>1</td>
    <td>Agregar licencia de conducir</td>
    <td rowspan="3">Texto en el botón "Reservar El recorrido será de ... kilómetros y se hará en ... minutos"<br><br>Al hacer clic en el botón, se abre la ventana "Automóvil reservado"</td>
    <td rowspan="3">Google Chrome<br>800x600</td>
    <td rowspan="3">APROBADO</td>
    <td rowspan="3"></td>
    <td rowspan="3"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Agregar método de pago</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Hacer clic en el botón de reserva</td>
  </tr>
  <!-- Caso 2 -->
  <tr>
    <td rowspan="2">cp3-2</td>
    <td rowspan="2">Comprobación de la lógica del botón de reserva al completar todos los campos y direcciones obligatorias, excepto el de la licencia de conducir en el formulario de reserva.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar ""1917 Bay St"" en el campo Desde<br>3. Ingresar ""615 S Broadway"" en el campo Hasta<br>4. Elegir el modo Personal<br>5. Elegir Automóvil compartido como el tipo de transporte<br>6. Hacer clic en el botón Reservar</pre></td>
    <td>1</td>
    <td>Agregar método de pago</td>
    <td rowspan="2">Texto en el botón "Agregar licencia de conducir y Reservar El recorrido será de ... kilómetros y se hará en ... minutos"<br><br>Al hacer clic en el botón, se abre la ventana "Agregar licencia de conducir"</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">NO APROBADO</td>
    <td rowspan="2"><a href="https://yostinch.atlassian.net/browse/IES3-27?atlOrigin=eyJpIjoiYjkxYWExZWY2ZGQ2NGM1Mzk2NjNkYWQ4YmEwYjVlZTciLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td rowspan="2"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Hacer clic en el botón de reserva</td>
  </tr>
  <!-- Caso 3 -->
  <tr>
    <td rowspan="2">cp3-3</td>
    <td rowspan="2">Comprobación de la lógica del botón de reserva al completar todos los campos y direcciones obligatorias, excepto el metodo de pago en el formulario de reserva.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar ""1917 Bay St"" en el campo Desde<br>3. Ingresar ""615 S Broadway"" en el campo Hasta<br>4. Elegir el modo Personal<br>5. Elegir Automóvil compartido como el tipo de transporte<br>6. Hacer clic en el botón Reservar</pre></td>
    <td>1</td>
    <td>Agregar licencia de conducir</td>
    <td rowspan="2">Texto en el botón "Agregar metodo de pago y Reservar El recorrido será de ... kilómetros y se hará en ... minutos"<br><br>Al hacer clic en el botón, se abre la ventana "Tarjeta agregada"</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">NO APROBADO</td>
    <td rowspan="2"><a href="https://yostinch.atlassian.net/browse/IES3-28?atlOrigin=eyJpIjoiMjU0YWFmOTg3ZmY1NDAyN2E1MjhkNjRjMTI0NDZjMTIiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td rowspan="2"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Hacer clic en el botón de reserva</td>
  </tr>
  <!-- Caso 4 -->
  <tr>
    <td rowspan="4">cp3-4</td>
    <td rowspan="4">Comprobación de la lógica del botón de reserva al completar todos los campos obligatorios y se han borrado las direcciones.</td>
    <td rowspan="4"><pre>1. Ir al banco de pruebas<br>2. Ingresar ""1917 Bay St"" en el campo Desde<br>3. Ingresar ""615 S Broadway"" en el campo Hasta<br>4. Elegir el modo Personal<br>5. Elegir Automóvil compartido como el tipo de transporte<br>6. Hacer clic en el botón Reservar</pre></td>
    <td>1</td>
    <td>Agregar licencia de conducir</td>
    <td rowspan="4">Texto en el botón "Agregar direcciones y Reservar"<br><br>No se puede hacer clic en el botón.</td>
    <td rowspan="4">Google Chrome<br>800x600</td>
    <td rowspan="4">NO APROBADO</td>
    <td rowspan="4"><a href="https://yostinch.atlassian.net/browse/IES3-29?atlOrigin=eyJpIjoiM2Y5Yzg4MTMxYzM2NDI1NWFmNDFmYzNjMmU3YjEzOTkiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td rowspan="4"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Agregar método de pago</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Borrar las direcciones</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Hacer clic en el botón de reserva</td>
  </tr>
  <!-- Caso 5 -->
  <tr>
    <td rowspan="2">cp3-5</td>
    <td rowspan="2">Comprobación de la lógica del botón de reserva al no completar los campos obligatorios y se han borrado las direcciones.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar ""1917 Bay St"" en el campo Desde<br>3. Ingresar ""615 S Broadway"" en el campo Hasta<br>4. Elegir el modo Personal<br>5. Elegir Automóvil compartido como el tipo de transporte<br>6. Hacer clic en el botón Reservar</pre></td>
    <td>1</td>
    <td>Borrar las direcciones</td>
    <td rowspan="2">Texto en el botón "Agregar licencia de conducir y reservar"<br><br>Al hacer clic en el botón, se abre la ventana "Agregar licencia de conducir"</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">OMITIDA</td>
    <td rowspan="2"></td>
    <td rowspan="2">La prueba se omite, ya que, al igual que la prueba CP3-4, al borrar las direcciones, el formulario de reserva del automóvil compartido se cierra.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Hacer clic en el botón de reserva</td>
  </tr>
</table>
