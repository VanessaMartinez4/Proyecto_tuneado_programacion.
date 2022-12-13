# Proyecto_tuneado_programacion.

![image](https://user-images.githubusercontent.com/119825521/207254519-40127c25-d59a-4eda-8929-d5516556830a.png)
*UNIVERSIDAD DE COLIMA*
Facultad de Ingeniería Civil
Ingeniero Topógrafo Geomático
Curso:

Programación de computadoras II

Proyecto:

Proyección de un perfil y
el cálculo de su longitud en pyqgis

Profesor:

M.C. Sebastián González Zepeda

Alumna:

Vanessa Belén Martínez Hernández

Semestre y grupo:

3 ° B

14 de diciembre del 2022

Proyección de un perfil y el cálculo de su longitud en PyQgis
Projecting a profile and calculating its length in PyQgis


Vanessa Belén Martínez Hernández

(1) Colima - Coquimatlán Kilómetro 9, Jardines del Llano, 28400 Coquimatlán, Col., 20177585, vmartinez6@ucol.mx

Resumén

Este proyecto se realizó con la finalidad de plasmar un poco de lo visto en este semestre, puesto que se usa la librería PyQgis para un proceso el cual tiene que ver con la topografía, tal como lo es la nivelación de perfil y el uso de la plataforma de Qgis, así bien automatizando los pasos, esto quiere decir que la utilidad de este es especial ya que agiliza el tiempo y tiene mejores resultados.

Palabras clave: Qgis, Python, librería, geoespacial, perfil

Abstract

This project was carried out with the purpose of capturing a bit of what was seen in this semester, since the PyQgis library is used for a process which has to do with topography, such as profile leveling and the use of the Qgis platform, well automating the steps, this means that the utility of this is special since it speeds up time and has better results.

Keywords: Qgis, python, library, geospatial, profile

 
1.	Introducción.

 
La utilización de la librería PyQgis durante este semestre es relevante, es por eso que es característico presentarlo en este proyecto, ya que a lo largo de este semestre se vieron varias bibliotecas de programación en el lenguaje Python que tenían relación con datos geográficos y espaciales. Es por eso que se utiliza QGIS. El cual tiene multitud de herramientas y complementos para el procesamiento de información del terreno o elevaciones y también para su visualización, por lo que es de gran utilidad su aplicación al campo de la topografía.

También, cabe destacar que necesitamos la definición de la nivelación de perfil, pues comprende la relación que tiene su shapefile proyectada en una imagen raster por medio de qgis, así que, la define así, tiene como objetivo determinar las cotas o elevaciones de puntos con distancias conocidas sobre un trazo para obtener el perfil del trazo.
Cuando se requiere del estudio de una vía de comunicación terrestre ya sea de camino, introducción de agua potable, un sistema de alcantarillado, un canal, entre otros; se utiliza este procedimiento el cual se encarga de determinar las elevaciones, cotas y alturas o intervalos cortos sobre una línea fija generalmente sobre el centro de un eje de la vía que se presenta alojar.

2.	Desarrollo


El Qgis aplicado a la topografía funciona como una base de datos la cual contiene información geográfica en forma de datos alfanuméricos. Estos datos se asocian mediante identificadores comunes en objetos gráficos de los mapas digitales.

A la hora de marcar un objeto en el mapa digital inmediatamente se saben las propiedades del mismo. También puede realizarse la búsqueda al revés. Un registro de la base de datos llevará asociada su ubicación en la cartografía.

La utilización del Qgis se realiza básicamente para la gestión de la información espacial; este ayuda a la división de la información en distintas capas temáticas. Estas se almacenan de forma independiente para poder utilizarlas de manera rápida y sencilla. De esta manera ayuda al topógrafo y al cartógrafo a relacionar la información a  
través del significado geoespacial de los objetos. Por ejemplo, el uso del programa permite la resolución de diferentes elementos en lo que respecta a la información geográfica:

– Localización: Particularidades de un lugar concreto.
– Tendencia: Cotejo entre situaciones temporales o espaciales sobre características.
– Rutas: Cálculo de rutas entre varios puntos.
– Pautas: Detección de pautas espaciales.
– Modelos: Generación de modelos a partir de situaciones o actuaciones simuladas.

Por último, es un programa de gran importancia que aporta una multitud de soluciones en diferentes ámbitos de actuación. Su versatilidad hace de él, una solución fundamental para su aplicación en casi todos los ámbitos.

La utilización de la librería PyQgis mantiene varias ventajas tales como generar scripts en donde se pueda almacenar procesos, lo cual se ahorra tiempo y se tiene mas precisión. Además se puede generar con más facilidad inventarios, informes y consultas sobre los contenidos

Primeramente, se debe contar con una imagen raster de la zona en donde se realizo el perfil, esta imagen puede obtener por medio de la pagina de Inegi.  ![image](https://user-images.githubusercontent.com/119825521/207255011-bf22658e-96e7-49fe-bd27-c53efc5eda3c.png)

Tambien debe de obtener el shapefile del perfil, en este caso, se hizo un proceso en ArcMap para poder obtenerlo. Y se muestra como se ve el shapefile y su representacion grafica de la nivelacion de perfil. 
![image](https://user-images.githubusercontent.com/119825521/207255058-dc78abe9-51f2-48b3-a056-df32da6b1721.png)
![image](https://user-images.githubusercontent.com/119825521/207255093-ce48eda7-738a-43a6-af2b-8eb1cd8d1d3d.png)

Se abre la consola de Python que tiene el software Qgis para pegar el código que se creo para realizar este proceso, el cual consiste en primeramente, importar todas las librerías(en caso que lo hiciéramos en un editor exterior) si lo realizamos en el de qgis, no es necesario.
![image](https://user-images.githubusercontent.com/119825521/207255152-56e4585d-ff9f-4a0e-bea3-009ee2910fa8.png)


