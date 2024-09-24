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

**Para saber más**

[Arcade Planet](https://arcadeplanet.es/)

------

<!-- .slide: data-background-color="#dddddd" -->

**Para saber más**

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

**Para saber más**

Dice la leyenda que hay millones de videojuegos de Atari ET el extraterrestre y Pacman enterrados en el desierto de Alamogordo

------

- Japón: Consolas de 8 bits: Famicom (NES)
- <!-- .element: class="fragment" -->Estados Unidos (tras la crisis): NES
- <!-- .element: class="fragment" -->Europa: microordenadores (Commodore 64, Spectrum, Amstrad CPC...)

------

<!-- .slide: data-background-color="#dddddd" -->

**Para saber más**

Sello de calidad de Nintendo

------

<!-- .slide: data-background-color="#dddddd" -->

**Para saber más**

1983 - 1992: Edad de oro del software español

------

**Para saber más**

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
- <!-- .element: class="fragment" -->... Pero la gran revolución fue...

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

- Creados por grandes compañías para videojuegos específicos (Unreal, CryEngine).
- <!-- .element: class="fragment" -->Creados para desarrolladores (Unity, Godot).

------

### 2.1. Arquitectura de un videojuego

------

- Interfaz de usuario
- <!-- .element: class="fragment" -->Recursos o assets: sprites, texturas, tiles, sonidos, imágenes...
- <!-- .element: class="fragment" -->Lógica del juego: EL BUCLE
  - <!-- .element: class="fragment" -->Eventos del usuario
  - <!-- .element: class="fragment" -->Actualizar el juego
    - <!-- .element: class="fragment" -->Acciones del jugador
    - <!-- .element: class="fragment" -->Eventos de otros elementos del juego
    - <!-- .element: class="fragment" -->Colisiones
    - <!-- .element: class="fragment" -->Animaciones
  - <!-- .element: class="fragment" -->Renderizar la escena (frame).

------

### 2.2. Videojuegos 2D y 3D

------

#### Videojuegos 2D

------

- Dos dimensiones: anchura y altura (x e y). Personajes, objetos entornos... son ilustraciones.
- <!-- .element: class="fragment" -->Sprites o ilustraciones bidimensionales.
- <!-- .element: class="fragment" -->Entornos y personajes son planos, con perspectiva limitada. Profundidad por parallax.
- <!-- .element: class="fragment" -->Animaciones 2D por cuadro o con esqueletos 2D.

------

- Perspectiva fija. Vista lateral (side-scrolling), de arriba hacia abajo (top-down) o vista isométrica.
- <!-- .element: class="fragment" -->El jugador normalmente no puede rotar la cámara.
- <!-- .element: class="fragment" -->El jugador normalmente solo puede moverse de izquierda a derecha, arriba o abajo.
- <!-- .element: class="fragment" -->Desarrollo más sencillo y rápido. Costos más bajos.

------

- Físicas e IA más simples debido al movimiento.
- <!-- .element: class="fragment" -->Menos potencia de procesamiento y memoria gráfica. Requerimientos menores.
- <!-- .element: class="fragment" -->Menos capacidad de inmersión, pero permiten estilos artísticos únicos y atractivos

------

#### Videojuegos 3D

------

Los videojuegos 3D presentan las siguientes características:

- Tres dimensiones: ancho, alto y profundidad (x, y e z).
- <!-- .element: class="fragment" -->Modelos tridimensionales para personajes y objetos. Mallas poligonales con texturas. Movimiento y rotación.
- <!-- .element: class="fragment" -->Cámaras móviles. Primera persona, tercera persona, ángulos personalizados.
- <!-- .element: class="fragment" -->Animaciones en 3D: esqueletos (rigging) y física simulada.

------

- Movimiento en los ejes x, y e z. Entornos explorables en todas las direcciones.
- <!-- .element: class="fragment" -->Físicas y colisiones más complicadas.
- <!-- .element: class="fragment" -->Desarrollo más complejo. Necesita motores más potentes, recursos y personal: artistas 3D, animadores, ingenieros especializados en gráficos...

------

- Complejidad gráfica. Necesitan GPU potente, memoria y procesador.
- <!-- .element: class="fragment" -->Optimizaciones avanzadas: técnicas de renderizado (occlusión culling), mapeo de sombras, LOD...
- <!-- .element: class="fragment" -->Experiencia más envolvente gracias a efectos de iluminación, sombras y texturas

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

Niebla en Silent Hill

------

#### 2.3. Tipos de motores y utilización

------

- Dimensiones gráficas
- <!-- .element: class="fragment" -->Género
- <!-- .element: class="fragment" -->Licencia
- <!-- .element: class="fragment" -->Plataforma
- <!-- .element: class="fragment" -->Precio

------

<!-- .slide: data-background-color="#dddddd" -->

# Actividad 1.1.

------

#### 2.4. Áreas de especialización, librerías y lenguajes de programación

------

##### Librerías gráficas

------

- OpenGL: API multiplataforma para gráficos 2D y 3D en tiempo real.
- <!-- .element: class="fragment" -->DirectX: API de Microsoft con un fuerte enfoque en gráficos 3D, usada en Windows y Xbox.
- <!-- .element: class="fragment" -->Vulkan: API de bajo nivel para gráficos de alto rendimiento, ideal para sistemas multihilo.
- <!-- .element: class="fragment" -->Metal: API gráfica de bajo nivel exclusiva para macOS e iOS.
- <!-- .element: class="fragment" -->SDL (Simple DirectMedia Layer): Librería para gráficos 2D, usada en motores más ligeros.
- <!-- .element: class="fragment" -->WebGL: Versión de OpenGL para renderizado en navegadores web.

------

##### Librerías de física

------

Estas librerías permiten simular comportamientos físicos, como la colisión, la gravedad, y la interacción de objetos en un entorno 3D o 2D.

------

- Box2D: Motor de física 2D ampliamente utilizado en juegos indie y motores como Unity y Godot.
- <!-- .element: class="fragment" -->Bullet Physics: Motor de física 3D utilizado en muchos motores, incluido Unreal Engine.
- <!-- .element: class="fragment" -->Havok: Motor de física de alto rendimiento usado en juegos AAA como Halo, Assassin’s Creed, y más.
- <!-- .element: class="fragment" -->PhysX: Librería de NVIDIA para simulación de física, integrada en Unreal Engine y Unity.
- <!-- .element: class="fragment" -->Chipmunk2D: Motor de física ligero para juegos 2D, utilizado en juegos móviles y proyectos indie.

------

##### Lenguajes de programación

------

- C++: Es el lenguaje más utilizado en el desarrollo de videojuegos de alto rendimiento, especialmente en juegos AAA.
- <!-- .element: class="fragment" -->C#: Es el lenguaje de programación principal en Unity, uno de los motores de juegos más populares, especialmente para juegos indie, móviles y en desarrollo multiplataforma.
- <!-- .element: class="fragment" -->Python: Es muy popular en juegos casuales, prototipos, y motores de juego más pequeños.
- <!-- .element: class="fragment" -->Java: Popular en el desarrollo de juegos móviles (especialmente en Android) y juegos para web.
- <!-- .element: class="fragment" -->JavaScript:  se utiliza principalmente para el desarrollo de juegos web y móviles. Con la evolución de HTML5 y WebGL, es una opción viable para juegos 2D y 3D en navegadores.
- <!-- .element: class="fragment" -->Lua: lenguaje ligero usado para scripting dentro de muchos motores de juegos, especialmente aquellos que necesitan un lenguaje embebido.

------

#### 2.5. Componentes de un motor de juego

------

- Motor gráfico (R)enderizado 2D/3D, Sombras, iluminación y efectos...).
- Motor de física (Colisiones, Simulación física)

