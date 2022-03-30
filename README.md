# Conservation Analyst

The aim of this work is to provide users with a web-based tool to support them in exploring the relative contribution of key datasets documenting biodiversity, ecosystem services and the planning and expanding protected area systems in order to account for complementary conservation criteria, such as biodiversity, carbon storage or the provision of clean water. 

![map](https://raw.githubusercontent.com/lucageo/BAT-GLOBAL/main/img/app.png)

## Use

The first step to use the tool is to select a country. This can be done by clicking on a country, or by using an url parameter to select the country. For instance, the url https://lucageo.github.io/BAT-GLOBAL/bat.html?iso3=MDG integrates the url parameter iso3=MDG corresponding to Madagascar. After selecting a country, users can access the following statistics either for the country’s total land area or only for the country’s protected land area: 

- the normalised scores for above and below ground carbon.
- the normalised score for water presence.
- the normalised score for natural areas.
- the normalised score for intact forest.
- the normalised score for mammals richness.
- the normalised score for threatened mammals richness.
- the normalised score for amphibians richness.
- the normalised score for threatened amphibians richness.
- the normalised score for birds richness.
- the normalised score for threatened birds richness.
- the conservation priority score, representing the sum of the average values of each variable available in the tool. 

Along with the statistics available on the left panel, a dynamic map displays the point grid which is styled according to the sum of all the variables using a colour gradient that spans from orange (minimum value) to green (maximum value). Hovering functions are also available to display the values of each variable.
The tool provides functions to dynamically update the map and related statistics by assigning weights to each variable, in this way the user can set specific conservation priorities and produce specific maps highlighting hot-spots and cold-spots based on the selected parameters. The results can be further refined by excluding or including in the analysis areas that are already protected.
Local spatial analysis can be also performed by selecting specific areas using the square or the polygon tools. In such a way the user can draw specific geometries, perform spatial queries and display the results in a spider chart. On the chart, one can visually analyse results and compare the selected area’s values with the ones related to the country’s lands and the ones corresponding to the country's protected areas.
Finally the tool allows for exporting maps and charts as images or PDF.


![map](https://raw.githubusercontent.com/lucageo/BAT-GLOBAL/main/img/app2.png)
