# Examen Web jaespildora

### Nombre:
- Agustín Espíldora

### Puntos a considerar:
- Para posicionar una nave en el tablero se debe hacer click en el tipo de nave en el panel de Acciones y luego hacer click en alguna casilla del tablero.
- No se pueden posicionar naves fuera de estas casillas.
- El número de las naves restantes al momento de su posicionamiento no se actualiza inmediatamente, por lo que el número no representa siempre la cantidad real de naves restantes. Es sólo un problema visual. Puedes seleccionar un tipo de nave para posicionarla en una casilla, o seleccionar una nave puesta en una casilla para volver a la lista de naves.
- Sólo se muestra la opcion de jugar cuando se posicionan todas la naves.
- Si se selecciona jugar ya no se pueden cambiar las naves de posición.
- Esta implementado el que no se pueda elegir una opción si ya se eligió la otra (si se apreta el boton move no se podrá hacer fire hasta terminar la acción).
- No se implementaron las respuestas de la api, por lo que no existe enemigo. Asi que implementé los disparos para hacerlos con las propias naves del usuario, lo que no debería ser muy distinto a cuando existan las naves del enemigo ya que son la misma entidad.
- No se ven las casillas a las que se puede disparar o mover, pero están correctamente implementadas.
- No se ve a donde se dispara, pero si se dispara a una casilla donde hay una nave ésta queda en rojo para marcarla como inutilizada.
- El barco al disparar en su casilla se autodestruye.
- Si quieres testear el juego sin tener que posicionar tooodos los barcos puedes ver el archivo `components/Menu.jsx` en la línea 135 y cambiar la clase que se le entrega al boton jugar.
