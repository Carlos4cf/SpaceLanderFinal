# SpaceLanderFinal
First game about landing a rocket

**Primera revisión 1.1**

Como primera visualización he leido el .pdf con las características, que nuestro cliente (Jordi) nos ha proporcionado.
En los bocetos de la visualización horizontal el fondo, el suelo de la luna y el cohete han sido colocados de forma correcta. Aunque estéticamente no encajan. He tenido que recortar las imagenes para quitarles el fondo menos la nave que estaba con fondo transparente.
El siguiente punto clave, han sido los iconos de "Volumen", "Play", "Configuración" y "Controles" no concuerdan con el resto de la pantalla en estilo y diseño entre ellos. Los iconos tienen fondo blanco y son demasiado grandes, estamos hablando de cambiar las imagenes o reducirlas para que queden de acuerdo a la pantalla y que la linea de los botones sea parecida entre ellos. En cuanto al marcador, sólo hay representado en el .pdf lo que quiere que aparezca, por lo que tendré que ponerme de acuerdo con el cliente para concretar los aspectos técnicos del marcador.
Los iconos que serán botones de los controles estarán dentro de Divs. Los menus tanto de la pantalla vertical como la de la horizontal serán desplegables.

**Segunda revisión 1.2**

La imagen de la luna que el cliente solicitó, tiene unas manchas en la imagen y no era del todo nítida. Por lo que hemos acordado cambiar la imagen. Le he enseñado 3 propuestas y hemos elegido una nueva y la hemos implementado, es muy similar a la que ellos nos habían entregado.
He ajustado el tamaño de la imagen porque estaba descompensado con el resto.
El icono de volumen solo servirá para desde el juego poner o quitar el volumen, con lo que con dos imágenes solucionaremos esto.

**Tercera revisión 1.3**

Hemos puesto los menús de forma desplegable en la pantalla horizontal de forma descendente a la izquierda. En la pantalla vertical el menú desplegable de forma horizontal. La primera plantilla no contemplaba un menu desplegable pero hemos acordado que es mucho más elegante que sea un menú desplegable con iconos.
En el marcador hemos concretado que sera un marco blanco y dentro estará la "velocidad", "altura" y "fuel".
En el menú la opción de ajustes nos enseñara las instrucciones y el desarrollador del juego, que se abrirá en otro documento .html y tendrá un botón central que servirá para volver al juego.

*CAMBIOS VERSIÓN FINAL*

**Cuarta revisión 1.4**  ¡CAMBIOS IMPORTANTES!

Después de tener encaminado el diseño del juego, hemos incorporado el JavaScript y eso nos ha obligado a realizar una serie de cambios en la estructura. Para empezar hemos querido mantener la esencia en cuanto al diseño de las primeras páginas, los iconos e imagenes son las mismas adaptadas. Hemos incorporado un panel en la parte superior izquierda donde aparecen la velocidad, fuel y altura que van modificandose en relación a la posición de la nave. Justo debajo tenemos el botón de ajustes que no detiene el juego y abre un pequeño menú en la parte superior derecha de la pantalla con las opciones de volver, play, niveles, instrucciones y el acerca de. Todas estas opciones de menú corresponden a los iconos predeterminados. Otro aspecto es el de incorporar un boton de reinico del juego justo debajo del icono de ajustes.

**Quinta revisión 1.5**

En esta actualización hemos intentado pulir un poco el juego. Hemos hecho que los botones al pasar el puntero sobre ellos se agranden un poco para saber que estás sobre ese icono. Hemos introducido 3 niveles de dificultad EASY, NORMAL e INSANE, donde la velocidad de la nave varía. En este punto no he podido encontrar la forma de hacer un solo JS y he tenido que hacer 3 JS uno para cada nivel de dificultad. Por último se han modificado los tamaños de los iconos para que cuadren con el resto del juego y sean proporcionales.

**Última revisión**

Funciones del juego:

**1:** La nave sube y baja hasta tocar el suelo lunar o que el fuel se acabe. Tiene 100L de fuel y debe aterrizar para no explotar a una velocidad máxima de 5 m/s.

**2:** Hay 3 niveles de dificultad, en cada nivel la dificultad cambia. Se ha cambiado la velocidad de la nave para que sea más difícil aterrizar.

**3:** Los botones reaccionan al pasar el ratón por encima de ellos para saber a cual estás clickando.

**4:** El acerca de incluye dos enlace a páginas que se han consultado para ayudar al desarollo del juego.

**5:** Si explota, muestra una explosión y al cabo de 2 segundos muestra por pantalla un mensaje de GAME OVER.

**6:** Cuando aterrizas correctamente salta una ventana emergente que te indica que has aterrizado correctamente y además a la velocidad a la que has aterrizado.

**7:** El botón de reinicio permite reinicar la partida cuando el usuario determine. Puede acceder desde la página principal o desde el menú desplegable.
