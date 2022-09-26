# w7-Kaggle-Predictions

Proyecto de Machine learning

## Introducción

Para el proyecto de la semana 7 deberemos juntar 2 csv para transformarlos con todo lo aprendido y así hacer un modelo de machine learning para predecir los sueldos del dataset. 


## Objetivos

1. Subir y juntar los dos csv dados.
2. Transformarlos con python los csv ya unidos.
3. No borrar filas en el csv test.
4. Hacer las mismas transformaciones en ambos csv.
5. Hacer gráficos para ver que estámos haciendo.
6. Entrenar y predecir para crear un nuebvo csv con la ID y el salario.

## Algunos pasos que he seguido

1. Abris los 2 csv en python y observar los datos dados, posteriormente unir mediante concat los 2 csv.
2. Coger las columnas para ir transformandolas.
3. En este caso he analizado la columna de job_title junto a la de salary_in_usd.

![portada](https://github.com/YasminMoreno/w7-Kaggle-Predictions/blob/main/img/graph1.png)

4. Posteriormente he observado los outliers que había para quitarlos.

![portada](https://github.com/YasminMoreno/w7-Kaggle-Predictions/blob/main/img/graph2.png)

5. He agrupado los job_title en 6 grupos.

![portada](https://github.com/YasminMoreno/w7-Kaggle-Predictions/blob/main/img/graph3.png)

6. También he hecho gráficas como ésta con la mediamedia de salarios por company_location para posteriormente dar un valor a cada localidad y así poder llegar a mejores resultados. 

![portada](https://github.com/YasminMoreno/w7-Kaggle-Predictions/blob/main/img/graph4.png)

7. He hecho  un dummies a la columna company_size y un label encode a la columna experience_level.

8. He hecho algun replace para cambiar nombres a algunos registros y alguna transformación más.

9. Prueba de modelos.

10. Entrenar y predecir. 


## Entregables

1. Carpeta `data` con los CSV que tenemosque limpiar. 
2. Carpeta `img` con algunas gráficas y la imagen del resultado final.
3. Archivo csv final `proyecto_sem7_5.`.


## Resultado final:

![portada](https://github.com/YasminMoreno/w7-Kaggle-Predictions/blob/main/img/captura_competition_kaggle.png)
