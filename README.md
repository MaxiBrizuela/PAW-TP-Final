## Sitio web Camaleón

**Descripción**<br>
Basado en el juego de mesa "Camaleón". Al iniciar nueva ronda un jugador es elegido de forma secreta y al azar para ser el camaleón.<br> 
<br> 
A todos los jugadores se les muestra una tabla con la categoría elegida al azar junto con sus opciones (SubCategorias). Además, exeptuando al camaleón, se les enseña la opción elegida (también al azar).<br> 
<br> 
Todos los jugadores deben escribir una palabra que este relacionada con la opción, incluso el camaleón. Basandose en las respuestas de los otros jugadores, cada jugador deberá votar quién cree que es el camaleón.<br> 
<br> 

### Propuesta general del sitio a desarrollar

**Soporte de usuarios:**<br>
&nbsp;-posibilita el alta de usuarios (registrarse)<br>
&nbsp;-usuario identificado:<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Nombre<br>
&nbsp;&nbsp;&nbsp;&nbsp;-E-mail<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Contraseña<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Estadísticas de usuario (partidas jugadas, partidas ganadas)<br>
&nbsp;-Los usuarios podrán o no, según se determine, modificar todos, algunos o ninguno de los campos por ellos mismos.<br>
&nbsp;-Posibilidad de recuperar contraseña (en caso de olvidarse de ella)<br>
<br><br>

**Diseño web adaptativo (responsive)**<br>
Permite a página web cambiar su aspecto dinámicamente, adaptándose a diferentes anchos de pantalla (computadora de escritorio, tablet, celular)<br>
Cuatro anchos de pantalla son considerados:
<br>
1024px o mayores<br>
Computadoras de escritorio (PC/Mac) y notebooks.<br>
<br>
768px a 1023px<br>
Tablets en horizontal.<br>
<br> 	
480px a 767px<br>
Tablets en vertical y celulares en horizontal.<br>
<br>
por debajo de 480px<br>
Celulares en vertical.<br>
<br>

**Módulos propios del juego**<br>
&nbsp;-Administración de la salas existentes<br>
&nbsp;-Alta de salas (por parte de usuarios)<br>
&nbsp;-Administración de categorías, y sus SubCategorias<br>
&nbsp;-Alta de categorías, junto con sus SubCategorías (por parte de usuarios)<br>
&nbsp;-Jugabilidad:<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Elección al azar de categoría<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Permitir escribir respuesta<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Permitir votación<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Permitir camaleón adivinar categoría<br>
<br>

### Especificaciones técnicas
-lenguaje de programación: PHP 7.3.2<br>	 
-base de datos:	MySQL<br>	 
-estándares web: HTML5, CSS3, JavaScript<br>
