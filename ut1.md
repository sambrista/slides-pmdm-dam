# UT 1

## Desarrollo de videojuegos

---

## Resultados de aprendizaje

------

Resultado de Aprendizaje 4: "Selecciona y prueba motores de juegos analizando la arquitectura de juegos 2D y 3D".

------

- Identificar los elementos que componen la arquitectura de un juego 2D y 3D.
- <!-- .element: class="fragment" -->Analizar los componentes de un motor de juegos.
- <!-- .element: class="fragment" -->Analizar entornos de desarrollo de juegos.

------

- Analizar diferentes motores de juegos, sus características y funcionalidades.
- <!-- .element: class="fragment" -->Identificar los bloques funcionales de un juego existente.
- <!-- .element: class="fragment" -->Reconocer la representación lógica y espacial de una escena gráfica sobre un juego existente.

------

Resultado de Aprendizaje 5: "Desarrolla juegos 2D y 3D sencillos utilizando motores de juegos".

------

- Establecer la lógica de un nuevo juego.
- <!-- .element: class="fragment" -->Crear los objetos necesarios para el juego y definir sus características.
- <!-- .element: class="fragment" -->Crear las escenas del juego y distribuir los objetos en las mismas.
- <!-- .element: class="fragment" -->Crear materiales para determinar las propiedades finales de la superficie de un objeto.

------

- Establecer las propiedades físicas de los objetos.
- <!-- .element: class="fragment" -->Incorporar sonido a los diferentes eventos del juego.
- <!-- .element: class="fragment" -->Utilizar cámaras y configurar la iluminación.

------

- Desarrollar e implantar juegos para dispositivos móviles.
- <!-- .element: class="fragment" -->Realizar pruebas de funcionamiento y optimización de los juegos desarrollados.
- <!-- .element: class="fragment" -->Documentar las fases de diseño y desarrollo de los juegos creados.

---

## 1. Introducción al desarrollo de videojuegos

------

- Un videojuego, según la RAE, es un "Juego electrónico que se visualiza en una pantalla".

- <!-- .element: class="fragment" -->De circuitos electrónicos básicos a superproducciones millonarias

------

Programadores, diseñadores y:

- <!-- .element: class="fragment" -->Compositores
- <!-- .element: class="fragment" -->Guionistas
- <!-- .element: class="fragment" -->Actores de doblaje
- <!-- .element: class="fragment" -->Animadores 3D y modelos
- <!-- .element: class="fragment" -->Traductores
- <!-- .element: class="fragment" -->Especialistas en marketing
- <!-- .element: class="fragment" -->...

------

### 1.1. Plataformas

------

- Ordenadores ("microordenadores" en los años 80): computadoras de uso general.
- <!-- .element: class="fragment" -->Videoconsolas: máquinas diseñadas específicamente para jugar videojuegos en el ámbito doméstico.
  - <!-- .element: class="fragment" -->hardware adicional: chips, sensores...
  - <!-- .element: class="fragment" -->Soportes: cartuchos, discos ópticos, tarjetas de memoria...
  - <!-- .element: class="fragment" -->Movilidad: sobremesa, portátiles o híbridas.

------

- Máquinas Arcade: máquinas de pago.
  - <!-- .element: class="fragment" -->Antiguamente muy populares
- <!-- .element: class="fragment" -->Smartphones y tablets

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más
    
