# Juego de Secuencia Numérica

Este es un juego interactivo desarrollado en Python con `pygame`, donde el jugador debe completar secuencias lógicas de números. El objetivo es identificar el siguiente número en la secuencia antes de cometer demasiados errores.

## Características
- **Interfaz gráfica minimalista** con colores cálidos y agradables.
- **Diferentes tipos de secuencias numéricas**, incluyendo:
  - Doble (multiplicación por 2)
  - Fibonacci
  - Potencias
- **Sistema de puntuación**: cada acierto suma puntos.
- **Límite de errores**: si el jugador comete más de 5 errores, el juego se reinicia con un mensaje.
- **Botón de reinicio** al perder la partida.

## Requisitos
Para ejecutar el juego, necesitas tener instalado `pygame`. Puedes instalarlo con:

```sh
pip install pygame
```

## Cómo jugar
1. Ejecuta el script en Python:
   ```sh
   python number_sequence_game.py
   ```
2. Se mostrará una secuencia de números con un signo de interrogación `?` indicando el número que falta.
3. Escribe tu respuesta y presiona `Enter`.
4. Si aciertas, ganas puntos y se genera una nueva secuencia.
5. Si te equivocas más de 5 veces, aparecerá un mensaje y un botón para reiniciar el juego.

## Posibles mejoras
- Agregar más patrones de secuencias (primos, factoriales, etc.).
- Incluir sonidos y efectos visuales para mejorar la experiencia.
- Implementar un sistema de niveles con aumento de dificultad.
- Soporte para múltiples jugadores o modo competitivo.
- Adaptar el juego para dispositivos móviles.

¡Diviértete desafiando tu lógica matemática con este juego de secuencias numéricas! 🚀

