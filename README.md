# MiniGames
Title: Práctica VR Minijuegos

Author: Fernando Arribas del Val

Date: 01 11 2026

Description: Colección de minijuego en un escenario con aspecto medieval.

Minijuegos:

1. Rompe-Ralph: coge el martillo y destroza las dos estatuas que están fuera. ¡Hazlas pedazos! - También puedes golpear la piñata que cuelga junto a la entrada de la taberna.

2. Dardos: coge el dardo de encima de la mesa, junto al pan y al montón de periódicos, y lánzalo contra la diana.
Problemas: he probado de varias formas (evento Component Hit e isOverlapping) tanto desde la diana como desde el dardo, pero al lanzar el dardo no queda "attach" a la diana, a menos que lo dejemos nosotros desde cerca.

3. Bolos: coge la bola y tírala contra los bolos. Intenta derribarlos todos. Tras ser lanzada la primera vez, la bola vuelve al inicio para una segunda oportunidad.

4. Mr. Potato: reconstruye al señor Potato con diferentes piezas. Coge la parte que le quieras añadir y suéltala cerca del cuerpo del Sr. Potato.

** He ajustado los componentes Grab de cada uno de los objetos para que cuando los cojas con la mano izquierda, estén orientados, añadiendo realismo.

** Se desactiva la opción de Nanite del proyecto y de cada uno de los objetos rompibles de la escena. Asimismo, se desactiva la opción Bone Colors de las estatuas para que muestre su textura en tiempo de ejecución. 