- Motor de animación: Se encarga de generar las animaciones. Algunos ejemplos:
  - Animación de personajes: Controla los esqueletos (rigs) y la interpolación de animaciones, tanto en modelos 3D como en sprites 2D.
  - Interpolación y blending: Suaviza las transiciones entre diferentes animaciones, como caminar y correr.

- Sistema de audio: Se encarga de la reproducción de sonidos y música.
  - Efectos de sonido: Maneja la reproducción de sonidos específicos, como disparos o explosiones.
  - Música: Maneja la reproducción de música de fondo.
  - Audio espacial: Simula cómo se escucha el sonido en diferentes ubicaciones y distancias dentro del juego.

- Sistema de entrada: Se encarga de recoger la entrada del usuario.
  - Control de dispositivos: Maneja las entradas del jugador a través de teclados, ratones, controladores o dispositivos táctiles.
  - Mapeo de controles: Permite asignar acciones en el juego a diferentes botones o teclas.

- Inteligencia Artificial (IA): Se encarga de dotar de inteligencia a los NPC, enemigos...
  - Navegación: Determina cómo los NPCs (personajes no jugables) se mueven y navegan por el entorno del juego.
  - Comportamiento: Define cómo actúan y reaccionan los NPCs en función de las acciones del jugador o del entorno.

