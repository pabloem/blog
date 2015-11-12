---
layout: post
title: Las Tortillas nos unen
language: spanish
tags:
  - español
  - data analysis
  - mexico
---

Hace poco descargué una base de datos con información de negocios de "manufactura" del sitio web del INEGI. 
La información está disponible en [el sitio web del INEGI](http://www3.inegi.org.mx/sistemas/descarga/), y hay
muchas cosas interesantes. Me puse a jugar con esos datos, y decidí hacer mi primera visualización de mapa, donde
se puedan observar patrones geográficos en los datos.

Al estar observando los datos, me di cuenta de que el tipo de negocio más común en la base de datos es el de 
tortillerias. Así es: tenemos más tortillerías en México, que cualquier otro tipo de negocio que fabrique algo. 
Se me hizo muy chistoso. Decidí estudiarlo en un pequeño mapa del Distrito Federal; y para no mostrar solamente 
tortillerías, busqué información sobre la población y el producto interno bruto de cada delegación. Todos
estos datos los pueden visualizar en el mapa que ven a continuación:

<iframe src="http://pabloem.github.io/inegi/df_d3_es.html" width="950" height="650" frameborder="0" scrolling="no"></iframe>

Hay muchos patrones interesantes. Por ejemplo, el número de tortillerías y la población tienen casi los mismos
colores en el mapa! - y la coloración del mapa de tortillerías per cápita es bastante uniforme! Sin importar el
PIB, ni el per cápita; la concentración de tortillerías en el Distrito Federal es de entre 3 y 10 por cada 1000 
personas. Es decir, que no importa que seamos ricos o pobres: Todos los Defeños comemos bastantes tortillas
(y cómo no? Si los tacos son lo mejor que hay).

Por otro lado, se pueden ver unos datos que no son tan alentadores: Las disparidades en el Producto Interno Bruto;
y especialmente las del PIB per cápita. Podemos ver que la delegación más poblada (Iztapalapa) es también 
una de las delegaciones con el *menor* PIB del DF; mientras que la Miguel Hidalgo tiene un PIB más de 6 veces
más grande. Esto habla de muchísima desigualdad. Claro, el PIB no representa exactamente el nivel de ingresos 
de los habitantes de cada zona; sino que representa la riqueza generada en esas zonas cada año - y claro,
zonas con negocios como las delegaciones Cuauhtémoc y Miguel Hidalgo tienen un PIB alto, aunque muchos de 
los trabajadores vengan desde otras zonas. 

Sin embargo, las disparidades no dejan de ser nada menos que *escandalosas*. De hecho, el PIB per cápita de la 
delegación Miguel Hidalgo es comparable con el de los países más ricos del mundo (hagan la conversión: Unos 
80,000 USD. Equivalente al de Suiza!); mientras que el PIB per cápita de la delegación Iztapalapa es de unos 
2,400 USD: Comparable al de Gana; y apenas 3% del de la Miguel Hidalgo.

De nuevo, no es posible atribuir estas diferencias solamente a la desigualdad económica - y tampoco es posible
decir que es todo debido a la distribución desigual de empresas y medios para generar riqueza. Hay muchos 
problemas que contribuyen a esta desigualdad; pero por ahora sólo vamos a considerarla.

Mientras tanto, podemos recordad que aunque la ciudad está llena de contrastes, hay algo donde todos estamos
en la misma página: Las Tortillas nos Unen.
