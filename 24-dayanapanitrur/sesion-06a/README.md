# sesion-06a

## Martes 14 de Abril del 2026

Partiendo la sesión, Misaa nos compartió varias recomendaciones muy útiles para desarrollar(nos).

Primero una herramienta muy útil, con la cuál realizó todo su portafolio y cv, ya que en el rubro creativo el curriculum vitae con datos sobre en qué liceo estudiaste, qué otras pegas agarraste por ahí, están obsoletos, esas cosas no existen en este ámbito y son innecesarias. Y la mayor parte de esto lo hizo con **Claude** de la empresa Anthropic, que es una IA que puede procesar y realizar tareas mucho más complejas y más específicas que las IA’s comunes.

Además el libro "Aesthetic Programing" 

Hace un tiempo, Aaron y Matias nos hicieron completar una encuesta anónima para evaluar las sesiones, la forma de enseñar, la materia, etc. Y algo de lo que me di cuenta y que pude rescatar es que, sí, la materia es densa. Esta puede ser muy compleja de comprender al ser tan técnica y tan estructurada. Pero lo transforman, exploran, nos invitan a pertenecer al lado creativo y metafórico de la tecnología. 

Tengo entendido que el libro trata de eso también, es simbólico, es analítico, te enseña a escribir código real, explorando la creatividad y la intención al momento de programar. Abarca la programación desde lo técnico pero también desde lo reflexivo y lo mezcla con cultura, política, entre más ámbitos. 

---

### Schmitt trigger

foto aqui)

Aaron dice que el Schmitt trigger es una compuerta NAND con "toppings" por decirlo así. Me gusta esa definición.

Es diferente a las compuertas NAND comunes.
Una compuerta NAND común por lo general tiene un umbral, el schmitt trigger tiene dos.

Cuando la señal es inestable o posee mucho ruido, en una compuerta NAND común al solo comprender 1 y 0 dentro de un umbral, se prende y apaga de forma frenética.

El schmitt trigger en esa situación le da un margen a la señal, le dice que no importa si baja o sube un poquito, solo si sube sobre ambos umbrales, tanto el de abajo como el de arriba va a ser 1 y si baja completamente por el umbral de abajo va a ser 0 (o así lo entendí yo).

Entonces, para pasar de 0 a 1 debe pasar por ambos umbrales para que se interprete bien y no quede como una señal curiosa.

Cuando está ahí entremedio, esa señal es RUIDO (El chip 4011 se suele usar mucho en circuitos en los que se busca este ruido).

Y a esto se le llama *Histéris*, que es todo este sistema interno que ocupan estos chips.

https://forum.arduino.cc/search?q=schmitt%20trigger

Para cuando se tienen dudas sobre estas cosas, existen estas páginas maravillosas para realizar preguntas, como este foro de la comunidad de arduino.

### 4093

Foto chip aqui)

Solo oscila SI pin2 = V ++

Cada una de las compuertas tienen un R y un C
Justamente el 4093 tiene 4 compuertas, por eso obtendremos 4 sonidos distintos.

El mixer hace que para poder obtener distintos sonidos y no tener que precisamente (y tediosamente)
conectar 4 parlantes, por lo que junta todas resistencias y las traduce en sonido.

SEQ4PASOS fotos aquí.)
