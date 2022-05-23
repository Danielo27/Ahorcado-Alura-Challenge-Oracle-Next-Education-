# Ahorcado-Alura-Challenge-Oracle-Next-Education

2 Challenge Alura Programa One Oracle Next Education; para este challenge realice uso de normalize con el fin de resetera los estilos por defecto del navegador.

## Desarrollo

Para el responsive desing se hizo uso de media querys, por medio del cual se creo un input oculto y un boton para activar el teclado de los dispositivos que tuvieran pantalla tactil al pulsar este boton se realiza focus por medio del javascript en el input sin que el usuario se de cuenta y se empieza a capturar la entrada del input.

para detectar si el dispositivo es tactil hasta el momento la forma que se aplico es verificando el ancho de la pantalla del dispositivo, evidentemente esto es muy basico y puede producir errores de compatibilidad con algunos dispositivos pero es una forma temporal que pude evaluar si el dispositivo es una tablet o ipad o un dispositivo movil. la regla que se aplico es que si la pantalla del dispositivo es menor a 900px se puede considerar como un dispositivo movil.

<img src="https://www.seobility.net/en/wiki/images/6/6f/Media-Queries.png" alt="Width Devices display" />
[Imagen Tomada de Seobility](https://www.seobility.net/es/)

Esto pretendo cambiarlo mas adelante agregando una evaluacion de que tipo de dispositivo es pero por el momento me ha funcionado bastante bien.

Tambien me parecio entretenido agreagar audio a los botones de la interfaz y a medida que el juego avanza agregue algunos sonidos mas para tener una mayor interaccion con el usuario.

## Responsive Desing

En la carpeta Capture en el repositorio puden ver mas imagenes acerca de como se ve la interfaz en las diferentes pantallas.

|PC|MOVIL|TABLET|
|--|--|--|
|![Interfaz Pc](https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/PC_Add_Word.PNG)| ![Interfaz Iphone](https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/Phone_Add_Words.png) |![Interfaz Tablet](https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/Tablet_Add_Word.png)|
El boton de keyboard y el input oculto para los dispositivos moviles solo se activa al detectar pantallas con un tamaño menor a 900px.



**Desarrollado por Daniel Quintero Henriquez**
