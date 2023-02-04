![](https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/portada%202.png)

<p align="center">
  <a href="#english">
    <img src="https://raw.githubusercontent.com/lipis/flag-icon-css/master/flags/4x3/gb.svg" alt="English" width="32" height="32">
  </a>
  <a href="#spanish">
    <img src="https://raw.githubusercontent.com/lipis/flag-icon-css/master/flags/4x3/es.svg" alt="Spanish" width="32" height="32">
  </a>
</p>

# English  


The objective of this project is to carry out an exhaustive exploratory analysis of the data of the information provided by Airbnb of the city of Buenos Aires. The goal is to better understand the city's housing rental market and gain insights and patterns from the data.

Through the analysis, it is sought to obtain conclusions about the supply and demand of housing in the city, as well as about the characteristics of the houses and the areas in which they are located. This analysis can be useful for homeowners in the city, as well as for the general public seeking information on the housing rental market in Buenos Aires.

---

[PROJECT](https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/airbnb_baires.ipynb)

I recommend downloading to be able to view all the interactive graphs correctly.

---

### WHAT WE CAN FIND
We can find a heat map like the following. They are used to visualize the correlation between different variables allowing an easy and quick interpretation between them and their intensity. In this case, the Spearman method is used, which measures the linear relationship between two variables.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/output.png" alt="Classification" style="width: 80%; height: auto;" />

---

Having the coordinates of the accommodation is wonderful and allows you to make graphs like the following. An interactive map that makes it very easy to see the location of each Airbnb accommodation and allows you to identify patterns.
FastMarkerCluster allows you to visualize the points in the form of clusters or groups, while the Folium library allows you to create the interactive and personalized map very efficiently. Very useful for visualizing geographic data.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/mapa1PNG.PNG" alt="Classification" style="width: 80%; height: auto;" />

--- 

In this map we can see by intensity of colors the average price by neighborhoods of the Autonomous City of Buenos Aires. Folium is used again to create the map with the geographic information provided by the GeoJSON file.
A dataframe has been created that contains the neighborhoods and their average prices. It is later converted to a dictionary with the "to_dict()" method. And finally, the Folium "StepColormap" function is used to assign a color to each neighborhood.
Being interactive, if you hover over a neighborhood, its name and average price are displayed.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/mapa2.PNG" alt="Classification" style="width: 80%; height: auto;" />

---

We can also find in this project many visualizations like the following. Where information is collected from the 10 neighborhoods with the most Airbnb accommodations with the variant of seeing the type of accommodation and its distribution.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/newplot.png" alt="Classification" style="width: 80%; height: auto;" />



---
---


# Spanish

Este proyecto tiene como objetivo llevar a cabo un análisis exploratorio exhaustivo de los datos de la información proporcionada por Airbnb de la ciudad de Buenos Aires. El objetivo es comprender mejor el mercado de alquiler de viviendas en la ciudad y obtener patrones e información valiosa a partir de los datos.

A través del análisis, se busca obtener conclusiones sobre la oferta y demanda de viviendas en la ciudad, así como también sobre las características de las viviendas y las áreas en las que se encuentran. Este análisis puede ser útil para propietarios de alojamientos en la ciudad, así como también para el público en general que busca información sobre el mercado de alquiler de viviendas en Buenos Aires.

--- 

[PROYECTO](https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/airbnb_baires.ipynb)

Recomiendo descargar para poder visualizar todas las gráficas interactivas correctamente.

---


### LO QUE PODEMOS ENCONTRAR
Podemos encontrar un mapa de calor como el siguiente. Se utilizan para visualizar la correlación entre diferentes variables permitiendo una fácil y rápida interpretación entre ellas y su intensidad. En este caso, se usa el método de Spearman, que mide la relación lineal entre dos variables.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/output.png" alt="Classification" style="width: 80%; height: auto;" />

---

Tener las coordenadas de los alojamientos es maravilloso y permite realizar gráficas como las siguientes. Un mapa interactivo que ayuda a ver muy fácilmente la ubicación de cada alojamiento de Airbnb y permite identificar patrones.
FastMarkerCluster permite visualizar los puntos en forma de clusters o agrupaciones, mientras que la librería Folium permite crear el mapa interactivo y personalizado muy eficientemente. Muy útil para visualizar datos geográficos.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/mapa1PNG.PNG" alt="Classification" style="width: 80%; height: auto;" />

--- 

En este mapa podemos ver por intensidad de colores el precio medio por barrios de la Ciudad Autónoma de Buenos Aires. Se vuelve a usar Folium para crear al mapa con la información geográfica que proporciona el archivo GeoJSON.
Se ha creado un dataframe que contiene los barrios y sus precios promedios. Más tarde se convierte en un diccionario con el método "to_dict()". Y finalmente, se utiliza la función "StepColormap" de Folium para asignar un color a cada barrio.
Al ser interactivo, si pasas el cursor por encima de un barrio se muestra su nombre y media de precio.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/mapa2.PNG" alt="Classification" style="width: 80%; height: auto;" />

---

También podremos encontrar en este proyecto muchas visualizaciones como la siguiente. Donde se recoge la información de los 10 barrios con más alojamientos de Airbnb con la variante de ver el tipo de alojamiento y su distribución.

<img src="https://github.com/silvilio/EDA-Airbnb-BuenosAires/blob/main/Im%C3%A1genes/newplot.png" alt="Classification" style="width: 80%; height: auto;" />
