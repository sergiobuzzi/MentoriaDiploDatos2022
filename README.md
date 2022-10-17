## Repositorio de la mentoría: 

# Predicción de Ventas en las Sucursales de una Cadena de Supermercados


![](https://github.com/sergiobuzzi/MentoriaDiplodatos2022/blob/master/images.jpg)

El objetivo central de la mentoría es implementar modelos predictivos univariados y multivariados de series temporales convencionales y de aprendizaje automático (y posiblemente combinaciones de ambos). Por medio de dichos modelos se intentará predecir las ventas en las sucursales de una importante cadena de supermercados, con una frecuencia diaria.

La correcta predicción de las unidades vendidas permite: por un lado, evitar desperdicios por mantener stock innecesario de productos perecederos y por el otro lado, evitar la pérdida de ventas por faltas de stock.

Además es de interés conocer qué tipo de algoritmo funcionará mejor. Por una parte, los modelos de aprendizaje profundo poseen la capacidad de capturar patrones complejos y no linealidades, pero alcanzan a desplegar toda su potencialidad en datasets grandes. Por la otra parte, los modelos estadísticos de series temporales no requieren tanta información pero presentan cierta dificultad para modelar no linealidades o quiebres estructurales. De esto surge la posibilidad de combinar ambos metodologías y probablemente de mejorar los resultados por medio de ingeniería de features y transformaciones basadas en el conocimiento del área específica.

Intentaremos responder preguntas tales como: cuáles variables proveen mas información para predeceir las ventas, si hay productos o sucursales similares, si los días de la semana, los días feriados y la ubicación de las sucursales impactan en las ventas, etc.

En la carpeta [datasets](https://github.com/sergiobuzzi/MentoriaDiplodatos2022/blob/master/datasets) se proveen varios archivos con datos sobre las ventas discriminadas por sucursal y rubro y otras variables como días festivos y promociones. ¡Si deseas agregar otras variables mejor! También hay información sobre el estado y la ciudad donde se encuentra cada sucursal. Esta información nos permitirá trabajar muchos contenidos de la Diplo.

¡Espero que te interese el desafío y aprendas mucho en el camino!

## Detalles

Los datos son tomados de la competencia ["Store Sales - Time Series Forecasting - Use machine learning to predict grocery sales"](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) de la plataforma kaggle.com.


## Hitos de la Mentoría

#### TP1: Análisis y Visualización (Entrega 20/05)

Exploración de las bases de datos. Medidas de Estadística Descriptiva. Gráficos de evolución temporal. Identificación de outliers "comunes" vs. identificación de outliers temporales. Cálculo de correlaciones. Intuición básica de los conceptos de no estacionariedad y estacionalidad.

#### TP2: Análisis y Curación de Datos (Entrega 17/06)

Curación de las bases de datos. Imputación de faltantes. Combinación de la información de distintas bases de datos. Exploración de posibles transformaciones de los datos.

#### Video de presentación intermedia del proyecto y dataset (Entrega 24/06)

#### TP3: Aprendizaje Supervisado (Entrega 29/07)

Separación de datos en entremamiento, validación y test.  Ingeniería de features. Aplicación de modelos estadísticos y de machine learning simples. Estimación de otros modelos mas avanzados como Redes Neuronales Recurrentes en su variante LSTM y Prophet. Selección de métricas. Selección de hiperparámetros. Comparación de resultados. Evaluación del poder predictivo.

#### TP4: Aprendizaje No Supervisado (Entrega 26/08)

Aplicación de algoritmos de clustering de series de tiempo para la identificación de sucursales y rubros similares.

#### Video de presentación final de mentoría (Entrega 23/09)

#### Presentación de mentorías (Jornadas 11/11 y 12/11)

