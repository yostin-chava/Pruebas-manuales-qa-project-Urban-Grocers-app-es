# Tabla lista de comprobación y resultados de las pruebas: prueba de las ventanas "Método de pago" y "Agregar tarjeta"

<table>
  <tr>
    <th>Número</th>
    <th>Descripción de la supervisión</th>
    <th>Estado de la versión</th>
    <th>Enlace al informe de errores</th>
  </tr>
  <!-- Numero 1 -->
  <tr>
    <td>1</td>
    <td>Verificar que el campo "Método de pago" esté vacío por defecto.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 2 -->
  <tr>
    <td>2</td>
    <td>Al hacer clic en el campo "Método de pago", se abre la ventana "Método de pago".</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 3 -->
  <tr>
    <td>3</td>
    <td>Al hacer clic en el botón "Agregar tarjeta", se abre el formulario "Agregar tarjeta".</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 4 -->
  <tr>
    <td>4</td>
    <td>El formulario "Agregar tarjeta" tiene un campo para agregar el número de la tarjeta.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 5 -->
  <tr>
    <td>5</td>
    <td>El formulario "Agregar tarjeta" tiene un campo para agregar el código de la tarjeta.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 6 -->
  <tr>
    <td>6</td>
    <td>Al hacer clic en el botón "Agregar", el formulario se cierra y se agrega la tarjeta ingresada.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 7 -->
  <tr>
    <td>7</td>
    <td>Al hacer clic en el botón "Cancelar", se cierra el formulario y no se agrega la tarjeta ingresada.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 8 -->
  <tr>
    <td>8</td>
    <td>Al hacer clic en "X", el formulario se cierra.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 9 -->
  <tr>
    <td>9</td>
    <td>Al introducir 12 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "999999999999"), el botón "Agregar" se habilita.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 10 -->
  <tr>
    <td>10</td>
    <td>Al introducir 12 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "000000000000"), el botón "Agregar" se habilita.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 11 -->
  <tr>
    <td>11</td>
    <td>Al introducir 12 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "999999999998"), el botón "Agregar" se habilita.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 12 -->
  <tr>
    <td>12</td>
    <td>Al introducir 12 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "000000000001"), el botón "Agregar" se habilita.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 13 -->
  <tr>
    <td>13</td>
    <td>Al dejar el campo "Número de tarjeta" vacío, el botón "Agregar" aparece inactivo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 14 -->
  <tr>
    <td>14</td>
    <td>Los espacios se añaden automáticamente cuando se introducen los números de la tarjeta y se quita el enfoque.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-14?atlOrigin=eyJpIjoiNzllNjlhMWVkNzRjNDA4MWJjMjVlMGUwMDJlNzE3YTAiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 15 -->
  <tr>
    <td>15</td>
    <td>Al agregar una tarjeta, la interfaz "Método de pago" muestra los 4 últimos dígitos de su número.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-15?atlOrigin=eyJpIjoiNDQxN2Q5MzVjZTM1NDYwYjliMDEyYjI3Mzg1Yzg5ZTQiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 16 -->
  <tr>
    <td>16</td>
    <td>Al introducir 11 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "12345678911"), el botón "Agregar" permanece inactivo.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-16?atlOrigin=eyJpIjoiZDg3NTVmZjZkM2Q1NGFkODhkMzM5MWRjN2Q4MjczYzEiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 17 -->
  <tr>
    <td>17</td>
    <td>Al introducir 1 carácter numérico en el campo "Número de tarjeta" (por ejemplo, "1"), el botón "Agregar" permanece inactivo.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-17?atlOrigin=eyJpIjoiMTk5MjUxOGM5MTc3NDg1NmJmNmMwZGZmZmVhNzlmNTQiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 18 -->
  <tr>
    <td>18</td>
    <td>No es posible introducir 13 caracteres numéricos en el campo "Número de tarjeta" (por ejemplo, "1234567891013").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-18?atlOrigin=eyJpIjoiYTZmN2ViMDllY2JlNGM0MGI3ZTFhOGQ2M2JjN2NiYWEiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 19 -->
  <tr>
    <td>19</td>
    <td>No es posible introducir otros caracteres en el campo "Número de tarjeta" (por ejemplo, "1p#$+-()._12").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-19?atlOrigin=eyJpIjoiNjEzMjVkNDQ4NWUzNDY0MGI0MGI2YWRlMmU5YTlhZmMiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 20 -->
  <tr>
    <td>20</td>
    <td>No es posible introducir espacios en el campo "Número de tarjeta" (por ejemplo, "1234 1234 1234").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-20?atlOrigin=eyJpIjoiNzBmYjM4YTdhZGU2NDlhZWEzYzBjNzVhNThiMWM2NGYiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 21 -->
  <tr>
    <td>21</td>
    <td>Al introducir 2 caracteres numéricos válidos ("01") en el campo "Código", el botón "Agregar" aparece activo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 22 -->
  <tr>
    <td>22</td>
    <td>Al introducir 2 caracteres numéricos válidos ("02") en el campo "Código", el botón "Agregar" aparece activo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 23 -->
  <tr>
    <td>23</td>
    <td>Al introducir 2 caracteres numéricos válidos ("98") en el campo "Código", el botón "Agregar" aparece activo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 24 -->
  <tr>
    <td>24</td>
    <td>Al introducir 2 caracteres numéricos válidos ("99") en el campo "Código", el botón "Agregar" aparece activo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 25 -->
  <tr>
    <td>25</td>
    <td>Al dejar el campo "Código" vacío, el botón "Agregar" aparece inactivo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 26 -->
  <tr>
    <td>26</td>
    <td>Al introducir 2 caracteres numéricos inválidos ("00") en el campo "Código", el botón "Agregar" aparece inactivo.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-21?atlOrigin=eyJpIjoiZDNkNDI3YWI3YWQxNDIwNDg0NjFkOTI5ZjM0MjQyZTYiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 27 -->
  <tr>
    <td>27</td>
    <td>Al introducir 1 carácter numérico ("1") en el campo "Código", el botón "Agregar" aparece inactivo.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-22?atlOrigin=eyJpIjoiM2QzNzhmZTBiYjlhNDg1MTllNjBlMmI3YmE5YzM2YjMiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 28 -->
  <tr>
    <td>28</td>
    <td>No es posible introducir 3 caracteres numéricos ("123") en el campo "Código".</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-23?atlOrigin=eyJpIjoiMGFhNThmNjQ0MDY1NGNhMjkyZWIxYWEyYWVjNTI0YzgiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 29 -->
  <tr>
    <td>29</td>
    <td>No es posible introducir otros caracteres en el campo "Código" (por ejemplo, "-#").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-24?atlOrigin=eyJpIjoiZDdmOGJhMzBkOWRiNGQxOWE1YzcwYzNhNzJiMTVmN2MiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 30 -->
  <tr>
    <td>30</td>
    <td>No es posible introducir espacios en el campo "Código" (por ejemplo, " 3").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-25?atlOrigin=eyJpIjoiNjZiNjQzMTkwODFiNGRjNTkxMDJmZWEyYWQ5YjJiZTAiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 31 -->
  <tr>
    <td>31</td>
    <td>Al agregar una tarjeta nueva ("Segunda tarjeta"), la ventana emergente "Añadir Tarjeta" debe estar completamente vacía.</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-26?atlOrigin=eyJpIjoiN2ZhYTQ4MzdiNThjNGZmMWIwNDYxOGU5ZjljZjJlMzYiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 32 -->
  <tr>
    <td>32</td>
    <td>Al introducir el "Número de tarjeta" y dejar el campo "Código" vacío, el botón "Agregar" aparece inactivo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 33 -->
  <tr>
    <td>33</td>
    <td>Al introducir el "Código" y dejar el campo "Número de tarjeta" vacío, el botón "Agregar" aparece inactivo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 34 -->
  <tr>
    <td>34</td>
    <td>Al introducir el "Número de tarjeta" y el "Código", el botón "Agregar" aparece activo.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 35 -->
  <tr>
    <td>35</td>
    <td>Al agregar la tarjeta, esta es visible en una ventana.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 36 -->
  <tr>
    <td>36</td>
    <td>Al ingresar varias tarjetas, se puede seleccionar una de ellas para el pago del viaje.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 37 -->
  <tr>
    <td>37</td>
    <td>El botón "Agregar Tarjeta" para agregar una tarjeta nueva está activo debajo de la tarjeta añadida.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 38 -->
  <tr>
    <td>38</td>
    <td>Al dar clic en el botón "Agregar Tarjeta", se abre el formulario para añadir tarjeta con el fin de agregar una tarjeta nueva.</td>
    <td>APROBADO</td>
    <td></td>
  </tr>
  <!-- Numero 39 -->
  <tr>
    <td>39</td>
    <td>No es posible introducir caracteres del alfabeto latino en el campo "Número de tarjeta" (por ejemplo, "Hola").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-37?atlOrigin=eyJpIjoiMWI3NzI4NjZkM2U0NDVjOWJjM2Q3N2M1YmY2Zjk4YTciLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 40 -->
  <tr>
    <td>40</td>
    <td>No es posible introducir caracteres no latinos en el campo "Número de tarjeta" (por ejemplo, "你好").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-38?atlOrigin=eyJpIjoiNWFlZGYwZjlhNDBhNDcxNGE3ZTVkNDI2Y2IyNmQ2NTUiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 41 -->
  <tr>
    <td>41</td>
    <td>No es posible introducir caracteres del alfabeto latino en el campo "Código" (por ejemplo, "Ho").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-39?atlOrigin=eyJpIjoiYjUxMmE4YzkxZjM3NDdjMThmZGFiNWU1ZjAzMDQ3NDgiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
  <!-- Numero 42 -->
  <tr>
    <td>42</td>
    <td>No es posible introducir caracteres no latinos en el campo "Código" (por ejemplo, "你").</td>
    <td>NO APROBADO</td>
    <td><a href="https://yostinch.atlassian.net/browse/IES3-40?atlOrigin=eyJpIjoiYThhYWY1NzJlOWIxNGJiYjkyMWNmMmE2NDc3Mjk0ZmQiLCJwIjoiaiJ9" target="_blank">Link a Jira</a></td>
  </tr>
</table>
