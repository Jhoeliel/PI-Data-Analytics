# <h1 align=center> **PROYECTO INDIVIDUAL Nº3** </h1>
<p align=center><img src=https://github.com/Jhoeliel/PI-Data-Analytics/blob/main/Dashboard.jpg><p>

Bienvenidos al Proyecto Individual N°3 - Data Analitycs, de la etapa de labs de [HENRY](https://www.soyhenry.com/)
<br/>
Elaborado por Jhoeliel Palma Salazar
<hr>

## **Contexto**
Los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, cuando el profesor Sebastian Thrun comenzó con la transmisión online de su curso introductorio a la Inteligencia Artificial. Poco tiempo después, Thrun fundó Udacity y con el pasar de los años se han ido sumando otras plataformas como edX y Coursera, brindando servicios similares: acceso a contenido específico, de calidad y de manera práctica, desde la comodidad del hogar. Muchas de estas plataformas tienen contenido gratuito mientras que el modelo de negocio en general se basa ya sea en el pago de suscripciones recurrentes para acceso general o únicas, para acceder a certificaciones o a cursos premium. Con el aumento de la popularidad de los MOOCs, no solo han aparecido nuevas plataformas privadas como las mencionadas anteriormente, sino que también muchas universidades y organizaciones sin fines de lucro han sumado a la oferta haciendo el mercado mucho más competitivo. En este contexto, resulta imperante para cada plataforma, ajustar sus modelos de negocio, los cursos y el contenido que se ofrece en los mismos para lograr captar y retener a la mayor cantidad de clientes.

## **Descrpcion**
Empleando los nombres de los títulos de los cursos incluidos en los datasets se genero una WordCloud para recoger rápidamente y de manera visual un análisis de sentimientos sobre las preferencias de los cursos.
Se realizo un EDA y algunas transformaciones así como Feature Engineering para preparar los datasets a ser usados en la preparación del DASHBOARD en Power BI. 
Esta parte del trabajo tanto el WordCLoud como el EDA y preparación de los datasets esta documentado en los archivos .ipynb (jupiter notebooks) que están incluidos en este repositorio.

## **Analisis**
Analizando la data puesta a disposición y segmentando esta información usando la cantidad de estudiantes (suscriptores) se pudo apreciar los siguiente:
* La categoría mas consumida es la de tecnologías de información ya sea web development o computer science. El nombre puede variar de acuerdo a la plataforma y las segunda categoría es la relacionada a negocios como: Bussiness Finance o Bussiness & Management según la plataforma.
* Los cursos mas populares son los relacionados a las categorías mencionadas como por ejemplo: HTML5, web developer o data science.
* El idioma Ingles es el de mayor presencia en estas plataformas teniendo una participación del 90% y el español con 8%.
* Otra característica observada es el nivel al que los cursos van orientados. En gran mayoría son para un publico Beginner (>50%) siendo los cursos para nivel avanzado los de menor consumo (>2%).
* Se observó también que las calificaciones que reciben en los reviews les dan en gran mayoría 5 puntos.
* Analizando la relación entre el numero de alumno inscritos y el numero de reviews otorgadas se puede apreciar que estas ultimas representan un porcentaje bastante bajo. 

## **Conclusiones**
* La apreciación de los cursos es bastante alta principalmente en los cursos de nivel mas básico.
* Existe una tendencia masiva al consumo de cursos de tecnología.
* Dentro de los cursos de tecnología los favoritos son WEB develoment y Data Science.
* La baja correlación entre los reviews y los alumnos inscritos podría significar posiblemente que son cursos que aun no se han terminado de cursar o han sido abandonados. Sin embargo los que si llegaron a terminarse han recibido alta calificación (rating).

## **Recomendaciones**
* La inversión inicial en un MOOC debe estar basada en cursos de tecnología ya que estos son los mas demandados y consumidos por el publico.
* Cuidar la calidad del servicio y contenidos con la intención de obtener el mas alto rating en todos los cursos.
* Monitorear el índice de la relación entre reviews vs cantidad de alumnos. Para poder hacer un seguimiento más preciso se debería considerar comenzar este seguimiento desde las bases de datos relacionales para poder exportar al data lake información relevante que pueda ser aprovechada.
* Así mismo se recomienda recopilar información respecto del número de cursos distintos que llega a tomar una misma persona



