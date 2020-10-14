# proyecto_3
**Proyecto 3 - Data Science - Acámica**

##Aplicaciones actuales: Procesamiento del Lenguaje Natural (idioma español)

**Objetivo**: Implementar un modelo que, dada la crítica de un producto, asigne la cantidad de estrellas correspondiente.

**Parte A: Exploración de datos**
- Evaluación de datos faltantes
- Evaluación de la distribución de las estrellas 
- Homogeneización del idioma 
- Recuento de reviews por tipo de categoría de producto
- Rating promedio por categoría de productos
- Recuento de revisores diferentes
- Tranformaciones de datos: 
    - Elimino los emojis 
    - Elimino los números 
    - Llevo a minúsculas, elimino puntuaciones, elimino `stop words`y hago la lemmatización.
    - Cambio vocales con acento por vocales sin acento
    - Tokenización

Responderé a las siguientes preguntas:

- 1) ¿Cuáles son las palabras asociadas a una buena puntuación? ¿Y a una mala puntuación?
- 2) ¿Cuándo se escribe mas? ¿Con buenas calificaciones o con malas?

**Parte B: Modelo de Machine Learning**
- 1) Haz todas las transformaciones de datos que consideres necesarias. Justifica.
- 2) Evalúa de forma apropiada sus resultados. Justifica la métrica elegida.
- 3) Elige un modelo benchmark y compara tus resultados con este modelo.
- 4) Optimiza los hiperparámetros de tu modelo.
- 5) Intenta responder la pregunta: ¿Qué información está usando el modelo para predecir?

**Parte C: Investigación. Para pensar, investigar y, opcionalmente, implementar**
- 1) ¿Valdrá la pena convertir el problema de Machine Learning en un problema binario? Es decir, asignar únicamente las etiquetas Positiva y Negativa a cada crítica y hacer un modelo que, en lugar de predecir las estrellas, prediga esa etiqueta. Pensar en qué situación puede ser útil. ¿Esperas que el desempeño sea mejor o peor
- 2) ¿Hay algo que te gustaría investigar o probar?

