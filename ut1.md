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

- <!-- .element: class="fragment" -->Conectadas a una TV.
- <!-- .element: class="fragment" -->Controles en la propia consola
- <!-- .element: class="fragment" -->Juegos muy básicos
- <!-- .element: class="fragment" -->Circuitos electrónicos.

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
  - <!-- .element: class="fragment" -->Mejora en gráficos, colores, sonido...
- <!-- .element: class="fragment" -->CD-ROMs frente a cartuchos y disquettes
- <!-- .element: class="fragment" -->Joysticks analógicos
- <!-- .element: class="fragment" -->Vibración

<!-- .element: class="fragment" -->... Pero la gran revolución fue...

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


- Mejora de capacidades gráficas y de procesamiento
  - <!-- .element: class="fragment" -->Gráficos más realistas
  - <!-- .element: class="fragment" -->Más elementos en pantalla
- <!-- .element: class="fragment" -->Internet: juego en línea
- <!-- .element: class="fragment" -->Teléfonos móviles con Java, smartphones y tablets.

------

Algunas de las tendencias actuales son:

- <!-- .element: class="fragment" -->DLCs y compras en el juego
- <!-- .element: class="fragment" -->Stores y abandono del modelo físico
- <!-- .element: class="fragment" -->Realidad Virtual
- <!-- .element: class="fragment" -->Juego en la nube
- <!-- .element: class="fragment" -->Boom de la nostalgia
- <!-- .element: class="fragment" -->Auge de los juegos indies

------

### 1.3. Desarrollo y publicación

------

#### Desarrollo

------

1. Elegir plataforma (y pedir permiso)
2. <!-- .element: class="fragment" -->¿SDK? ¿Motor de juego?
3. <!-- .element: class="fragment" -->Desarrollo y prueba
  - <!-- .element: class="fragment" -->Emulador
  - <!-- .element: class="fragment" -->Dispositivo
  - <!-- .element: class="fragment" -->Devkit
4. <!-- .element: class="fragment" -->Generar y publicar juego

------

#### Publicación

- <!-- .element: class="fragment" -->Stores digitales
- <!-- .element: class="fragment" -->Copias físicas