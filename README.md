# Realidad aumentada · Pedro Claro

Ejercicio de la Unidad 3 (Taller de Diseño de Interfaces, UAI).

**Ver en vivo:** https://pclarow.github.io/realidad-aumentada/

## Cómo funciona

La **mano es el marcador**. La cámara detecta la mano con MediaPipe (Hand Landmarker). Cuando la reconoce, dibuja una **flecha roja** sobre ella (desde la muñeca hacia los dedos) y encima aparece el modelo 3D animado, que sigue la posición, el tamaño y el giro de la mano.

Es un marcador universal: no hace falta imprimir ninguna imagen, cualquier persona puede probarlo con su propia mano.

1. Abre el link en el celular o el computador y da permiso a la cámara.
2. Muestra tu mano abierta.
3. El botón "Cambiar cámara" alterna entre la cámara frontal y la trasera.

## Tecnologías

- MediaPipe Tasks Vision (detección de manos)
- Three.js + GLTFLoader (modelo 3D)
- Canvas 2D (flecha roja del marcador)

## Versión anterior

La primera versión usaba un marcador de imagen con AR.js: [marcador.html](https://pclarow.github.io/realidad-aumentada/marcador.html) (necesita [marker.png](https://pclarow.github.io/realidad-aumentada/marker.png)).
