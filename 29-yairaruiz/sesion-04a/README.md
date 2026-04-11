# sesion-04a

## 1. Desarmar y proceso ##
**Dispositivo: Mouse con cable (tipo óptico)**



**Paso 1: Apertura**
Se retira el tornillo ubicado en la parte inferior del mouse visible en la base. Luego, se separan las dos mitades de la carcasa: superior e inferior.




**Paso 2: Separación de piezas**
Al abrirlo, se distinguen claramente:

+ La carcasa superior con los botones integrados.
+ La carcasa inferior cumple la función de soporte, ya que mantiene los componentes en su posición y protege el circuito interno. 
+ La PCB en la base. 
+ La rueda scroll está montada sobre un eje que le permite girar y transmitir ese movimiento a un sensor en la placa.



**Paso 3: Exposición de la PCB**
Se observa la placa principal donde están montados los componentes electrónicos. Esta se mantiene conectada al cable USB y a los elementos mecánicos (rueda y botones).



## 2. Elementos de la PCB identificados ##
+ Chip (IC – circuito integrado):
Es el componente central negro con varias patas. Es el “cerebro” del mouse, encargado de procesar el movimiento y enviar la señal al computador.

+ Sensor óptico:
Se ubica en la parte inferior. Detecta el movimiento sobre la superficie.

+ LED:
Pequeña luz visible. Ilumina la superficie para que el sensor funcione.

+ Resistencias (R):
Regulan la corriente eléctrica dentro del circuito.

+ Capacitores (C):
Almacenan energía momentáneamente y estabilizan el flujo eléctrico.

+ Microinterruptores (switches):
Son los botones (izquierdo y derecho). Están en la parte superior de la PCB con una pequeña pieza roja o negra. Detectan el clic.

+ Rueda scroll + encoder:
La rueda está conectada a un mecanismo que detecta el giro (encoder), enviando señales a la PCB.

## 3. Conexiones entre PCB y componentes ##
+ Cable USB - PCB:
El cable principal entra directamente a la placa y está soldado. Transporta energía y datos.

+ Botones (carcasa superior) -  microinterruptores:
Los botones físicos presionan los switches montados en la PCB.

+ Rueda scroll - sensor/encoder:
La rueda mecánica está alineada con un sensor que detecta su movimiento.

+ LED + sensor óptico - PCB:
Ambos están integrados en la placa y trabajan juntos para detectar movimiento.

+ Carcasa - soporte estructural:
La carcasa no conduce electricidad, pero mantiene todos los componentes en su posición.

Dentro del mouse, la electricidad entra por el cable y se reparte por toda la placa. Esa energía permite que todos los componentes funcionen y se comuniquen entre sí. La corriente va recorriendo los caminos de la placa y llega a cada parte según lo que se necesite en ese momento.

El chip es la parte principal, porque recibe toda la información. Cuando uno hace clic, los botones activan pequeños interruptores que mandan una señal al chip. Lo mismo pasa con la rueda: cuando gira, envía señales que indican si uno está subiendo o bajando. El chip toma todo eso y lo convierte en acciones que el computador entiende.

Por abajo, hay una luz y un sensor que detectan el movimiento del mouse sobre la superficie. Este sensor “lee” cómo se mueve y manda esa información al chip. Finalmente, toda esa información viaja de vuelta por el cable hacia el computador, lo que permite que el cursor se mueva en la pantalla.



