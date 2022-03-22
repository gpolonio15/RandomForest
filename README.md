# RandomForest
Modelo regresión de Random Forest, sobre el set de datos House_sales de Seattle entre 2014 y 2015, que contiene 19 características de las casas más el precio, consta de 21613 observaciones.



El objetivo del estudio es predecir el precio de las viviendas.
Antes de entrenar los datos, se realizo un análisis de componentes principales (Principal Component Analysis PCA) es un método de reducción de dimensionalidad que permite simplificar la complejidad de espacios con múltiples dimensiones a la vez que conserva su información.
Los predictores más importantes, como se podían esperar es la latitud, longitud y código postal debido a que es muy importante la zona donde se encuentra el piso/casa, luego los metros del terreno, el nivel de construcción, el año de construcción del piso, los baños, y muy poco importante las plantas, el año de renovación y aunque parezca extraño las habitaciones.
Por último, se evalúa la capacidad predictiva del modelo final empleando el conjunto de test.
