Este proyecto consta de un problema de clases desbalanceadas de analisis crediticio, para ello se solicitó la creación de modelos predictivos que apoyen a la toma de decisión acerca de si entregar un credito o no a un cliente.
Para ello se crea la marca binaria de si es bueno o malo.

El problema inicia con la limpieza de la base de datos, búsqueda de valores faltantes, duplicados, etc.
Luego un analisis de variables viendo su correlación e information value
Despues de toda la limpieza se normalizan los datos para entrenar al modelo.

Para entrenar al modelo se utilizaron técnicas de OverSampling y UnderSampling para equiparar las clases (Dado que naturalmente hay mas clientes buenos que malos)

Luego con el train set se entrena a los modelos haciendo inicialmente una búsqueda exhaustiva de parametros con gridsearchcv el cual nos permite obtener el mejor conjunto de parametros
para cada modelo.

Despues de entrenar al modelo se utiliza el test set para obtener las métricas y evaluar el desempeño del modelo (en este caso el enfoque será en F1-Score)

en desarrollo...
