## Medidas de tendencia central

***
## *Media*
    Tendencia de la distribuición 
    Tiene problemas con los Outliers
***
## *Mediana*
    *Segundo Cuartil*
        Representa la tendencia central de la distribuición  

    Cuartiles:  
     IQR (inter Quartil Range) -> 50% de los datos  
     La mejor forma de visualizar es por medio de los  `boxplot`

***
## Varianza && Desviación Estandar  

    1. Valor de la mediana al cuadrado  
    2. la varianza de infla con Outliers
    3. A mayor varianza se espera que los valores estén mas dispersos

    La Desviación Estandar es la mas usada y es la raíz cuadrada de la varianza 
    ```{r} 
        sd()pref_o_intelligence
        var()
        mean()
        median()
    ```
    (sigma)
    ![alt text](http://slideplayer.es/slide/2458262/8/images/1/Desviaci%C3%B3n+Est%C3%A1ndar+en+relaci%C3%B3n+con+siete+puntajes%3A.jpg "Desviación Estandar")
    
##  Simetría (Skewness)
    
    Se llama Simetría pero sirve para mirar la asimetría 
    Sí es positiva la distribuición va hacia la derecha 
    Sí es negativa la distribuición va hacia la izquierda


## Kurtosis

    Que tanto se parecen las distribuciones en las colas con la normal

    sí Kurtosis<3 Es muy probable encontrar valores similares a la media en los extremos

    sí Kurtosis>3 Es muy probable encontrar valores iguales en los extremos




