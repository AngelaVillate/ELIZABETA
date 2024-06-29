# ELIZABETA
MIA
En este espacio podrás encontrar los códigos que fueron utilizados para el desarrollo de "Elizabeta, solución de conflictos mediante IA. Diseño, entrenamiento y comparación de la efectividad de modelos para la toma de decisiones", investigación desarrollada en el marco de la maestría en IA de la Universidad Internacional de la Rioja durante el periodo 2023-2024,

Algunas ideas sobre Elizabeta: 

Esta investigación tiene varios objetivos. Primero, se propone diseñar un modelo Random Forest capaz de predecir decisiones en el ámbito societario. La elección de este modelo se justifica por la necesidad de integrar herramientas automatizadas que respalden la toma de decisiones judiciales y que puedan explicar los resultados obtenidos. En el contexto del sistema jurídico, donde la argumentación es crucial, más que la mera predicción de resultados, se busca verificar si un modelo como el Random Forest puede ofrecer explicaciones sobre sus decisiones, a la par que demuestra una eficiencia similar a la de una red neuronal.
Ambos modelos fueron alimentados con los mismos datos y tenían como objetivo determinar la responsabilidad de los administradores en eventos específicos dentro de una sociedad. Dado que este modelo se basa principalmente en documentos de decisiones judiciales, esta investigación cuenta con componente significativo de técnicas de procesamiento de lenguaje natural. Gran parte del análisis se enfoca en establecer prácticas efectivas para mejorar el rendimiento del modelo, la elaboración de corpus y el tratamiento de documentos decisionales en el contexto de la inteligencia artificial y el aprendizaje automático.
Es fundamental destacar que la IA debe integrarse de manera efectiva con los conocimientos y disciplinas cotidianas para desarrollar modelos que no solo sean eficientes, sino que también reflejen las prioridades de nuestra sociedad, especialmente en áreas tan sensibles como la justicia.

Los códigos relacionados con la extracción de datos son:
Procesos de scraping, se incluye, incluso el proceso de scraping fallido, debido a las políticas de la págia

https://github.com/AngelaVillate/ELIZABETA/blob/main/ScrapingLaudoaLaudo_Bog.ipynb 
https://github.com/AngelaVillate/ELIZABETA/blob/main/Lectura%20textos%20adicionales.ipynb
https://github.com/AngelaVillate/ELIZABETA/blob/main/ScrapingSuper.ipynb

Los códigos relacionados con la fase de preprocesamiento de la información son:
Una vez recolectados los datos, se realizaron varias fases para su comprensión, preprocesamiento y estandarización para la elaboración del modelo

https://github.com/AngelaVillate/ELIZABETA/blob/main/NER_Datos.ipynb
https://github.com/AngelaVillate/ELIZABETA/blob/main/clusterizaci%C3%B3n%20general.ipynb
https://github.com/AngelaVillate/ELIZABETA/blob/main/extracci%C3%B3n_hechos.ipynb
https://github.com/AngelaVillate/ELIZABETA/blob/main/pretensiones240624.ipynb
https://github.com/AngelaVillate/ELIZABETA/blob/main/nube_de_palabras.ipynb

Embeddings, de lo cualitativo a lo cuantitativo:
Se hizo uso de modelos preentrandos transformers para generar los emebdings de los insights del modelo
https://github.com/AngelaVillate/ELIZABETA/blob/main/Embedings%20(1).ipynb

La elaboración de los modelos se encuentra en:
Se realizaron dos modelos para compara explicabilidad y métricas
RandomFoerst: Elizabeta
https://github.com/AngelaVillate/ELIZABETA/blob/main/Elizabeta.ipynb

Red Neuronal
https://github.com/AngelaVillate/ELIZABETA/blob/main/red_neuronal%20(1).ipynb

