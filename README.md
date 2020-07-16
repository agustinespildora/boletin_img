# Examen Web jaespildora

### Nombre:
- Agustín Espíldora

### Puntos a considerar:
- Para posicionar una nave en el tablero se debe hacer click en el tipo de nave en el panel de Acciones y luego hacer click en alguna casilla del tablero.
- Se ve el id de la nave en la casilla una vez que la posicionas.
- No se pueden posicionar naves fuera de estas casillas.
- Se puede sacar una nave que ya se posicionó y volverá a quedar guardada aunque el número del tipo de nave en el panel de Acciones no se actualiza inmediatamente, por lo que el número no representa siempre la cantidad real de naves restantes. Es sólo un problema visual.
- Sólo se muestra la opción de jugar cuando se posicionan todas la naves.
- Si se selecciona jugar ya no se pueden cambiar las naves de posición.
- Esta implementado el que no se pueda elegir una opción si ya se eligió la otra (si se apreta el boton "move" (mover) no se podrá hacer "fire" (disparar) hasta terminar la acción).
- No se implementaron las respuestas de la api, por lo que no existe enemigo. Asi que implementé los disparos para hacerlos con las propias naves del usuario, lo que no debería ser muy distinto a cuando existan las naves del enemigo ya que son la misma entidad.
- No se ven las casillas a las que se puede mover, pero están correctamente implementadas.
- Aunque no se ve a donde se puede disparar sólo se dispara si la casilla está en el rango de la nave. Si se dispara a una casilla donde hay una nave ésta queda en rojo para marcarla como inutilizada.
- Las casillas inutilizadas quedan marcadas en rojo con el id del barco que fue destruido ahí.
- El barco al disparar en su propia casilla se autodestruye.
- Si quieres testear el juego sin tener que posicionar tooodos los barcos puedes ver el archivo `components/Menu.jsx` en la línea 135 y cambiar la clase que se le entrega al boton jugar.
- El log tiene un tamaño limitado.
