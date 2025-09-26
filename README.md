## Práctica 2. Funciones básicas de OpenCV


### 2.1. Aspectos cubiertos
En esta practica se ha desarrollado cuatro ejercicios.El primero es Contar los bordes por filas y mostrar las filas con bordes por el encima de 90% del máximo donde utilizando la función de numpy np.where conseguimos encontrar la mayor concentración de píxeles de borde y luego visualizarlo
```python
rows_over_threshold = np.where(borders_by_row_ratio > 0.9 * max_border_number)[0]
```
El segundo ejercicio es aplicar  umbralizado a la imagen resultante de Sobel (convertida a 8 bits), y posteriormente realizar el conteo por filas y columnas similar al realizado en el ejemplo con la salida de Canny de píxeles no nulos y calcular el valor máximo de la cuenta por filas y columnas, y determina las filas y columnas por encima del 0.90*máximo. Remarca con alguna primitiva gráfica dichas filas y columnas sobre la imagen del mandril aquí utilizamos lineas donde hicimos rectas discontinuas u continuas en rojo ¿Cómo se comparan los resultados obtenidos a partir de Sobel y Canny?
Se puede distinguir que la diferencia principal entre ambos es en la calidad del borde que coje siendo canny el más avanzado de los dos.

En el tercer ejercicio escojimos hacer dos filtros usando el de la anterior practica de minecraft y aplicado en esta practica Canny para la deteccion de bordes multietapa.

### 2.2. Entrega



