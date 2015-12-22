---
layout: post
title: Population and GDP across Mexico
tags:
  - mexico
  - data analysis
  - statistics

---
I found a TopoJSON map of Mexico - made from Mike Bostock's very easy-to-follow [example](bl.ocks.org/mbostock/9265467), and a dataset of population and GDP per municipality; so I set out to make a small visualization with it, and the result is the following map.

Note: The bottom bars represent population and GDP per municipality. On these bars, the coloring of each municipality is by quintiles over GDP. Notice how 20% of all GDP is produced in only 2.36% of municipalities, and so on. The visualization can be manipulated by clicking on those bars.

<iframe src="http://pabloem.github.io/inegi/gdp/index.html?lang=en" width="760" height="720" frameborder="0" scrolling="no"> </iframe>

I liked the visualization because we can see a lot of interesting patterns. First of all we can see the fact that Mexico has become a diverse and well distributed economy. A few municipalities with very high GDP are the area nearby the [Cantarell Complex](https://en.wikipedia.org/wiki/Cantarell_Field), the largest oilfield in the country; but the top 10 most productive municipalities don't really concentrate on a single area (Monterrey, Guadalajara, Mexico City, Toluca and the Cantarell region). As we go further and further, we can see regions all over the country lighting up: Some large cities, some touristic destinations, industrial centers, and border cities.

Unfortunately, the map allows us to visualize two other facts that are not so uplifting. On the one hand, we can observe economic inequality: A total of 140 municipalities produce 90% of the GDP in the country, but house only 50% of the population. This means that 50% of the population lives very close to the main areas of production in the country, while the other 50% lives in areas that are generally less prosperous.

The other saddening fact evidenced by the map is poverty in the south of the country. Particularly in the state of [Oaxaca](https://en.wikipedia.org/wiki/Oaxaca). Although it is also fair to say that municipalities in Oaxaca are smaller, and the economic output of the state may have been broken down into smaller parts. (Visualization on GDP per state pending!).

Anyway, hope you liked the map! All comments are welcome! : )

Also, for those curious on details on the data, you can find the information on [the API](http://www.inegi.org.mx/desarrolladores/indicadores/apiindicadores.aspx) that I used, as well as the indicators on the [National Institute of Geography and Statistics' website](http://www.inegi.org.mx).