[Arcade Planet](https://arcadeplanet.es/)

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

[Los lugares más insólitos donde se ha ejecutado 'Doom': cajeros, tests de embarazo, robots de cocina, osciloscopios o 'Minecraft'](https://www.xataka.com/videojuegos/lugares-insolitos-donde-se-ha-ejecutado-doom-cajeros-tests-embarazo-robots-cocina-osciloscopios-minecraft)

------

Plafatormas más populares:

- <!-- .element: class="fragment" -->Ordenadores:
  - <!-- .element: class="fragment" -->PC con Microsoft Windows
- <!-- .element: class="fragment" -->Videoconsolas
  - <!-- .element: class="fragment" -->Sony PlayStation 5
  - <!-- .element: class="fragment" -->Xbox Series X
  - <!-- .element: class="fragment" -->Nintendo Switch (Híbrida)
- <!-- .element: class="fragment" -->Smartphones y tablets:
  - <!-- .element: class="fragment" -->Dispositivos Apple (iPhone / iPad)
  - <!-- .element: class="fragment" -->Dispositivos con Sistema Operativo Android.

------

### 1.2. Evolución

------

#### 70s: Orígenes del videojuego

Las primeras videoconsolas aparecieron a principios de los 70. Eran dispositivos que se conectaban a la televisión, integraban los controles en la propia consola y ofrecian juegos muy básicos implementados con circuitos electrónicos.

------

Ejemplos son Atari Pong o Magnavox Oddisey.

------

- Desarrollo de juegos como software
- <!-- .element: class="fragment" -->Chips de memoria contenidos en cartuchos intercambiables.
- <!-- .element: class="fragment" -->Mejora de las características técnicas
- <!-- .element: class="fragment" -->Salones arcade
- <!-- .element: class="fragment" -->Resultado: BOOM del mercado de los videojuegos.

------

Ejemplos de consolas son:

- <!-- .element: class="fragment" -->Atari 2600
- <!-- .element: class="fragment" -->Colecovision

------

Ejemplos de juegos son:

- <!-- .element: class="fragment" -->Pacman
- <!-- .element: class="fragment" -->Pole Position
- <!-- .element: class="fragment" -->Space Invaders
- <!-- .element: class="fragment" -->Asteroids

------

#### 80s: Crisis del 83 y época de los 8 bits

- <!-- .element: class="fragment" -->Resultado del boom
- <!-- .element: class="fragment" -->Saturación de consolas y juegos
- <!-- .element: class="fragment" -->Juegos de dudosa calidad
- <!-- .element: class="fragment" -->Consecuencia: Crisis del 83-85.

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

Dice la leyenda que hay millones de videojuegos de Atari ET el extraterrestre y Pacman enterrados en el desierto de Alamogordo

------

- Japón: Consolas de 8 bits: Famicom (NES)
- <!-- .element: class="fragment" -->Estados Unidos (tras la crisis): NES
- <!-- .element: class="fragment" -->Europa: microordenadores (Commodore 64, Spectrum, Amstrad CPC...)

------


<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

Sello de calidad de Nintendo

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

1983 - 1992: **Edad de oro del software español**

------

A finales de esta década:

- <!-- .element: class="fragment" -->Primera videoconsola portátil exitosa: Nintendo Game Boy
- <!-- .element: class="fragment" -->Se populariza el PC de IBM (y clónicos) frente a los microordenadores

------

Ejemplos de videojuegos:

- <!-- .element: class="fragment" -->Super Mario Bros
- <!-- .element: class="fragment" -->Bubble Bobble
- <!-- .element: class="fragment" -->Tetris.
- <!-- .element: class="fragment" -->Manic Miner
- <!-- .element: class="fragment" -->La Abadía del Crimen

------

#### 90s: Generación de 16 bits y revolución del 3D

------

- Primeras consolas de 16 bits (Super Nintendo, Mega Drive de Sega...)
  - Mejora en gráficos, colores, sonido...
- CD-ROMs frente a cartuchos y disquettes
- Joysticks analógicos
- Vibración

------

**GRÁFICOS 3D**

- <!-- .element: class="fragment" -->PCs con tarjeta gráfica 3D
- <!-- .element: class="fragment" -->consolas
  - <!-- .element: class="fragment" -->Sony Playstation (32 bits)
  - <!-- .element: class="fragment" -->Nintendo 64 (64 bits)

------

Ejemplos de videojuegos:

- <!-- .element: class="fragment" -->Super Mario Kart
- <!-- .element: class="fragment" -->Sonic the HedgeHog
- <!-- .element: class="fragment" -->Final Fantasy VII
- <!-- .element: class="fragment" -->Metal Gear Solid
- <!-- .element: class="fragment" -->Super Mario 64
- <!-- .element: class="fragment" -->The Legend of Zelda, Ocarina of Time
- <!-- .element: class="fragment" -->Starcraft
- <!-- .element: class="fragment" -->Quake.

------

#### 2000 hasta la actualidad: internet y smartphones

------

Desde la aparición de los gráficos 3D no se ha producido ninguna otra revolución de tal envergadura. Las plataformas han ido mejorando sus capacidades gráficas y de procesamiento, de modo que los gráficos son cada vez más realistas y permiten representar más elementos en pantalla, y la llegada de internet a los hogares supuso la popularización del juego en línea, que ha llegado a superar en muchos casos al juego local.

Por otro lado, aparecen los teléfonos móviles con Java y posteriormente los smartphones Apple y Android, que suponen la llegada de una nueva plataforma con identidad propia.

Algunas de las tendencias actuales son:

- **DLCs y compras en el juego**: internet posibilita que tras adquirir el juego se pueda comprar contenido descargable (niveles, personajes, skins...) e incluso items (armas, armaduras...) que dan ventajas respecto al resto de jugadores. En el caso de los videojuegos para móviles, es muy común que estos requieran esperar grandes cantidades de tiempo, que se pueden acortar pagando.
- **Stores y abandono del modelo físico**: las plataformas permiten comprar y descargar juegos online, y las ofertas suelen ser más agresivas que los formatos tradicionales de discos, cartuchos... de modo que estos formatos son cada vez menos populares. Algunas plataformas ofrecen suscripciones, de modo que una mensualidad da acceso ilimitado a un catálogo de títulos.
- **Realidad Virtual**: Han aparecido plataformas que ofrecen realidad virtual a través de gafas, como Playstation VR o Meta Quest. Pese a que la experiencia es revolucionaria, su alto precio frena su difusión entre los jugadores.
- **Juego en la nube**: Esta tecnología consiste en que el juego se ejecuta en servidores online, haciendo prácticamente independiente el juego del dispositivo en el que se juega. Esto permite convertir cualquier dispositivo en una videoconsola o PC de última generación, o jugar en una plataforma a juegos de otras. Algunos ejemplos son Google Stadia (fallido), Amazon Luna o Playstation Now. 
- **Boom de la nostalgia**: Se ha popularizado el desarrollo de versiones remasterizadas de videojuegos antiguos, de remakes (videojuegos hechos de nuevo con la tecnología actual) y de videojuegos de estética pixelada.
- **Auge de los juegos indies**: los videojuegos indies o independientes son videojuegos realizados por grupos reducidos de desarrolladores o empresas pequeñas, que se caracterizan por ser innovadores y tener un precio menor frente a los títulos de las grandes distribuidoras. En ocasiones recaudan el dinero necesario para su desarrollo a partir de crowdfunding. En los últimos años han aparecido títulos muy exitosos como Minecraft, Stardew Valley o Undertale.

### 1.3. Desarrollo y publicación

#### Desarrollo

El proceso de desarrollo de un videojuego varía en función de la plataforma para la que este se desarrolla, de modo que uno de los primeros pasos es elegir para qué plataforma o plataformas queremos desarrollar el juego. En el caso de plataformas cerradas, en las que la compañía controla los videojuegos que se lanzan para esta, es posible que tengamos que contactar con la compañía y esperar a que acepten nuestro proyecto de videojuego.

El siguiente paso consiste en decidir si vamos a utilizar un motor de juego o trabajar directamente con el SDK (Software Development Kit, Kit de Desarrollo de Software) de la plataforma. Un motor de juegos es un framework diseñado para el desarrollo de juegos, que incluye librerías y sofware de soporte (como editores de niveles) que facilitan la tarea. Tanto en el caso del motor como del SDK, es posible que haya que pagar o registrarse como desarrollador para tener acceso a él.

Una vez se dispone del motor o el SDK comienza el desarrollo propiamente dicho. Este se lleva a cabo en ordenadores, pero para hacer pruebas, debug... se puede usar:

- Un emulador, si está disponible.
- Un dispositivo de dicha plataforma, si tenemos acceso y este nos permite ejecutar nuestras propias aplicaciones.
- Un kit de desarrollo (o devkit), que es una versión ampliada para desarrollo del dispositivo de la plataforma.

Por último, una vez se ha desarrollado el juego, este puede ser generado y publicado.

#### Publicación

La publicación consiste en la puesta a disposición del público de nuestro videojuego, y varía según el tipo de dispositivo. En general las opciones son:

##### Stores digitales

Se contacta con una store para que esta distribuya el juego a cambio normalmente de una comisión. Es el modo de publicar y distribuir más utilizado hoy en día.

##### Venta de copias físicas

Este método hoy en día sólo es popular (y cada vez menos) en videoconsolas. Se necesitaría una empresa que fabrique las copias físicas y otra (que puede ser la misma) que se encargue de la distribución. La inversión necesaria para la producción junto con la tendencia de los usuarios a comprar copias digitales hace que esta opción hoy en día sólo sea atractiva para videojuegos de grandes compañías.
