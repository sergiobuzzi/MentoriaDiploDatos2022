### MentoriaDiploDatos2022

## Repositorio de la mentoría: 

# Predicción de Ventas en las Sucursales de una Cadena de Supermercados


![](https://github.com/sergiobuzzi/MentoriaDiplodatos2022/blob/master/images.jpg)

El objetivo central de la mentoría es implementar modelos predictivos univariados y multivariados de series temporales convencionales y de aprendizaje automático (y posiblemente combinaciones de ambos). Por medio de dichos modelos se intentará predecir las ventas en las sucursales de una cadena de supermercados, con una frecuencia diaria.

La correcta predicción de las unidades vendidas permite: por un lado, evitar deperdicios por mantener stock innecesario de productos perecederos y por el otro lado, evitar la pérdida de ventas por faltas de stock.

Los datos son tomados de la competencia "Store Sales - Time Series Forecasting - Use machine learning to predict grocery sales" de la plataforma kaggle.com.

Algunos métodos estadísticos tradicionales han demostrado no ser muy 

Uno de los desafíos mas interesantes de la mentoría consiste en que, al no ser demasido grande la cantidad de observaciones, cabe preguntarse qué tipo de algoritmo funcionará mejor. Por una parte, los modelos de aprendizaje profundo poseen la capacidad de capturar patrones complejos y no linealidades, pero alcanzan a desplegar toda su potencialidad en datasets grandes. Por la otra parte, los modelos estadísticos de series temporales no requieren tanta información pero presentan cierta dificultad para modelar no linealidades o quiebres estructurales. De esto surge la posibilidad de combinar ambos metodologías y probablemente de mejorar los resultados por medio de ingeniería de features y transformaciones basadas en el conocimiento del área específica.

¡Espero que te interese el desafío y aprendas mucho en el camino!

## Detalles

En la carpeta [datasets](https://github.com/sergiobuzzi/MentoriaDiplodatos2022/blob/master/datasets) se proveen varios archivos con datos sobre las ventas discriminadas por sucursal y rubro y otras variables como días festivos y promociones. También hay información sobre el estado y la ciudad donde se encuentra cada sucursal, y un posible agrupamiemto

A continuación se plantean los posibles contenidos generales a desarollar en los prácticos:

#### TP1: Análisis y Visualización

Exploración de las bases de datos. Medidas de Estadística Descriptiva. Gráficos de evolución temporal. Identificación de outliers "comunes" vs. identificación de outliers temporales. Cálculo de correlaciones. Intuición básica de los conceptos de no estacionariedad y estacionalidad.

#### TP2: Análisis y Curación de Datos

Curación de las bases de datos. Imputación de faltantes. Combinación de la información de distintas bases de datos. Exploración de posibles transformaciones de los datos.

#### TP3: Introducción al Machine Learning

Separación de datos en entremamiento, validación y test. Aplicación de modelos estadísticos y de machine learning simples. Selección de métricas. Selección de hiperparámetros. Comparación de resultados.

#### TP4: Aprendizaje Supervisado

Estimación de otros modelos mas avanzados como Redes Neuronales Recurrentes en su variante LSTM y Prophet. Evaluación del poder predictivo.

#### TP5: Aprendizaje No Supervisado

Aplicación de algoritmos de clustering de series de tiempo para la identificación de sucursales y rubros similares.



