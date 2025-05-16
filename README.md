# Pickup-point-assessment-on-spatial-data
analytical solution for assessing potential locations for pick-up points based on spatial data

Development of an analytical solution for assessing potential locations for pick-up points based on spatial data
This Jupyter Notebook contains a practical implementation of the graduation thesis aimed at developing an analytical tool to evaluate and select optimal locations for pick-up points (PUPs), based on spatial data and modern GIS methods.
Data preparation and processing:
* Integration of spatial layers: residential buildings, POIs, road network, transit stops, rental locations.
* Construction of a hexagonal grid for spatial aggregation.
Spatial analysis:
* Calculation of POI density and proximity.
* Network analysis using the road network (OSM).
* Identification of hot and cold spots using the Getis-Ord Gi* method.
* Modeling attractiveness factors through Geographically Weighted Regression (GWR).
* Application of a modified Huff model.
Economic evaluation:
* Modeling location profitability using the Monte Carlo method.
* Comparing locations by overall attractiveness and return on investment.
Technologies used: geopandas, networkx, osmnx, pysal, statsmodels, matplotlib, folium, h3, numpy, pandas.
Goal: To develop an intelligent approach for placing pick-up points based on geospatial data, considering factors such as demand, competition, transport accessibility, and rental attractiveness.

Разработка аналитического решения для оценки потенциальных мест размещения пунктов вывоза заказов на основе пространственных данных

 Описание проекта

Данный Jupyter Notebook содержит практическую реализацию выпускной квалификационной работы, целью которой является разработка аналитического инструмента, помогающего оценивать и выбирать оптимальные локации для размещения пунктов выдачи заказов (ПВЗ), основанного на пространственных данных и современных ГИС-методах.
Подготовка и обработка данных:
Интеграция пространственных слоёв: жилые здания, POI, дорожная сеть, остановки, арендные помещения.
Построение гексагональной сетки для пространственной агрегации.
Пространственный анализ:
 Расчёт плотности и близости POI.

 Сетевой анализ с использованием дорожной сети (OSM).

 Выявление горячих и холодных зон методом Getis-Ord Gi*.

 Моделирование факторов привлекательности через GWR.

 Применение модифицированной модели Хаффа.
 Экономическая оценка:
Моделирование доходности точек методом Монте-Карло.
 Сравнение локаций по совокупной привлекательности и окупаемости.
 Используемые технологии:
  geopandas, networkx, osmnx, pysal, statsmodels, matplotlib, folium, h3, numpy, pandas.

 Цель:

Сформировать интеллектуальный подход к размещению ПВЗ на основе гео-данных, учитывая факторы спроса, конкуренции, транспортной доступности и арендной привлекательности.
