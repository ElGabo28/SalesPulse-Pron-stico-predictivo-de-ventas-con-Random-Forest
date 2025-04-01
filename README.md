# SalesPulse-Pron-stico-predictivo-de-ventas-con-Random-Forest
SalesPulse es un sistema de predicción de ventas que utiliza el algoritmo **Random Forest Regressor** para predecir la cantidad de piezas vendidas basándose en: - Precio unitario - Descuentos aplicados - Inversión en publicidad,se usan datos ficticios.

Arhivos en el repositorio:
- RL_prediccion_venta_piezas.ipynb: Contiene el codigo desde la carga de datos hasta que se guardan los valores predichos con el modelo de ML.
- datos_proyectados.csv: Contiene los datos que se usarán para predecir los resultados futuros según el Precio unitario, Descuentos aplicados e Inversión en publicidad.
- datos_ventas.csv: Contiene el dataset con el que se entrenará el modelo.
- modelo_piezas_venta.pkl: Es el modelo de ML.
- predicciones_futuras_completo.csv: Contiene los datos que se usarán para predecir los resultados futuros + el nuevo campo "piezas vendidas predichas" que son el numero de pezas que se venderán según el modelo. 
