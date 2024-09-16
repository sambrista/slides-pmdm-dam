# UT 1

## Desarrollo de videojuegos

---

## Resultados de aprendizaje

------

Resultado de Aprendizaje 4: "Selecciona y prueba motores de juegos analizando la arquitectura de juegos 2D y 3D".

------

- Identificar los elementos que componen la arquitectura de un juego 2D y 3D.
- Analizar los componentes de un motor de juegos.
- Analizar entornos de desarrollo de juegos.

------

- Analizar diferentes motores de juegos, sus características y funcionalidades.
- Identificar los bloques funcionales de un juego existente.
- Reconocer la representación lógica y espacial de una escena gráfica sobre un juego existente.

------

Resultado de Aprendizaje 5: "Desarrolla juegos 2D y 3D sencillos utilizando motores de juegos".

------

- Establecer la lógica de un nuevo juego.
- Crear los objetos necesarios para el juego y definir sus características.
- Crear las escenas del juego y distribuir los objetos en las mismas.
- Crear materiales para determinar las propiedades finales de la superficie de un objeto.

------

- Establecer las propiedades físicas de los objetos.
- Incorporar sonido a los diferentes eventos del juego.
- Utilizar cámaras y configurar la iluminación.

------

- Desarrollar e implantar juegos para dispositivos móviles.
- Realizar pruebas de funcionamiento y optimización de los juegos desarrollados.
- Documentar las fases de diseño y desarrollo de los juegos creados.

---

## 1. Introducción al desarrollo de videojuegos

------

- Un videojuego, según la RAE, es un "Juego electrónico que se visualiza en una pantalla".

- De circuitos electrónicos básicos a superproducciones millonarias

------

Programadores, diseñadores y:

- Compositores
- Guionistas
- Actores de doblaje
- Animadores 3D y modelos
- Traductores
- Especialistas en marketing
- ...

------

### 1.1. Plataformas

------

- **Ordenadores** ("microordenadores" en los años 80): computadoras de uso general.
- **Videoconsolas**: máquinas diseñadas específicamente para jugar videojuegos en el ámbito doméstico.
  - **hardware adicional**: chips, sensores...
  - **Soportes**: cartuchos, discos ópticos, tarjetas de memoria...
  - **Movilidad**: sobremesa, portátiles o híbridas.

------

- **Máquinas Arcade**: máquinas de pago.
  - Antiguamente muy populares.
- **Smartphones y tablets**

------

!!!info Para saber más
    En Sevilla se encuentra [Arcade Planet](https://arcadeplanet.es/), uno de los salones arcade más grandes de Europa, donde por poco dinero podemos disfrutar de una gran colección de máquinas arcade (nuevas, antiguas, de importación...).

------

*[FPS]: First Person Shooter
!!!info Para saber más
    El videojuego Doom, desarrollado principalmente por John Carmack y John Romero en 1993, es uno de los videojuegos más famosos y se considera uno de los pioneros del género [FPS]. En 1999 su motor fue publicado como software libre y desde entonces entusiastas de la programación y la electrónica han intentado ejecutarlo en dispositivos de todo tipo. Podemos encontrar algunos ejemplos en: [Los lugares más insólitos donde se ha ejecutado 'Doom': cajeros, tests de embarazo, robots de cocina, osciloscopios o 'Minecraft'](https://www.xataka.com/videojuegos/lugares-insolitos-donde-se-ha-ejecutado-doom-cajeros-tests-embarazo-robots-cocina-osciloscopios-minecraft)

------

Plafatormas más populares:

- Ordenadores:
  - PC con Microsoft Windows
- Videoconsolas
  - Sony PlayStation 5
  - Xbox Series X
  - Nintendo Switch (Híbrida)
- Smartphones y tablets:
  - Dispositivos Apple (iPhone / iPad)
  - Dispositivos con Sistema Operativo Android.

------

### 1.2. Evolución

------

#### 70s: Orígenes del videojuego

Las primeras videoconsolas aparecieron a principios de los 70. Eran dispositivos que se conectaban a la televisión, integraban los controles en la propia consola y ofrecian juegos muy básicos implementados con circuitos electrónicos.

------

Ejemplos son Atari Pong o Magnavox Oddisey.

------

- Desarrollo de juegos como software
- Chips de memoria contenidos en cartuchos intercambiables.
- Mejora de las características técnicas
- Salones arcade
- Resultado: BOOM del mercado de los videojuegos.

------

Ejemplos de consolas son Atari 2600 y Colecovision.
Ejemplos de juegos son PacMan, Pole Position, Space Invaders y Asteroids.

------

#### 80s: Crisis del 83 y época de los 8 bits

- Resultado del boom
- Saturación de consolas y juegos
- Juegos de dudosa calidad
- Consecuencia: Crisis del 83-85.

------

!!!info Para saber más
    En 1983 se enterraron en el desierto de Alamogordo en EEUU gran cantidad de copias de los juegos de Atari *ET el Extraterrestre* y *Pacman*, ya que se fabricaron millones de unidades pero las ventas fueron mucho peor de lo esperado (menos de la mitad en el caso de Pacman), a lo que se sumó las devoluciones por la pésima calidad de los productos.

------

En Japón triunfaron las consolas de 8 bits, con la Nintendo Famicom (llamada Nintendo Entertainment System o NES en occidente) como consola estrella. Esta consola también triunfó en Estados Unidos tras la crisis. Por otro lado, en Europa tuvieron más éxito los microordenadores, como el Commodore 64, el Spectrum o el Amstrad CPC.

!!!info Para saber más
    Nintendo llevó una política de control de calidad muy rigurosa sobre los juegos que se publicaban para su consola. Para ello diseño un sello de calidad que hoy dia sigue luciendo en sus juegos.

!!!info Para saber más
   Entre 1983 y 1992 aproximadamete tuvo lugar la conocida como **Edad de oro del software español**. La llegada de los microordenadores domésticos supuso la primera toma de contacto con la programación para muchos usuarios, que se interesaron en crear sus propios juegos. España llego a ser uno de los mayores productores europeos de videojuegos para microordenaores de 8 bits (principalmente para Spectrum).

A finales de esta década se lanza la Nintendo Game Boy, que se considera la primera videoconsola portátil exitosa, y los microordenadores empiezan a ser reemplazados por ordenadores basados en el PC de IBM.

Ejemplos de videojuegos de esta época son Super Mario Bros, Bubble Bobble o Tetris.

#### 90s: Generación de 16 bits y revolución del 3D

A finales de los 80 y principio de los 90s aparecen las primeras consolas de 16 bits (Super Nintendo, Mega Drive de Sega...), las cuales suponen una mejora en gráficos, colores, sonido... considerable. Otras innovaciones fueron el uso de CD-ROMs como soporte de juegos, en lugar de cartuchos o disquettes, el uso de joysticks analógicos o la vibración como refuerzo háptico. Sin embargo, la revolución principal fue la popularización de los juegos con gráficos 3D, ya sea en PCs con tarjeta gráfica 3D o en consolas como la Sony Playstation, de 32 bits, o la Nintendo 64, de 64 bits.

Ejemplos de videojuegos de este periodo son Super Mario Kart, Sonic the HedgeHog, Final Fantasy VII, Metal Gear Solid, Super Mario 64, The Legend of Zelda, Ocarina of Time, Starcraft y Quake.

#### 2000 hasta la actualidad: internet y smartphones

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
