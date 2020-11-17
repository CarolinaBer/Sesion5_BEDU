# Sesión5 BEDU:Consultas en MongoDB.
Para realizar las consultas haremos uso de las ***expresiones regulares** (regular expresions)*** 
![imagen](regex.png)
### :pushpin: Reto 1. Expresiones regulares.
Usando la base de datos `sample_airbnblistingsAndReviews`, realiza los siguientes filtros:

- Propiedades que no permitan fiestas.
- Propiedades que admitan mascotas.
- Propiedades que no permitan fumadores.
- Propiedades que no permitan fiestas ni fumadores.
### :pushpin: Reto 2. Notación punto y arreglos. 
Usando la colección `sample_airbnblistingsAndReviews`, agrega un filtro que permita obtener todas las publicaciones que tengan 50 o más comentarios, que la valoración sea mayor o igual a 80, que cuenten con conexión a Internet vía cable y estén ubicada en Brazil.
**NOTA** En este caso es mejor utilizar el código de país para encontrar la ubicación deseada. 
### :pushpin: Reto 3. Introducción a las agregaciones.
Usando la colección `sample_airbnblistingsAndReviews`, mediante el uso de agregaciones, encontrar el número de publicaciones que tienen conexión a Internet, sea desde Wifi o desde cable (Ethernet).
