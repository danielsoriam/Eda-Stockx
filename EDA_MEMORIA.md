# **Analisis exploratorio de Datos de reventa de sneakers**



## **Memoria del Eda**
- [**Inicio**](#Analisis-exploratorio-de-Datos-de-reventa-de-sneakers)
  - [**Descripción**](#descripción)
  - [**Fuentes**](#fuentes)
  - [**Dataset**](#dataset)
  - [**Limpieza de Datos**](#limpieza-de-datos)
  - [**Objetivos del Análisis**](#objetivos-del-análisis)
  - [**Conclusiones**](#conclusiones)
<!-- TOC -->



### **Descripción**
-----------

- Se va a realizar un análisis sobre una muestra random de ventas de todas Off-White x Nike and Yeezy 350 desde 9/1/2017 (mes cuando Off-White debuta con su colección “The Ten” )hasta la fecha del concurso 2019, los datos nos lo proporcina la empresa de reventa de street wear STOCKX. 
- Los datos son de ventas en Estados Unidos exclusivamente

### **Fuentes**
-----------

### https://www.kaggle.com/datasets/hudsonstuck/stockx-data-contest
### https://stockx.com/news/the-2019-data-contest/

### **Dataset**
-----------
- **Concurso 2019**: Extraemos los datos de la página oficial de Stockx.

- **Excel to Csv**: Convertimos el excel en formato csv.

- **Exportación**: Con la herramienta de la biblioteca Pandas, hacemos un readcsv y convertimos el archivo en un series.
- **DataFrame**: Con Pandas convertimos esa tabla en nuestro Dataframe, con el cual podemos empezar a ver los datos de una manera mas ordenada por filas y columnas.

### **Limpieza de Datos**

------
- **Conversiones**: Procedemos a quitar los signos de dolar $ que traen las columnas de precios, limpiamos los nombres de los sneakers poniendo los espacios donde corresponde, convertimos las fechas de lanzamiento y venta a objetos de datetime.

- **Numéricos**: Después convertimos en enteros y float las columnas de precios y de talla de zapatos respectivamente.

###  **Objetivos del Análisis**:
Queremos determinar cuales serán las mejores opciones para invertir en sneakers, ya sea por marca, por modelo, por zona o por talla de zapatillas.

- **Valoración del Análisis**:
Según el análisis vemos que es mejor invertir en Off White en California y en una talla 10 americano, nos producirá una venta bastante rápida y con un buen beneficio.

### **CONCLUSIONES**

-----------

Para terminar, se podría decir que este mercado es muy fructífero, si tienes la posibilidad de comprar Off White a precio retail, y si vives en una gran ciudad como New York y California.
Si se quiere invertir en Yeezy habría que elegir un modelo o color que no sea muy común y eso vuelve al par mas codiciado y con un beneficio competitivo.
Stockx recientemente ha lanzado NTF'S de los pares mas exclusivos del mercado, en los cuales habría que estar al tanto también.