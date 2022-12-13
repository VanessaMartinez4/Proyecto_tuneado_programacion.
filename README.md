# Proyecto_tuneado_programacion.

![image](https://user-images.githubusercontent.com/119825521/207254519-40127c25-d59a-4eda-8929-d5516556830a.png)

**UNIVERSIDAD DE COLIMA**

*Facultad de Ingeniería Civil*

*Ingeniero Topógrafo Geomático*

*Curso:*

Programación de computadoras II

*Proyecto:*

Proyección de un perfil y
el cálculo de su longitud en pyqgis

*Profesor:*

M.C. Sebastián González Zepeda

*Alumna:*

Vanessa Belén Martínez Hernández

*Semestre y grupo:*

3 ° B

14 de diciembre del 2022

**Proyección de un perfil y el cálculo de su longitud en PyQgis**
*Projecting a profile and calculating its length in PyQgis*


Vanessa Belén Martínez Hernández

(1) Colima - Coquimatlán Kilómetro 9, Jardines del Llano, 28400 Coquimatlán, Col., 20177585, vmartinez6@ucol.mx

**Resumén**

Este proyecto se realizó con la finalidad de plasmar un poco de lo visto en este semestre, puesto que se usa la librería PyQgis para un proceso el cual tiene que ver con la topografía, tal como lo es la nivelación de perfil y el uso de la plataforma de Qgis, así bien automatizando los pasos, esto quiere decir que la utilidad de este es especial ya que agiliza el tiempo y tiene mejores resultados.

Palabras clave: Qgis, Python, librería, geoespacial, perfil

**Abstract**

This project was carried out with the purpose of capturing a bit of what was seen in this semester, since the PyQgis library is used for a process which has to do with topography, such as profile leveling and the use of the Qgis platform, well automating the steps, this means that the utility of this is special since it speeds up time and has better results.

Keywords: Qgis, python, library, geospatial, profile

 
**1.	Introducción.**

 
La utilización de la librería PyQgis durante este semestre es relevante, es por eso que es característico presentarlo en este proyecto, ya que a lo largo de este semestre se vieron varias bibliotecas de programación en el lenguaje Python que tenían relación con datos geográficos y espaciales. Es por eso que se utiliza QGIS. El cual tiene multitud de herramientas y complementos para el procesamiento de información del terreno o elevaciones y también para su visualización, por lo que es de gran utilidad su aplicación al campo de la topografía.

También, cabe destacar que necesitamos la definición de la nivelación de perfil, pues comprende la relación que tiene su shapefile proyectada en una imagen raster por medio de qgis, así que, la define así, tiene como objetivo determinar las cotas o elevaciones de puntos con distancias conocidas sobre un trazo para obtener el perfil del trazo.
Cuando se requiere del estudio de una vía de comunicación terrestre ya sea de camino, introducción de agua potable, un sistema de alcantarillado, un canal, entre otros; se utiliza este procedimiento el cual se encarga de determinar las elevaciones, cotas y alturas o intervalos cortos sobre una línea fija generalmente sobre el centro de un eje de la vía que se presenta alojar.

**2.	Desarrollo**


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

Se lee el archivo del shapefile del perfil y el de la imagen raster que es de Colima, para asi ambas ser proyectadas y crear capas en Qgis.

![image](https://user-images.githubusercontent.com/119825521/207256509-0aabbe0b-2682-483f-ade2-c2afbb20bdc2.png)

Se mantiene activa la capa para poder leer las características, tales como lo es el perfil, y asi obtener la longitud del mismo.

![image](https://user-images.githubusercontent.com/119825521/207256560-bc1e30c9-6d1d-49ef-b85b-dc29800d6b2b.png)

Se observa que mediante el código se lee la capa raster y la de perfil.

![image](https://user-images.githubusercontent.com/119825521/207256622-7422ff5b-38e3-4422-a8a6-c5b64bd26af8.png)

**3.	Manejo de datos**

Para este programa se realiza un análisis de la librería de PyQgis, la cual se puede utilizar en una consola de Python en el software de Qgis. Primeramente, se analiza la capa del vector, la cual fue resultado de los datos de una práctica de campo llevada a cabo en la Facultad de Ingeniería Civil en el camino del estacionamiento. Una vez obtenido el shapefile del vector, se realiza un programa el cual permite abrir una capa de archivo “.shp” y de esta misma calcula la longitud que esta tiene.

Python
 
Python es un lenguaje de programación orientado a objetos de alto nivel y fácil de interpretar con sintaxis fácil de leer. Ideal para prototipos y tareas ad hoc, Python tiene un amplio uso en computación científica, desarrollo web y automatización. Como lenguaje de programación para principiantes y de uso general, Python es compatible con muchos de los principales científicos de computadoras y desarrolladores de aplicaciones en todo el mundo.

Qgis

QGIS	es	un	Sistema	de	Información Geográfica (SIG) de Código Abierto licenciado bajo GNU - General Public License . QGIS es un proyecto oficial de Open Source Geospatial Foundation (OSGeo). Corre sobre Linux, Unix, Mac OSX, windows y Android y soporta numerosos formatos y funcionalidades de datos vector, datos ráster y bases de datos. QGIS	funciona		en	diferentes sistemas operativos: Linux, Windows, Mac y Android. Uno de sus puntos fuertes es la interoperabilidad y te permitirte trabajar con una multitud de datos vectoriales y raster. Por citar algunos:

• Formato Shapefile (.shp formato nativo de QGIS) desarrollado por ESRI ArcGIS.
•Formatos MapInfo (.tab, mif-mid).
•Formato KML de Google Earth.
•Formatos DAO (Autocad DXF).

**4.	Conclusiones**

En relación con el programa realizado con la librería de pyqgis, refleja asi un poco de todo lo visto durante todo el semestre. Realizando  una proyeccion de un perfil reflejada en una imagen raster. En está librería observamos que tiene bastante relación dentro de nuestra carrera, pues la aplicación de los diferentes códigos vistos en clases, nos facilitan y agilizan la interacción de varios procesos con la plataforma Qgis, asi como las diferentes librerías existentes en relación con Python y la datos geoespaciales.

**Referencias**

https://www.certicalia.com/blog/como-utilizar-qgis-topografias#:~:text=El%20Qgis%20aplicado%20a%20la,gr%C3%A1ficos%20de%20los%20mapas%20digitales.

https://docs.qgis.org/2.14/es/docs/pyqgis_developer_cookbook/index.html

https://mappinggis.com/2014/02/primeros-pasos-con-pyqgis/


