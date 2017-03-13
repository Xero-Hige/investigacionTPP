# Recognizing Contextual Polarity in Phrase-Level Sentiment Analysis

El paper va de como la clasificacion polar de una frase utilizando lexicones tiende a carecer
de informacion necesaria como para poder clasificarla objetivamente. La propuesta del mismo es
introducir otro tipo de marcado denominado polaridad contextual. 

La polaridad contextual en contraposicion de la polaridad previa (prior-polarity) tiene mejor en
cuenta la connotacion real polar en si.

La clasificacion la hace en 2 pasos, primero limpia los que no son polares (no aparece ninguno de
los features relacionados) y despues los que si tienen features los clasifica en positivos, negativos
y neutrales.
