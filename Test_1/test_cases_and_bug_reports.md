# Tabla casos de prueba

<table>
  <tr>
    <th>ID</th>
    <th>Título</th>
    <th>Condición previa</th>
    <th>Pasos</th>
    <th>Descripción de los pasos</th>
    <th>Resultado esperado</th>
    <th>Estado</th>
    <th>ID del error</th>
  </tr>
  <!-- Caso 1 -->
  <tr>
    <td>CASO-1</td>
    <td>Desplazamiento del mapa</td>
    <td>Abrir la aplicación Urban Routes</td>
    <td>1</td>
    <td>Desplazarse por el mapa hacia arriba y hacia abajo.</td>
    <td>El mapa se mueve. Todos los objetos se muestran según el diseño.</td>
    <td>Aprobado</td>
    <td></td>
  </tr>
  <!-- Caso 2 -->
  <tr>
    <td rowspan="2">CASO-2</td>
    <td rowspan="2">Zoom del mapa</td>
    <td rowspan="2">La aplicación Urban Routes no debe estar abierta</td>
    <td>1</td>
    <td>Abrir la aplicación Urban Routes</td>
    <td rowspan="2">El nivel de zoom aumenta en un valor. Todos los objetos se muestran según el diseño.</td>
    <td rowspan="2">Aprobado</td>
    <td rowspan="2"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Hacer clic en el botón "más" (+) en la esquina inferior derecha.</td>
  </tr>
  <!-- Caso 3 -->
  <tr>
    <td>CASO-3</td>
    <td>No se puede hacer clic en los encabezados del área en el mapa.</td>
    <td>Abrir la aplicación Urban Routes.</td>
    <td>1</td>
    <td>Hacer clic en el encabezado de área en el mapa (ejemplo: Hollywood).</td>
    <td>No ocurre nada. Los usuarios no pueden interactuar con los encabezados del mapa.</td>
    <td>No Aprobado</td>
    <td>P1_EC3</td>
  </tr>
  <!-- Caso 4 -->
  <tr>
    <td>CASO-4</td>	
    <td>No se puede hacer clic en los encabezados de la ciudad en el mapa</td>	
    <td>Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Hacer clic en el encabezado de la ciudad en el mapa (ejemplo: West Hollywood).</td>	
    <td>No ocurre nada. Los encabezados de la ciudad no se pueden seleccionar.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 5 -->
  <tr>
    <td>CASO-5</td>	
    <td>Se puede seleccionar el campo "Desde"</td>
    <td>Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Hacer clic en el campo "Desde".</td>	
    <td>Se selecciona el campo "Desde". El cursor parpadea. El campo de búsqueda está vacío.</td>	
    <td>No Aprobado</td>	
    <td>P1_EC5</td>
  </tr>
  <!-- Caso 6 -->
  <tr>
    <td rowspan="2">CASO-6</td>	
    <td rowspan="2">Se pueden buscar objetos en el campo "Hasta"</td>	
    <td rowspan="2">Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Hacer clic en el campo "Hasta".</td>	
    <td rowspan="2">Se muestra la lista de estaciones de metro.</td>	
    <td rowspan="2">No Aprobado</td>	
    <td rowspan="2">P1_EC6</td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Escribir "Subway" (Metro).</td>
  </tr>
  <!-- Caso 7 -->
  <tr>
    <td rowspan="2">CASO-7</td>	
    <td rowspan="2">El pin de la dirección aparece después de completar el campo "Desde"</td>	
    <td rowspan="2">- Abrir la aplicación Urban Routes<br>-El campo "Desde" debe estar vacío</td>	
    <td>1</td>	
    <td>Hacer clic en el campo "Desde".</td>	
    <td rowspan="2">El mapa hace zoom sobre el pin de la dirección seleccionada. La vista coincide con la descripción del diseño.</td>	
    <td rowspan="2">No Aprobado</td>	
    <td rowspan="2">P1_EC7</td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Ingresar una dirección (ejemplo: East 2nd Street, 601).</td>
  </tr>
  <!-- Caso 8 -->
  <tr>
    <td rowspan="2">CASO-8</td>	
    <td rowspan="2">El pin de la dirección aparece después de completar el campo "Hasta"</td>	
    <td rowspan="2">- Abrir la aplicación Urban Routes<br>-El campo "Hasta" debe estar vacío</td>	
    <td>1</td>	
    <td>Hacer clic en el campo "Hasta".</td>	
    <td rowspan="2">El mapa hace zoom sobre el pin de la dirección seleccionada. La vista coincide con la descripción del diseño.</td>	
    <td rowspan="2">No Aprobado</td>	
    <td rowspan="2">P1_EC8</td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Ingresar una dirección (ejemplo: 1300 1st St).</td>
  </tr>
  <!-- Caso 9 -->
  <tr>
    <td>CASO-9</td>	
    <td>La dirección se elimina después de borrar el campo "Desde"</td>
    <td>Abrir la aplicación Urban Routes. El campo "Desde" debe estar lleno</td>	
    <td>1</td>	
    <td>Hacer clic en la "X" del campo "Desde".</td>	
    <td>El campo está vacío. La dirección introducida anteriormente se ha eliminado del campo. La marca correspondiente desaparece del mapa.</td>	
    <td>Omitida</td>	
    <td></td>
  </tr>
  <!-- Caso 10 -->
  <tr>
    <td>CASO-10</td>	
    <td>La dirección se elimina después de borrar el campo "Hasta"</td>
    <td>Abrir la aplicación Urban Routes. El campo "Hasta" debe estar lleno</td>	
    <td>1</td>	
    <td>Hacer clic en la "X" del campo "Hasta".</td>	
    <td>El campo está vacío. La dirección introducida anteriormente se ha eliminado del campo. La marca correspondiente desaparece del mapa.</td>	
    <td>Omitida</td>	
    <td></td>
  </tr>
  <!-- Caso 11 -->
  <tr>
    <td>CASO-11</td>	
    <td>Se muestran los objetos 3D</td>
    <td>Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Ampliar el mapa varias veces sobre un objeto 3D (por ejemplo: Los Angeles International Airport LAX).</td>	
    <td>El objeto se renderiza en 3D.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 12 -->
  <tr>
    <td>CASO-12</td>	
    <td>El modo de vista de pantalla completa se activa al hacer clic en el botón del modo de vista de pantalla completa</td>
    <td>-Abrir la aplicación Urban Routes.<br>-El modo de vista de pantalla completa no debe estar activado</td>	
    <td>1</td>	
    <td>Hacer clic en el botón del modo de vista de pantalla completa en la esquina superior derecha.</td>	
    <td>El modo de vista de pantalla completa se activa y las pestañas del navegador se ocultan. Todos los objetos de la interfaz del mapa están en su lugar. El nivel de zoom no cambia.</td>	
    <td>No Aprobado</td>	
    <td>P1_EC12</td>
  </tr>
  <!-- Caso 13 -->
  <tr>
    <td>CASO-13</td>	
    <td>El modo de vista de pantalla completa se desactiva al hacer clic de nuevo en el botón del modo de vista de pantalla completa</td>
    <td>-Abrir la aplicación Urban Routes.<br>-Activar el modo de vista de pantalla completa</td>	
    <td>1</td>	
    <td>Hacer clic en el botón del modo de vista de pantalla completa en la esquina superior derecha.</td>	
    <td>El modo de vista de pantalla completa se desactiva y las pestañas del navegador se vuelven a mostrar. Todos los objetos de la interfaz del mapa están en su lugar. El nivel de zoom no cambia.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 14 -->
  <tr>
    <td rowspan="3">CASO-14</td>	
    <td rowspan="3">El modo Relieve se activa al hacer clic en el botón del modo Relieve</td>	
    <td rowspan="3">Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Acercar el cursor al botón del modo de mapa en la esquina superior izquierda.</td>	
    <td rowspan="3">La casilla de verificación se rellena. El mapa se muestra en modo Relieve y coincide con el diseño.</td>	
    <td rowspan="3">Aprobado</td>	
    <td rowspan="3"></td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Acercar el cursor al botón del modo Relieve.</td>
  </tr>
  <tr>
    <td>3</td>	
    <td>Hacer clic en el botón del modo Relieve.</td>
  </tr>
  <!-- Caso 15 -->
  <tr>
    <td rowspan="2">CASO-15</td>	
    <td rowspan="2">El modo Satélite se activa al hacer clic en el botón del modo Satélite</td>	
    <td rowspan="2">Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Acercar el cursor al botón del modo Satélite en la esquina superior izquierda.</td>	
    <td rowspan="2">El mapa muestra el modo Satélite. La vista no tiene problemas notables.</td>	
    <td rowspan="2">Aprobado</td>	
    <td rowspan="2"></td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Hacer clic en el botón Satélite.</td>
  </tr>
  <!-- Caso 16 -->
  <tr>
    <td>CASO-16</td>	
    <td>Los edificios se muestran al hacer zoom sobre ellos</td>
    <td>Abrir la aplicación Urban Routes.</td>	
    <td>1</td>	
    <td>Hacer zoom en un edificio.</td>	
    <td>El edificio se muestra según el diseño.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 17 -->
  <tr>
    <td>CASO-17</td>	
    <td>Las estaciones de metro se muestran al hacer zoom sobre ellas</td>
    <td>Abrir la aplicación Urban Routes.</td>	
    <td>1</td>	
    <td>Hacer zoom en una estación de metro de Los Ángeles (ejemplo: Downtown Long Beach Station).</td>	
    <td>Se muestra el ícono del metro.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 18 -->
  <tr>
    <td>CASO-18</td>	
    <td>Los lugares de interés se muestran al hacer zoom sobre ellos</td>
    <td>Abrir la aplicación Urban Routes.</td>	
    <td>1</td>	
    <td>Hacer zoom en un lugar de interés (ejemplo: Los Angeles County Museum of Art).</td>	
    <td>Se muestra el ícono del lugar de interés.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 19 -->
  <tr>
    <td>CASO-19</td>	
    <td>Los parques se muestran al hacer zoom sobre ellos</td>
    <td>Abrir la aplicación Urban Routes.</td>	
    <td>1</td>	
    <td>Hacer zoom en un parque de la ciudad (ejemplo: Vista Hermosa Natural Park).</td>	
    <td>Se muestra el ícono del parque.</td>	
    <td>No Aprobado</td>	
    <td>P1_EC19</td>
  </tr>
  <!-- Caso 20 -->
  <tr>
    <td>CASO-20</td>	
    <td>La información del objeto se muestra al hacer clic en un objeto</td>
    <td>Abrir la aplicación Urban Routes.</td>	
    <td>1</td>	
    <td>Hacer clic en un lugar en el mapa (ejemplo: Dodger Stadium).</td>	
    <td>La visualización de información (con información del lugar) está abierta. La vista coincide con el diseño.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 21 -->
  <tr>
    <td>CASO-21</td>	
    <td>La información del objeto se oculta al hacer clic en la cruz en la vista de información</td>
    <td>-Abrir la aplicación Urban Routes.<br>-Abrir la vista de información</td>	
    <td>1</td>	
    <td>Hacer clic en la "X" en la vista de información.</td>	
    <td>La vista de información está cerrada. No hay elementos adicionales en el mapa.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 22 -->
  <tr>
    <td rowspan="5">CASO-22</td>	
    <td rowspan="5">El modo Street View se activa cuando el ícono de Street View se arrastra sobre una calle</td>	
    <td rowspan="5">-Abrir la aplicación Urban Routes.<br>-El modo Street View no debe estar activado</td>	
    <td>1</td>	
    <td>Desplazarse por el mapa hasta el área del Dodger Stadium.</td>	
    <td>El área del Dodger Stadium se amplía.</td>	
    <td rowspan="5">Aprobado</td>	
    <td rowspan="5"></td>		
  </tr>
  <tr>
    <td>2</td>	
    <td>Establecer el nivel máximo de zoom.</td>
    <td>El nivel de zoom aumenta al máximo.</td>
  </tr>
  <tr>
    <td>3</td>	
    <td>Hacer clic en el ícono "menos" (-) en la esquina inferior derecha 5 veces.</td>
    <td>El nivel de zoom se reduce en 5 niveles.</td>
  </tr>
  <tr>
    <td>4</td>	
    <td>Arrastrar el ícono del modo Street View y colócalo en cualquier calle.</td>
    <td>El modo Street View se activa.</td>
  </tr>
  <tr>
    <td>5</td>	
    <td>Desplázarse sobre la imagen.</td>
    <td>La imagen se desplaza 360 grados.</td>
  </tr>
  <!-- Caso 23 -->
  <tr>
    <td>CASO-23</td>	
    <td>El modo Street View se desactiva al hacer clic en una flecha gris</td>
    <td>-Abrir la aplicación Urban Routes.<br>-Activar el modo Street View</td>	
    <td>1</td>	
    <td>Hacer clic en la pequeña flecha gris situada en el rectángulo negro (en la esquina superior izquierda del mapa).</td>	
    <td>El modo Street View se desactiva.</td>	
    <td>Aprobado</td>	
    <td></td>
  </tr>
  <!-- Caso 24 -->
  <tr>
    <td>CASO-24</td>	
    <td>La información de la aplicación se muestra al hacer clic en el logotipo de la aplicación</td>
    <td>Abrir la aplicación Urban Routes</td>	
    <td>1</td>	
    <td>Hacer clic en el logotipo de Urban Routes.</td>	
    <td>Se muestra la información sobre la aplicación.</td>	
    <td>No Aprobado</td>	
    <td>P1_EC24</td>
  </tr>
</table>

<!----------------------->
<!----------------------->
# Tabla informe de errores
<!----------------------->
<!----------------------->

<table>
  <tr>
    <th>ID del error</th>
    <th>Título</th>
    <th>Pasos a seguir</th>
    <th>Resultado esperado</th>
    <th>Resultado actual</th>
    <th>Severidad</th>
  </tr>
  <tr>
    <td>P1_EC3</td>
    <td>Al hacer clic en el encabezado del área del mapa se muestra una descripción del área seleccionada.</td>
    <td>
      - Abrir la aplicación Urban Routes.<br>
      - Hacer clic sobre cualquier encabezado de área que no sea encabezado de la ciudad.
    </td>
    <td>No se puede interactuar con el encabezado de área.</td>
    <td>Se muestra descripción del área seleccionada.</td>
    <td>Grave</td>
  </tr>





