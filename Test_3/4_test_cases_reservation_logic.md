# Tabla casos de prueba y pruebas: la lógica de las funciones de reserva

<div style="overflow-x:auto;">
  <table>

  <thead>
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
  </thead>
  <tbody>
  <!-- Caso 1 -->
  <tr>
    <td>cp4-1</td>
    <td>Verificar que la interfaz de la ventana "Reservar un automóvil" 
      se muestre correctamente cuando el usuario completa todos los campos requeridos de forma válida.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>En el centro de la pantalla aparecerá una ventana con el título "Automóvil reservado". En su interior se encuentra la marca, número de placa, ícono y dirección del vehículo, así como el costo del trayecto y el temporizador que muestra el tiempo de espera gratuito.</td>
    <td>Google Chrome<br>800x600</td>
    <td>APROBADO</td>
    <td></td>
    <td></td>
  </tr>
  <!-- Caso 2 -->
  <tr>
    <td>cp4-2</td>
    <td>Comprobación de la marca del vehículo seleccionado en la ventana "Reservar un automóvil" al completar todos los campos correctamente.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>La marca del automóvil es la misma del auto selecionado.</td>
    <td>Google Chrome<br>800x600</td>
    <td>OMITIDA</td>
    <td></td>
    <td>Esta prueba fue omitida debido a que la función de ver y elegir los automóviles disponibles no está habilitada aún.</td>
  </tr>
  <!-- Caso 3 -->
  <tr>
    <td>cp4-3</td>
    <td>Verificar que la dirección asociada al vehículo seleccionado se muestre correctamente en la ventana "Reservar un automóvil", una vez que el usuario completa todos los campos requeridos.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>La direcion del vehiculo es "1917 Bay St".</td>
    <td>Google Chrome<br>800x600</td>
    <td>APROBADO</td>
    <td></td>
    <td></td>
  </tr>
   <!-- Caso 4 -->
  <tr>
    <td>cp4-4</td>
    <td>Verificar que el costo del trayecto se calcule y muestre correctamente en la ventana "Reservar un automóvil", una vez que el usuario completa todos los campos requeridos.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>El costo del trayecto es igual al de la tarifa seleccionada.</td>
    <td>Google Chrome<br>800x600</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-30?atlOrigin=eyJpIjoiNDJjMjg1YWIwZTc5NDJhYzhmMDEwNGFmYmQ1YmYxNTYiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td></td>
  </tr>
  <!-- Caso 5 -->
  <tr>
    <td rowspan="3">cp4-5</td>
    <td rowspan="3">Verificar el comportamiento del sistema al eliminar las direcciones "Desde" y "Hasta" para asegurar que el sistema actualice o limpie correctamente la información relacionada.</td>
    <td rowspan="3"><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td rowspan="3">La dirección no aparece y se muestra el precio por minuto.</td>
    <td rowspan="3">Google Chrome<br>800x600</td>
    <td rowspan="3">NO APROBADO</td>
    <td rowspan="3"><a href="https://yostinch.atlassian.net/browse/IES3-31?atlOrigin=eyJpIjoiZjBkOGVmNGEwYWQ5NDJjOTg5YTFkNWFjZmJiYWYzZjIiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td rowspan="3"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Borrar la dirección "Desde"</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Borrar la dirección "Hasta"</td>
  </tr>
  <!-- Caso 6 -->
  <tr>
    <td rowspan="2">cp4-6</td>
    <td rowspan="2">Verificar que al eliminar únicamente la dirección "Desde", el sistema actualice o limpie correctamente el costo del trayecto y cualquier información relacionada que dependa de dicha dirección.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td rowspan="2">La dirección no aparece y se muestra el precio por minuto.</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">OMITIDA</td>
    <td rowspan="2"></td>
    <td rowspan="4">La prueba fue omitida debido a que el precio por minuto no se muestra en la prueba cp4-5.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Borrar la direccion "Desde"</td>
  </tr>
  <!-- Caso 7 -->
  <tr>
    <td rowspan="2">cp4-7</td>
    <td rowspan="2">Verificar que al eliminar únicamente la dirección "Hasta", el sistema actualice o limpie correctamente el costo del trayecto y cualquier información relacionada que dependa de dicha dirección.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td rowspan="2">La dirección del vehiculo es "1917 Bay St" y se muestra el precio por minuto.</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">OMITIDA</td>
    <td rowspan="2"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Borrar la direccion "Hasta"</td>
  </tr>
  <!-- Caso 8 -->
  <tr>
    <td>cp4-8</td>
    <td>Comprobar que el tiempo mostrado por el temporizador en la ventana "Reservar un automóvil" sea coherente y coincida exactamente con el temporizador o duración establecida en la descripción de la tarifa "Casual".</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>El temporizador inicia en 15min.</td>
    <td>Google Chrome<br>800x600</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-32?atlOrigin=eyJpIjoiYzFlZDA3Y2E3MzE1NDNkMjgyODgwOTlmNjc5MzE2Y2EiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td></td>
  </tr>
  <!-- Caso 9 -->
  <tr>
    <td>cp4-9</td>
    <td>Comprobar que el tiempo mostrado por el temporizador en la ventana "Reservar un automóvil" sea coherente y coincida exactamente con el temporizador o duración establecida en la descripción de la tarifa "Camping".</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>El temporizador inicia en 12min.</td>
    <td>Google Chrome<br>800x600</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-33?atlOrigin=eyJpIjoiNGVmMDc5NzBhYzljNGQ2OTgyYzQxMjEwMmU5YWVhNGEiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td></td>
  </tr>
  <!-- Caso 10 -->
  <tr>
    <td>cp4-10</td>
    <td>Comprobar que el tiempo mostrado por el temporizador en la ventana "Reservar un automóvil" sea coherente y coincida exactamente con el temporizador o duración establecida en la descripción de la tarifa "De lujo".</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>El temporizador inicia en 10min.</td>
    <td>Google Chrome<br>800x600</td>
    <td>APROBADO</td>
    <td></td>
    <td></td>
  </tr>
  <!-- Caso 11 -->
  <tr>
    <td>cp4-11</td>
    <td>Verificar que el temporizador de la ventana 'Reservar un automóvil' disminuya correctamente con el tiempo.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>El temporizador disminuye en el tiempo.</td>
    <td>Google Chrome<br>800x600</td>
    <td>APROBADO</td>
    <td></td>
    <td></td>
  </tr>
  <!-- Caso 12 -->
  <tr>
    <td rowspan="2">cp4-12</td>
    <td rowspan="2">Comprobar que, mientras el temporizador no finalice, el botón 'Cancelar' en la ventana 'Reservar un automóvil' cancele correctamente el viaje.</td>
    <td rowspan="2"><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td rowspan="2">El viaje se cancela de forma gratuita.</td>
    <td rowspan="2">Google Chrome<br>800x600</td>
    <td rowspan="2">NO APROBADO</td>
    <td rowspan="2"><a href="https://yostinch.atlassian.net/browse/IES3-34?atlOrigin=eyJpIjoiMjZhYTVlZTQzNDk3NGE1MmI1NDJiZTAwNzk1N2RjMWIiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td rowspan="2"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Hacer clic en el botón “Cancelar” de la ventana “Reservar automóvil”.</td>
  </tr>
  <!-- Caso 13 -->
  <tr>
    <td>cp4-13</td>
    <td>Comprobar que, al finalizar el tiempo de espera gratuito, el temporizador comienza a contar el tiempo de uso compartido del vehículo.</td>
    <td><pre>1. Ir al banco de pruebas<br>2. Ingresar "East 2nd street, 601" en el campo Desde.<br>3. Ingresar "1300 1St st" en el campo Hasta.<br>4. Elegir el modo Personal.<br>5. Elegir Automóvil compartido como el tipo de transporte.<br>6. Hacer clic en el botón "Reservar".<br>7. Dejar la tarifa en casual.<br>8. Agregar la licencia de conducir.<br>9. Agregar el metodo de pago.</pre></td>
    <td>1</td>
    <td>Hacer clic en el botón de reserva</td>
    <td>Al finalizar el tiempo de espera gratuito, el temporizador comienza a contar el tiempo de uso compartido del vehiculo.</td>
    <td>Google Chrome<br>800x600</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-35?atlOrigin=eyJpIjoiYmIyZTE2ODViYjY1NGFiNGEzZmJmMTk2ZGViMzljZGMiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
    <td></td>
  </tr>
  
</tbody>
</table>
</div>
