## Analisis de Datos con Power BI

- Creado por: Camilo Mejía Ramírez
- Fecha Inicio: 15 marzo 2024.
- visita mi sitio web: [camilomejiar.com](https://camilomejiar.com/)

<br>

## Business Inteligence BI.

Es la habilidad de transformar los datos e información de forma agil que permita
tomar decisiones mejor fundamentadas. Esto va desde la recopilación y analisis de datos hasta la creacion, 
visualización e informes. 

## Flujo de BI

  * ETL: Extracción de datos, consolidacion de fuentes, limpieza y transformación.
  * Modelado: Relaciones, indicadores, optimización.
  * Reporting: Visulación de datos, reportes, dashboards, storytelling.

## Suite de Negocio

Es conjunto integrado de herramientas y aplicaciones que abarcan diferentes aspectos de la gestión empresarial.
Entre ellas encontramos las siguientes.

  * Power BI Desktop. Es una herramienta de inteligencia empresarial construida por Microsoft, permite a los usuarios
    crear visualizaciones de datos interactivas y significativas. Con Power BI Desktop, puedes conectar, transformar
    y modelar datos de diversas fuentes para luego diseñar cuadros de mando y reportes que ofrecen información valiosa
    para la toma de decisiones.

  * Power BI Service.  Es una herramienta que al igual que Desktop cumple con las mismas funciones, la unica diferencia
    es que esta se encuentra en la nube y permite establecer todo en ambiente colaborativo con otros usuarios, es decir
    que puedes programar actualizaciones de datos, compartir informes con colegas, configurar alertas, y acceder a
    tus visualizaciones desde cualquier dispositivo con conexión a Internet.

  * Power BI Mobile. Es una extensión de de Power BI, la cual te permite acceder a reportes, informes y demas interacciones
    en tiempo real, desde un dispositivo mobile.

## Como Descargar e Instalar Power BI Desktop.

1. Ve al navegador de tu elección y escribe: power bi
2. Vamos a ir a la primera opcion que aparece power bi Microsoft
   
   ![descarga powerbi](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/d7191396-c017-43c6-a8b5-e586bd373e42)

3. Si queremos descargar Power Bi Desktop seleccionamos:
   3.1. Producto.
   3.2. Power Bi.
   3.3. Desktop.

   ![desktop powerbi](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/02a549f5-dddf-47c9-a004-0fa125fb3734)

4. Al dar clic en Desktop, este te abrira un enlace en donde daras Descargar gratis, posteriormente te abrira una venta de
   Microsoft Store, el cual en el caso mio ya esta instalado, de lo contario te saldria descargar y posteriormente seguir la ruta
   respectiva.

   ![descarga](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/fd431706-31b3-4e50-a859-3e7ca5c5153b)
   ![abrir microsft](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/062eea44-20e6-42ca-9514-4b523bec890a)

5. Por ultimo te saldra la ventana principal de Power BI, el cual corresponde al Desktop.

   ![escritorio powerbi](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/5df3677b-107c-4baa-a5c9-8d29eeb9b70b)


### Nota: hay que tener presente que la version Desktop, corresponde a la estructuracion de los informes y la version service y mobile, corresponde a la entrega de los resultados de los analisis que se realizaron.

<br>

## Arquitectura de Power BI

Existen distintas arquitecturas o planes que incorporan los componentes de Power BI de forma diferente.

## Power BI FREE.
Esta corresponde a la version gratuita, la cual es utilizada para realizar pruebas o ejercicios de practica, esta presenta las siguientes caracteristicas:

  * Incluye 1 GB de Almacenamiento.
  * No permite la colaboración simultanea (reportes, dashboards y database).
  * Compartir reportes solo es posible en modo público. Por lo cual se recomienda de uso practica, puesta toda la información estara expuesta en caso de ser   tipo   organización.

## Power Bi PRO.
 Ofrece las herramientas de Power BI FREE e incluye otras herramientas colaborativas:

   * Incluye 10 GB de Almacenamiento.
   * Se puede compartir con usuarios internos (siempre y cuando cuenten con la licencia PRO)
   * Permite compartir la información de manera segura y confiable.
   * Cuenta con una opción de puerta de enlace (Power BI Gateway) este soporta hasta 8 re cargas por día.

## Power BI PREMIUM.
  Ofrecer los servicios Power Bi PRO con algunas mejoras y herramientas colaborativas:

   * Incluye 100 TB de Almacenamiento.
   * Se puede compartir con usuarios internos (incluso aquellos que no tengan Power BI PRO).
   * Mayor escalabilidad y rendimiento que la capacidad compartida en Power BI SERVICE.
   * Cuenta con Power BI Gateway (soporta hasta 48 recargas por día).

<br> 
Las siguientes son lecturas recomendadas:
  
  [Comparaciones y precios](https://powerbi.microsoft.com/es-mx/pricing/)

<br>

## Como conectarse a una Base de Datos.

En esta seccion vamos a conocer los tipos de conexiones que exiten en Power BI, siendo una de ellas la base de datos SQL Server.

## Instrucciones:
   1. Abrimos Power Bi Desktop desde el computador.
   2. Al abrir la pantalla principal de Power BI nos dirigimos a Inicio y enseguida Obtener datos y se elige la opcion SQL Server.
     
      ![sql server](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/67e6cdd4-7641-4a21-9bed-85ebeb8d5a46)

   3. Al ingresar los datos del Servidor y Bases de Datos (opcional).
     * Agregamos las nuevas credneciales que nos otorga y procedemos con el cargue de la misma informacion.
     
   ![ingreso](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/f6005b14-93f0-4281-922e-6fa49afae5de)

   4. Seleccionamos la pestaña Bases de Datos e ingresamos la informacion correspondiente.

  ![seleccionar](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/c49fe470-fb17-46b5-931b-995ff7d6d73d)
  
   5. Enseguida aparecen las tablas de la Base de Datos y seleccionamos las que vamos a cargar.
  
 ![tablas](https://github.com/camilomejiar/Analisis_de_Datos_PowerBI/assets/101876440/26da9892-c5b1-4de0-a5a5-4f4df2628608)

Con esto finalizamos la Conexion a una Base de datos desde SQL Server. 
  
## Tipo de Conexiones
   Power BI nos permite conectar a multiples fuentes de datos, entre ella encontramos archivos en Excel, BSQ Server, hasta sitios web.

   * IMPORT (Importanción). Los datos se copian a manera local dentro del modelo de Power BI (es el mas común).
   * Direct QUery. Los datos no se copian, pues cada interacción solicita una consulta a la base de datos (se recomienda su uso cuando los datos cambian con frecuencia).
   * Live Connection o Dinámica. Se realiza con lectura desde SSASS o desde un conjunto de datos de Power Bi Service.
   * Modelos Compuestos. Combina las tecnologias de importaciones y Direct Query. Permite la conexion en multiples conjuntos de datos.

## Preparación de los datos con Power BI.
Antes de iniciar a trabajar en la fuente de información, esta no esta lista para ser aprovechada visualmente y generalmente tiene datos que no estan sincronizados. Es aqui en donde tenemos diversos procesos de transformación para obtener una base de datos limpia, ordenada y apta para ser trabajada, para ello vamos a comenzar a definir ¿que es ETL? y cual es su impacto.

¿Que es ETL?
ETL, es un proceso intermedio entre las fuentes de datos originales de donde extraemos la información y el modelado de datos para su analisis posterior. 

* Extract (Extraer). Desde prácticamente cualquier fuente de datos, desde archivos planos hasta complejos, dases de datos o servicios cloud.
  
* Transform (Transformar). Pemrite modificar o enriquecer la información sin modificar la fuente.

* Load (Cargar). Ena vez realizada la transofmración. se encarga de cargar el resultado al modelo de datos.

¿Que es Power Query?
Se puede definir como un tipo de tecnologia de conexion de datos que permite detectar, conectar, combinar y refinar distintos origenes de datos para satisfacer las necesidades de análisis y visualización.

¿Que hace Power Query?
Principalmente realiza el proceso de ETL (Extraer, Transformar y Cargar) en Power BI para su posterior análisis. 
Nota. El objetivo de Power Query no es analizar los datos.

Se podria decir que Power Query es similar a los macros de Excel, en donde nos permite llegar a una serie de resultados que permiten retroceder o avanzar sin modificar los datos originales.

¿Como usar Power Query?.
