## Recognizing Contextual Polarity in Phrase-Level Sentiment Analysis

### Resumen
El paper va de como la clasificacion polar de una frase utilizando lexicones tiende a carecer
de informacion necesaria como para poder clasificarla objetivamente. La propuesta del mismo es
introducir otro tipo de marcado denominado polaridad contextual. 

La polaridad contextual en contraposicion de la polaridad previa (prior-polarity) tiene mejor en
cuenta la connotacion real polar en si.

La clasificacion la hace en 2 pasos, primero limpia los que no son polares (no aparece ninguno de
los features relacionados) y despues los que si tienen features los clasifica en positivos, negativos
y neutrales.

### Analisis
No tiene mucho sentido mirar el proceso en detalle. Particularmente porque requiere de un marcado 
intensivo que **no** podemos darle a nuestro tp. A simple vista es particularmente complejo
armar un lexicon para utilizar, sumado a multilenguaje ya es algo que no es facil de controlar.
De hecho, la solucion de traducir y evaluar no es muy viable en esas condiciones.

Creo que lo mas util que se puede sacar del paper este en si es un poco el analisis de la necesidad
de contextualizar las palabras en caso de usarlas como features.
