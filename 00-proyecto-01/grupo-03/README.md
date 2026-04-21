# grupo-03

## integrantes

- Catalina Balboa
- Catalina Jeria
- Angel Sabogal

## descripción del sintetizador realizado

Construimos un sintetizador a partir de 4 secciones que describiremos como: **Clock Generator** construido a partir de un chip 555 (el C1 "condensador" y RV1 "potenciometro" controlan la frecuencia del clock) además de conectar el capacitor cerámico cerca del chip para brindarle mayor estabilidad a esta parte del circuito en concreto y posteriormente se le agregará también uno a cada chip del circuito con el fin de que tengan un circuito estable. La iguiente parte es el **Secuenciador** que se hace con el chip 4017, el cual tiene un led por cada conexión STEP "son 4" y a este se le conecta el Clock para poder comprobar que los electrones estan fluyendo correctamente por el circuito y esto nos lo dicen los leds encendiendose en secuencia uno despues de otro. Continuamos con el **Sintetizador** tratandose esta vez del chip 4093 en donde a las patas 1, 5, 8 y 12 se les conectan respectivamente los STEPS 1, 2, 3 y 4 y desde las patas 3, 4, 10 y 11 pasando por las resistencias que convergen enun mismo punto se conecta el cable que une el mix y además se le contecta directamente del chip de la pata 7 a GND (Tierra) y la 14 a VCC (Positivo) "C y RV de cada compuerta controlan frecuenciade oscilador Schmit Trigger. POT Puede ser reemplazado por LDR, resistencia experimentaal, etc". Y por último para la salida el MIX que venía del sintetizador se conecta al potenciometro que va conectado al chip LM386 de **Salida** y este potenciometro es para el volumen por lo que en este mismo chip al tener ya todo conectado finalizamos colocando el parlante (lo que le da vida al sonido si todo está funcionando correctmente)

imagen del sintetizador en su contexto

audio o video del sintetizador en acción

## proceso y resultados del reloj y secuenciador

con chips 555 y 4017

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## proceso y resultados de osciladores y amplificador

con chips 4093 y 386

incluir texto e imágenes sobre cableado, pruebas, resultados obtenidos.

## modificaciones realizadas a los circuitos originales

incluir texto, imágenes sobre modificaciones realizadas a los circuitos originales, incluyendo el proceso de diseño, pruebas y resultados obtenidos.

incluir modificaciones en posición, chips, parámetros, valores, etc.

## carcasas de cartón

textos, imágenes

incluir origen de materiales, decisiones de posiciones de los componentes, decisiones estéticas, pruebas, resultados obtenidos.

## interconexión entre módulos

textos, imágenes, diagramas de interconexión

## resultados finales

texto

imagen

video / audio

## aprendizajes y errores

las mejores lecciones aprendidas y los errores más comunes y cómo los resolvieron

## conclusiones

sobre modularidad, materialidad, trabajo en equipo, trabajo electrónico, trabajo maquinal.
