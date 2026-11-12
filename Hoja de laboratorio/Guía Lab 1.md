## 1. Momento 1 - predecir
---
>[!question] Pregunta 1 
> Les llega una cadena de 1 679 ceros y unos, sin nada más. ¿Qué es lo primero que intentarían para encontrarle sentido? Escriban tres ideas, en orden.


**Respuesta:**
1. Un primer acercamiento dar por hecho que es un texto y comparar secuencias de 1's y 0's frecuentes con palabras comunes
2. 1679 es semiprimo porque solo es divisible por 73 y 23. Seria lógico pensar en dividir la cadena en 73 partes de 23 dígitos, donde cada una de las partes es una palabra.
3. Asociar una secuencia de caracteres con un número binario del 0 al 26, siendo 0 la primera 
>[!question] Pregunta 2
>Si alguien quisiera mandar un **dibujo** con bits, ¿cómo lo haría? ¿Qué tendría que adivinar quien lo recibe?

**Respuesta:** 
Se puede mandar el dibujo usando 1 para los cuadritos llenos y 0 para los vacíos. El que lo recibe tendría que saber o adivinar cuántas filas y columnas tiene para poder formar el dibujo




>[!question] Pregunta 3
> Por qué quien diseñó el mensaje eligió un número que es producto de **dos primos**? ¿Qué habría pasado si el mensaje tuviera 1 680 bits, que se pueden acomodar de 40 maneras?


**Respuesta:**
Porque así es mas claro la forma en la que el emisor esperase que se entendiese el mensaje. En lugar de probar 40 rectángulos diferentes para buscarle un sentido, solo se prueban dos, el rectángulo de 23 filas y 73 columnas, y el de 73 filas y 23 columnas. 

>[!question] Pregunta 4 
>¿Cuál es la diferencia entre el carácter `'1'` y el bit 1? Dos líneas.

**Respuesta:**
El carácter '1' es un texto mientras que el bit 1 es un valor binario.
Aunque se representan igual, '1' es un carácter y 1 es un número entero en Python

>[!question] Pregunta 5 
>¿Por qué quien diseñó el mensaje eligió un número que es producto de **dos primos**? ¿Qué habría pasado si el mensaje tuviera 1 680 bits, que se pueden acomodar de 40 maneras?

**Respuesta:**
Eligieron un número que es producto de **dos primos** porque así hay **pocas formas de acomodar los bits** y es más fácil adivinar las dimensiones del dibujo. Si tuviera **1680 bits**, habría **40 formas diferentes** de acomodarlos, entonces sería mucho más difícil saber cuáles son las dimensiones correctas del dibujo.

>[!question] Pregunta 6
>  ¿Qué parte del mensaje habrían podido descifrar sin saber química? ¿Y sin saber que en 1974 Plutón contaba como planeta? Agreguen esas convenciones a su lista.


**Respuesta:**
La parte de los números y la figura humana, porque se pueden interpretar visualmente. En cambio, la información de los elementos químicos sería difícil de entender sin conocimientos de química.
Sería difícil interpretar correctamente la parte del sistema solar, porque no sabríamos por qué aparecen nueve planetas

>[!question] Pregunta 7
>La cabeza del humano es **un solo bit**, y la barra del ADN termina justo en ella. ¿Es casualidad o es un mensaje? ¿Cómo lo sabrían?

**Respuesta:**
No parece ser casualidad, sino que puede ser un mensaje intencional para relacionar la figura humana con el ADN. Para saberlo habría que revisar cómo están organizados los bits y comprobar si esa ubicación tiene un significado o si pudo ocurrir por coincidencia

>[!question] Pregunta 8
> Si ustedes hubieran diseñado el mensaje, ¿qué habrían cambiado para que fuera más fácil de leer?

**Respuesta:**
Cuántas filas y columnas tiene el mensaje y en qué orden se debe leer. También habríamos explicado los símbolos y las referencias científicas para que cualquier persona pudiera entenderlo más fácilmente