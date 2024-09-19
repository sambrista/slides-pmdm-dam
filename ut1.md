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

1983 - 1992: Edad de oro del software español

------

# Para saber más

[Desarrollo en máquinas limitadas](https://www.youtube.com/watch?v=ZWQ0591PAxM)

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

GRÁFICOS 3D

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
- <!-- .element: class="fragment" -->Quake

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

### 1.3. Géneros

- <!-- .element: class="fragment" -->Acción: GTA V, Devil May Cry 5
- <!-- .element: class="fragment" -->Aventura: The Legend of Zelda Breath of the Wild, Detroit: Become Human
- <!-- .element: class="fragment" -->RPG: Final Fantasy VII, The Witcher 3
- <!-- .element: class="fragment" -->MMORPG: World of Warcraft, Guild Wars 2
- <!-- .element: class="fragment" -->FPS: Call of Duty: Modern Warfare, DOOM

------

- <!-- .element: class="fragment" -->Plataformas: Super Mario Oddisey, Rayman Origins
- <!-- .element: class="fragment" -->Lucha: Mortal Kombat 11, Street Fighter V
- <!-- .element: class="fragment" -->Deportes: EA Sports FC 25, NBA 2K25
- <!-- .element: class="fragment" -->Carreras: Mario Kart 8, Forza Horizon 5

------

- <!-- .element: class="fragment" -->RTS: StarCraft II, Age of Empires IV
- <!-- .element: class="fragment" -->Simulación: The Sims 4, Microsoft Flight Simulator
- <!-- .element: class="fragment" -->Survival Horror: Resident Evil 2 Remake, Silent Hill 2
- <!-- .element: class="fragment" -->Metroidvania: Hollow Knight, Metroid Dread

------

### 1.4. Desarrollo y publicación

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

---

## 2. Motores de videojuegos

------

Un motor de videojuegos es un conjunto de herramientas, bibliotecas y entornos de desarrollo diseñados para facilitar la creación de videojuegos. En lugar de desarrollar un juego desde cero, un motor proporciona componentes preconstruidos que agilizan el proceso de desarrollo, evitando a los desarrolladores tener que reinventar elementos básicos del sistema.

------

- A veces son diseñados por grandes compañías para videojuegos específicos (Unreal, CryEngine).
- A veces son creados para que los desarrolladores los usen (Unity, Godot).

------

### 2.1. Videojuegos 2D y 3D

------

#### Videojuegos 2D

------

- Los gráficos se representan en dos dimensiones: anchura y altura (x e y), y los personajes, objetos entornos... son ilustracionesestán dibujados en un entorno plano.
- Para dibujar esos personajes, objetos entornos... se utilizan sprites o ilustraciones bidimensionales. 
- Los entornos y personajes son planos, con perspectiva limitada (aunque algunos juegos usan técnicas como parallax para simular profundidad).
- Las animaciones en 2D suelen ser hechas cuadro por cuadro o usando esqueletos 2D.
- La perspectiva es fija, generalmente en una vista lateral (side-scrolling), de arriba hacia abajo (top-down) o vista isométrica.
- El jugador normalmente no puede rotar la cámara; todo el juego ocurre dentro de un único plano.
- Los movimientos de los personajes están limitados a los ejes X e Y, lo que significa que el jugador normalmente solo puede moverse de izquierda a derecha, arriba o abajo.
- El desarrollo de juegos 2D suele ser más sencillo y rápido en términos de creación de activos visuales y programación, y los costos de producción pueden ser más bajos debido a la menor complejidad en la creación de gráficos y animaciones.
- Las físicas y la inteligencia artificial son más simples porque el movimiento está limitado a dos ejes.
- Generalmente, los juegos 2D requieren menos potencia de procesamiento y memoria gráfica. En consecuencia, pueden correr bien en dispositivos más antiguos o con menor capacidad.
- Aunque algunos juegos 2D pueden ser visualmente impresionantes, su capacidad de inmersión está más limitada en comparación con los juegos 3D debido a la falta de profundidad visual. Sin embargo, muchos juegos 2D tienen estilos artísticos únicos y atractivos que no pueden replicarse en 3D.

------

#### Videojuegos 3D

------

Los videojuegos 3D presentan las siguientes características:

- Los gráficos se representan en tres dimensiones: ancho, alto y profundidad (X, Y y Z). Utilizan modelos tridimensionales para representar personajes y objetos, creados mediante mallas poligonales con texturas, que son capaces de moverse y rotar en un espacio tridimensional.
- Los entornos 3D permiten cámaras que se pueden mover en diferentes ángulos, lo que ofrece una vista más dinámica. La cámara es dinámica y puede moverse libremente en diferentes direcciones, ofreciendo vistas en primera persona, tercera persona, o vistas desde ángulos personalizados.
- Las animaciones en 3D suelen basarse en sistemas de esqueleto (rigging) y física simulada.
- Los entornos pueden ser explorados en todas las direcciones, y la cámara puede rotar alrededor de los personajes.
- Los personajes pueden moverse en los ejes X, Y y Z, permitiendo la exploración en cualquier dirección.
- El desarrollo de juegos 3D es más complejo y requiere más recursos. Se necesitan artistas 3D, animadores, ingenieros especializados en gráficos y motores más potentes.
- Las físicas y las colisiones en 3D son más complicadas de simular, ya que se debe tener en cuenta la profundidad y el movimiento en el eje Z.
- Los entornos 3D requieren de optimización avanzada, como la reducción de polígonos, uso eficiente de luces y sombras, y técnicas para cargar datos de manera progresiva.
- Los efectos de iluminación, sombras y texturas en 3D suelen ser más avanzados, contribuyendo a una experiencia más envolvente.
- Los juegos 3D, debido a su complejidad gráfica, suelen demandar más recursos del sistema, como una GPU potente, más memoria y mejores procesadores.
- Los motores de juegos 3D necesitan optimizaciones más avanzadas, como el uso de técnicas de renderizado como la occlusión culling (no dibuja objetos que no se ven porque otros elementos los tapan), mapeo de sombras y LOD (nivel de detalle) (simplifica el detalle de los objetos lejanos).

------

!!!info Para saber más
    La niebla que caracteriza la atmósfera del videojuego Silent Hill se creó para aligerar la carga del renderizado de las escenas.

------

- Los gráficos en 3D pueden ofrecer una mayor inmersión al jugador, ya que se simula un entorno más realista donde el jugador puede explorar y ver objetos desde diferentes ángulos.