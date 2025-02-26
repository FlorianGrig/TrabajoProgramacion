# Trabajo-Programacion
IES LUIS VIVES – Grupo: 1º DAW
Programación
Práctica 01

El club de fútbol New Team, famoso por sus jugadores y entrenadores destacados, ha decidido
implementar un nuevo sistema de gestión de personal. Este sistema debe ser capaz de manejar la
información de entrenadores y jugadores de manera eficiente.

1. Gestión de Personal:
   
  Diseña una estructura base que pueda ser utilizada para representar a cualquier empleado
  del club. Esta estructura debe incluir información esencial como un identificador único y
  gestionado por el sistema de almacenamiento (es decir, por mucho que se indique, será el
  sistema quién los asigne para evitar conflictos), nombre, apellidos, fecha de nacimiento,
  fecha de incorporación al club, salario, y país de origen.

2. Entrenadores:
   
  Además de la información general, cada entrenador debe tener un campo adicional que
  indique su área de especialización. Las especialidades posibles incluyen entrenador de
  porteros, entrenador principal y entrenador asistente.
  
3. Jugadores:
   
  Además de la información general, cada jugador debe incluir detalles como su posición en
  el campo (portero, defensa, centrocampista o delantero), número de camiseta, altura,
  peso, número de goles anotados y partidos jugados.

Necesitamos crear un servicio con caché LRU de máximo 5 elementos para gestionar nuestro personal
con las operaciones CRUD. Los datos deben estar validados para evitar problemas de entrada de datos
en el sistema de almacenamiento central. Debemos tener en cuenta que los datos nos pueden llegar por
consola y ficheros en formato CSV, XML, JSON y Binario (con un formato establecido por el
desarrollador/a que pueda ser compatible con todos los lenguajes existentes) y que esos mismos
formatos serán los soportados para la salida de la información. Toda salida de información por consola
debe estar localizada según lo indicado en el fichero de configuración.

Tendremos un menú con las siguientes opciones:

1. Cargar datos desde fichero según la especificación indicada.
2. Crear miembro del equipo.
3. Actualizar miembro de equipo.
4. Eliminar miembro del equipo.
5. Copiar datos a fichero según la especificación realizada.
6. Realizar consultas indicadas.

Además, una vez seleccionado todos los elementos debemos obtener las siguientes consultas:
1. Listados de personal agrupados por entrenadores y jugadores.
2. El delantero más alto.
3. Media de goles de los delanteros.
4. Defensa con más partidos jugados.
5. Jugadores agrupados por su país de origen.
6. Entrenador con el mayor salario.
7. Promedio de altura de los jugadores agrupados por posición.
8. Listado de todos los jugadores que han anotado más de 10 goles.
9. Jugadores con un salario mayor al promedio del equipo.
10. Número total de partidos jugados por todos los jugadores.
11. Jugadores agrupados por el año de su incorporación al club.
12. Entrenadores agrupados por su especialidad.
13. Jugador más joven en el equipo.
14. Promedio de peso de los jugadores por posición.
15. Listado de todos los jugadores que tienen un dorsal par.
16. Jugadores que han jugado menos de 5 partidos.
17. Media de goles por partido de cada jugador.
18. Listado de jugadores que tienen una altura superior a la media del equipo.
19. Entrenadores que se incorporaron al club en los últimos 5 años.
20. Jugadores que han anotado más goles que el promedio de su posición.
21. Por posición, máximo de goles, mínimo de goles y media.
22. Estimación del coste total de la plantilla.
23. Total del salario pagado, agrupados por año de incorporación.
24. Jugadores agrupados por país y, dentro de cada grupo, el jugador con más partidos jugados.
25. Promedio de goles por posición, y dentro de cada posición, el jugador con el mayor número de
goles.
26. Entrenadores agrupados por especialidad, y dentro de cada especialidad, el entrenador con el
salario más alto.
27. Jugadores agrupados por década de nacimiento, y dentro de cada grupo, el promedio de partidos
jugados.
28. Salario promedio de los jugadores agrupados por su país de origen, y dentro de cada grupo, el
jugador con el salario más bajo y alto.

- Se debe entregar el proyecto funcional en ejecutable jar, configurable mediante ficheros de
configuración, con todos los elementos que lo formen testeados.
- Se debe seguir el modelo de trabajo con GitFlow/Git/Pull Request.
- Código totalmente documentado y con el uso de Logs
- Documentación que como mínimo tendrá 15 páginas en tamaño Apto o similar 11 e interlineado
simple, que incluya:
- Presentación del proyecto
- Presentación del equipo y reparto de tareas.
- Trello y gestión del trabajo. Análisis de riesgos.
- Captura del grafico de donde se muestre el modelo de flujo de trabajo GitFlow y se explique cómo
se ha integrado y resuelto los conflictos.
- Especificación de requisitos funcionales, no funcionales y de información de forma razonada.
- Diagrama de arquitectura de software.
- Herramientas tecnológicas usadas.
- Justificación de elecciones de cada uno de los elementos software existente justificando de las
opciones posibles y porqué se ha decantado el equipo por ella, justificado pros y contras de la
solución parcial aportada por dicho elemento.
- Principios SOLID aplicados y ejemplos de su implementación y uso en el código.
- Patrones aportados en la solución y ejemplos de uso.
- Ejemplos de ejecución del código
- Explicación de las consultas y ejemplos de salidas de cada una de ellas.
- Explicación teórico-práctica de cada prueba o conjunto de test relevantes realizados.
- Captura de la cobertura del código en test.
- Estimación económica de la ejecución del proyecto.
  
Fecha de entrega: 5 de marzo de 2025 a las 15:15, mediante repositorio con documentación en PDF y
código del ejemplo. Exposición de 10 minutos por grupo
