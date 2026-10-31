Química Quest: Aventura en la tabla periódica
Química Quest es un videojuego educativo de exploración y desafíos sobre los elementos químicos y la tabla periódica. El jugador recorre un tablero de laboratorio, interpreta consignas, identifica elementos por su símbolo, número atómico o familia química y evita zonas peligrosas que cambian de posición.

El objetivo es resolver 15 desafíos distribuidos en 3 niveles antes de perder las 3 vidas disponibles. La experiencia combina conocimientos de química, observación, toma de decisiones y orientación espacial.
Jugar en línea
Abrir Química Quest

El enlace funciona una vez que GitHub Pages está habilitado y el archivo index.html está publicado en la rama correspondiente.
Objetivos educativos
- Reconocer símbolos y nombres de elementos químicos.
- Relacionar elementos con su número atómico.
- Identificar familias o categorías de la tabla periódica, como metales alcalinos, halógenos y gases nobles.
- Reforzar conocimientos mediante desafíos breves y retroalimentación.
- Desarrollar atención, orientación y toma de decisiones frente a opciones y obstáculos.
¿Cómo se juega?
Al iniciar, aparece una pantalla con las instrucciones. Después de seleccionar «¡Comenzar a jugar!», el personaje aparece en el tablero.
1. Leer la misión: se muestra una consigna para encontrar un elemento químico. Puede pedir su símbolo, número atómico o identificación por nombre y familia.
2. Explorar el tablero: usar el teclado para mover al personaje entre las casillas.
3. Elegir una respuesta: desplazarse hasta la casilla del elemento correcto entre cuatro opciones disponibles.
4. Evitar los peligros: las casillas marcadas con ☣️ representan zonas contaminadas y cambian de ubicación aproximadamente cada 2,8 segundos.
5. Completar los desafíos: cada acierto permite avanzar a la siguiente misión. El juego termina al resolver los 15 desafíos o al perder las 3 vidas.
El tablero tiene 8 columnas y 6 filas. Las opciones de respuesta y las zonas de riesgo aparecen en diferentes posiciones según la ronda.
Niveles y progresión
La aventura consta de tres niveles consecutivos, con cinco desafíos por nivel:
Nivel	Desafíos	Puntos por acierto
1	1 al 5	+100
2	6 al 10	+125
3	11 al 15	+150


Las consignas se generan a partir de una selección de elementos de la tabla periódica. En cada ronda se presentan cuatro elementos posibles y solo uno cumple la misión. El progreso se muestra en la parte superior de la pantalla.
Sistema de puntuación y vidas
- Respuesta correcta: suma 100, 125 o 150 puntos, dependiendo del nivel.
- Elemento incorrecto: descuenta 50 puntos y 1 vida.
- Zona contaminada ☣️: descuenta 50 puntos y 1 vida.
- Puntuación mínima: el marcador nunca baja de 0 puntos.
- Vidas iniciales: 3 corazones.
- Victoria: se obtiene al completar los 15 desafíos.
- Derrota: ocurre cuando se agotan los 3 corazones.
Al finalizar, el juego presenta un resumen del desempeño y permite volver a jugar. Cuando se identifica correctamente un elemento, también se ofrece una curiosidad o información breve sobre él.
Controles
Tecla	Acción
↑ o W	Mover hacia arriba
↓ o S	Mover hacia abajo
← o A	Mover hacia la izquierda
→ o D	Mover hacia la derecha
Enter	Iniciar o reiniciar una partida desde la pantalla correspondiente


El movimiento se controla por teclado. No se necesitan botones de dirección en pantalla.
Interfaz y características
- Pantalla inicial de instrucciones: explica la misión, los controles y las penalizaciones antes de comenzar.
- Tablero fijo: cuadrícula de 8 × 6 casillas.
- Indicadores visibles: puntuación, nivel actual, vidas y progreso de la misión.
- Peligros dinámicos: dos zonas contaminadas se reubican periódicamente durante la partida.
- Consignas variables: identificación de símbolos, números atómicos y familias químicas.
- Información contextual: mensajes de acierto o error y datos breves de los elementos.
- Ilustración temática: personajes científicos integrados en el archivo principal.
- Reinicio de partida: permite comenzar otra vez al ganar o perder.
Tecnologías utilizadas
- HTML5: estructura de la página y punto de entrada del juego.
- CSS3: diseño, distribución, tablero e interfaz visual.
- JavaScript: mecánicas, desplazamiento, selección de respuestas, niveles, vidas y puntuación.
- React 18 y ReactDOM: componentes y actualización de la interfaz, cargados desde CDN.
- Google Fonts: tipografías DM Sans y Space Grotesque.
El juego se distribuye en un único archivo HTML, que incluye los estilos, la lógica de JavaScript y la ilustración insertada. No necesita npm, Node.js ni un proceso de compilación para publicarse.
Conexión a Internet: es necesaria para cargar React, ReactDOM y las fuentes externas. Los gráficos integrados en el HTML no necesitan archivos de imagen adicionales.

Ejecutar el proyecto
Opción 1: abrirlo en el navegador
1. Descargar el archivo index.html.
2. Abrirlo con un navegador moderno, como Chrome, Edge o Firefox.
3. Leer las instrucciones y comenzar la partida.
Es necesario disponer de Internet para cargar las bibliotecas externas.
Opción 2: publicar con GitHub Pages
1. Crear un repositorio público en GitHub.
2. Subir index.html y README.md a la raíz del repositorio mediante Add file → Upload files.
3. Confirmar los archivos con Commit changes.
4. Abrir Settings → Pages.
5. En Build and deployment, elegir Deploy from a branch.
6. Seleccionar la rama main y la carpeta / (root); después guardar.
7. Acceder al enlace que aparece en la sección de GitHub Pages una vez finalizada la publicación.
No se requiere Codespaces. GitHub Pages publica el archivo index.html como una página web estática.
Estructura del repositorio
qu-mica/
├── index.html    # Videojuego completo: estructura, diseño, lógica e ilustración
└── README.md     # Documentación del proyecto
Uso educativo
Química Quest puede utilizarse como actividad de práctica o repaso en clases de Química y ciencias. Se presta a propuestas individuales, juegos de revisión de contenidos y desafíos de identificación de elementos.

La dinámica está orientada al reconocimiento de elementos seleccionados, no a la exploración exhaustiva de los 118 elementos de la tabla periódica. Por ello, funciona como recurso complementario de enseñanza y no como sustituto del material teórico de la asignatura.
Estado del proyecto
Versión web jugable con 3 niveles y 15 desafíos. Su publicación se realiza mediante GitHub Pages. Esta documentación describe las funciones presentes en el archivo index.html entregado con el proyecto.
