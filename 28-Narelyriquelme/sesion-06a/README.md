# sesion-06a
## Apuntes 14 abr
### Schmitt Trigger
es un circuito comparador que utiliza histéresis para limpiar señales. Básicamente, es el "filtro de estabilidad" de la electrónica: toma señales analógicas ruidosas, lentas o con interferencias y las convierte en ondas cuadradas digitales perfectas.

**La Histéresis:**

A diferencia de un comparador común que tiene un solo umbral, el Schmitt Trigger tiene dos:
+ Umbral Superior ($V_{cc+}$): La señal de entrada debe subir por encima de este punto para que la salida cambie.
+ Umbral Inferior ($V_{cc-}$): La señal debe bajar de este punto para volver al estado anterior.

**Segun gemini sus aplicaciones principales serian:**
+ Eliminación de rebote (Debouncing): Ideal para botones físicos que, al presionarse, generan múltiples pulsos mecánicos. El Schmitt Trigger asegura que solo se registre un pulso limpio.
+ Conversión de ondas: Transforma ondas senoidales o triangulares en ondas cuadradas perfectas.
+ Osciladores: Es la base de muchos osciladores simples (como los que se usan en síntesis de sonido) cuando se combina con una resistencia y un condensador.Limpieza de datos: Se usa para recuperar señales digitales que se han degradado o llenado de ruido durante su transmisión.

imagen

### Chips
+ **4093** Contiene 4 puertas NAND, pero con una característica especial: cada entrada tiene un Schmitt Trigger.
   + solo oscila si pin 2=V++
     
imagen
+ **4017** el secuenciador de pasos. Es el chip que permite que las luces (o los sonidos) se activen uno por uno en orden.
  
imagen
