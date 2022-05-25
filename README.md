# Ahorcado-Alura-Challenge-Oracle-Next-Education !

![insignia alura](https://d335luupugsy2.cloudfront.net/cms%2Ffiles%2F10224%2F1644516322badge.png?utm_campaign=alura_latam_-_challenge_email_projeto_2_esp&utm_medium=email&utm_source=RD+Station)

## [Demostracion](https://danielo27.github.io/Ahorcado-Alura-Challenge-Oracle-Next-Education-/)


:bowtie: 2 Challenge Alura Programa One Oracle Next Education; para este challenge realice uso de:

 - [Normalize: Para resetear Estilos del Navegador](https://necolas.github.io/normalize.css/)
 - [Bootstrap Icons: Para algunos iconos de la interfaz](https://icons.getbootstrap.com/)

## Desarrollo :blush:

Para el responsive desing se hizo uso de media querys, por medio del cual se creo un input oculto y un boton para activar el teclado de los dispositivos que tuvieran pantalla tactil al pulsar este boton se realiza focus por medio del javascript en el input sin que el usuario se de cuenta y se empieza a capturar la entrada del input.

para detectar si el dispositivo es tactil hasta el momento la forma que se aplico es verificando el ancho de la pantalla del dispositivo, evidentemente esto es muy basico y puede producir errores de compatibilidad con algunos dispositivos pero es una forma temporal que pude evaluar si el dispositivo es una tablet o ipad o un dispositivo movil. la regla que se aplico es que si la pantalla del dispositivo es menor a 900px se puede considerar como un dispositivo movil.

<img src="https://www.seobility.net/en/wiki/images/6/6f/Media-Queries.png" alt="Width Devices display" />
[Imagen Tomada de Seobility](https://www.seobility.net/es/)

Esto pretendo cambiarlo mas adelante agregando una evaluacion de que tipo de dispositivo es, pero por el momento me ha funcionado bastante bien.

Tambien me parecio entretenido agreagar audio a los botones de la interfaz y a medida que el juego avanza agregue algunos sonidos mas para tener una mayor interaccion con el usuario.

## Responsive Desing :stuck_out_tongue_winking_eye:

En la carpeta Capture en el repositorio puden ver mas imagenes acerca de como se ve la interfaz en las diferentes pantallas.

|PC|MOVIL|TABLET|
|--|--|--|
|<img src="https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/PC_Add_Word.PNG" width="600px">| <img src="https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/Phone_Add_Words.png" width="200px">|<img src="https://raw.githubusercontent.com/Danielo27/Ahorcado-Alura-Challenge-Oracle-Next-Education-/main/capture/Tablet_Add_Word.png" width="300px">

El boton de keyboard y el input oculto para los dispositivos moviles solo se activa al detectar pantallas con un tamaño menor a 900px, Para dar el mensaje de que el usuario gano o perdio se creo un popup flotante que aun hay que mejorar para que se vea mucho mejor al usuario.

## Reparaciones :wrench:

- Se reparo el bug que hacia que el juego validara las teclas especiales como letras cuando se juega desde un pc.

## Agradecimientos :punch:

- Espero el proyecto les guste y cualquier aportacion sera bien recibida para mejorar el codigo.
- Agradecimientos al compañero @jhsalaz por informar acerca del bug que provocaba que las teclas especiles se validaran como letras.

**Desarrollado por Daniel Quintero Henriquez :sweat_smile:**