- Sistema de scripts: Permite personalizar con código el desarrollo del videojuego y el comportamiento de los elementos.
  - Lógica del juego: Permite que los desarrolladores definan las reglas y mecánicas del juego a través de un lenguaje de scripting como Lua, Python o C#.
  - Interactividad: Controla los eventos y respuestas dentro del juego en función de las acciones del jugador.

- Sistema de redes (opcional): Da soporte al juego en línea.
  - Multijugador: Maneja la comunicación entre jugadores en diferentes dispositivos o ubicaciones a través de internet o red local.
  - Sincronización de estado: Asegura que los estados del juego sean coherentes para todos los jugadores en un entorno multijugador.

- Herramientas de desarrollo: Herramientas auxiliares para desarrollar el juego
  - Editor de niveles: Permite crear y diseñar mapas, niveles o entornos del juego.
  - Herramientas de depuración: Ayuda a identificar y resolver errores o problemas en el juego.
  - Gestión de recursos: Maneja los activos del juego (gráficos, sonidos, modelos, etc.) y su integración dentro del motor.

- Sistema de interfaz de usuario (UI): Gestiona la interacción con el usuario.
  - Menús y HUD: Permite la creación de interfaces gráficas como menús, botones, marcadores, y barras de vida.
  - Interacción con el jugador: Facilita la creación de interfaces para que el jugador interactúe con el juego, como inventarios o diálogos.

- Gestor de escenas
  - Cambio de escenas: Maneja la transición entre diferentes escenas o niveles del juego.
  - Cargado dinámico: Permite cargar y descargar partes del entorno o escenas mientras el juego sigue en ejecución.

- Sistema de partículas: Simula sistemas de partículas para efectos como fuego, humo, explosiones, chispas, etc.

------

#### 2.6. Aplicación de modificaciones sobre juegos existentes (Mods)

------

Los mods son alteraciones hechas por jugadores o desarrolladores externos al contenido original de un videojuego.

------

- Mods estéticos.
- <!-- .element: class="fragment" -->JMods de jugabilidad.
- <!-- .element: class="fragment" -->JExpansiones.
- <!-- .element: class="fragment" -->JConversiones totales.
- <!-- .element: class="fragment" -->JMods de calidad de vida.

- Mods y motores.

------

<!-- .slide: data-background-color="#dddddd" -->

# Para saber más

Doom, y [ChiquitoDOOM](https://www.doomworld.com/idgames/sounds/chiquito). [Vídeo](https://www.youtube.com/watch?v=lXepPTAekiU)