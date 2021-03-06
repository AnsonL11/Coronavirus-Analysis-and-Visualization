# Data Scrapy, Analysis and Visualization for The Pandemic of Covid-19
![covid19](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/Coronavirus%20complication.jpg)
# Overview
This project aims to analyze and understand the spread of coronavirus throughout the world. Covid-19 is the official name of this virus which named by World Health Organization. This project used data Scraping as a technique to retrieve large amounts of data from the website. [Link](https://news.qq.com/zt2020/page/feiyan.htm#/) The data stored by web Scrapping is an unstructured format, it need to convert the unstructured into structured data for Data analysis and exploration.
# What is COVID-19
Coronaviruses (COVID-19) are types of viruses that typically affect the respiratory tracts of birds and mammals, including humans. Doctors associate them with the common cold, bronchitis, pneumonia, and severe acute respiratory syndrome (SARS), and they can also affect the gut. These viruses are typically responsible for common colds more than serious diseases.

This virus is a contagious coronavirus that outburst from Wuhan in China. This new strain of virus has led to a dramatic loss of human life worldwide and presents an unprecedented challenge to public health, food systems and the world of work. This dataset will help us understand the spread of Covid-19 aroud the world.

# Environment
* ``Python 3.8``
* ``Jupyter Notebook``

# Dependencies
**Code to run:** [Covid19 Pandemic analysis.ipynb](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/Covid19%20Pandemic%20analysis.ipynb).

**Visualization:** [nbviewer](https://nbviewer.org/github/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/Covid19%20Pandemic%20analysis.ipynb).

# Import Libraries for web scraping:
* ``pip``
* ``Requests: pip install requests ``
* ``Pandas``
* ``csv``
# Import Libraries for data visualization
* ``Matplotlib``
* ``Plotly``
* ``Plotly express``
* ``Pyecharts``

# Deployment statragies
  1. Define the URL from the website, then check the respond of the URL. (Website: https://news.qq.com/zt2020/page/feiyan.htm#/)
  2. Inspect the page to see under which tag the data want to collect is nested.
  3. Find the information and extract
  4. Store the data in csv format using Pandas
  5. Visualize the results using Plotly, Matplotlib and Pyecharts.
   
# Outcome
 1. Get to know the situation of continents and countries towards the pandemic.
 2. Understand the spread of virus in every single country.
 3. Visualization over the world map.

# Covid-19 Analysis and Visualization

![scatter](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/scatters.png)

The scatter above illustrates the numbers of confirmed cases of Covid-19 among 7 continents in the world. The scatter highlights that Europe is the worst affected continent compare to others as it reach to total 200 million confirmed cases. Asia is the second worst of affected continents it has 150 million confirmed cases; North Ameirica rank to the thrid and the fourth goes to South America followed by Africa and Oceania.

As of May 2022, Over 520 million confirmed cases have been reported globally. This is not a bright sign as it can tell the pandemic has impacted almost every corner of life.This may probably due to an opportunity to stop the spread of the virus during its early stages was missed and it caused serious consequences for many countries such as causing economies to stall, stretching healthcare systems to the limit and governments have been forced to implement harsh restrictions on human activity to control the spread of the virus.

![pie](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/pie.png)

![continent](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/conditions.png)

Two chart above Pie and Bar indicate the situation of Covid-19 throughout the world. The Pie chart is about the ratio of Covid-19 situation whereas the Bar chart is showing the total number of cases. Both charts are divide into 5 categories; confirmed, active, newcases, deaths and recovered cases.
According to the charts, out of over 525 mil confirmed cases reported globaly, over 480 million recovered cases have been reported which is 92% cases have been recovered from the pandemic.

6.8% which is 36 million cases are still active and over 6 million cases which 1.2% people have been reported deaths. It can be seen from information that active and deaths cases reported are less than half numbers compare to recovered cases.
It is clear that the world are getting recovered from pandemic of Covid-19. This may due to goverments around the world have been made a great efforts to emphasize on pandamic prevention and medical attention.
Also, many countries and societies are dedicating to furthering the vaccination ever since numerous vaccines begin their roll out in countries across the world.

![treemap](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/sunburst.png)

The diagram above describe the confirmed cases of Covid-19 of affected continents and countries around the world.
It clearly shows that Europe is the worst affected continents and France is the highest confirmed cases in Europe which has 29 million follow by Germany and UK both countries have 26 million and 22 million total confrimed cases respectively.
Asia is the second worst affected continent and India is the top higher confirmed cases which is 43 million cases and Korea is the second higher which is 17 million confirmed cases.

The thrid goes to North America follow by South America. United States has a significant amount of total confirmed cases not only in North America but of all country, it has total 85 million confirmed cases. Brazil has 31 million confirmed cases the majority affected country in South America.
In Oceania, Australia has the most confirmed cases. This makes sense as Australia is the largest country in this continent.


![vertical](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/vertical.png)

The 4 bar charts above tell the situation of Covid-19 among continents with divided into 4 conditions, they are total number of confirmed cases, active cases, death cases and recovered cases.

Although Europe countries have the most confirmed cases, but they also have the higher recovered cases compare to other continents. This situation can tell that a tremendous medical assistance has plunged into Europe countries.
Asian countries considered more successful in curbing the virus spread, it can tells from the charts above that although Asia is the second higher of confirmed cases, however Asia also the second higher recovered continent and the numbers of active and deaths cases are less than Europe and North America not to mention that Asia is the largest population in the world.

The pandemic prevention measures in North America and South America are relatively unfavorable compare to Asia, this may due to many countires are easing their restriction precaution to curb the spread of virus.
Total cases in Oceania with 4 conditions are relatively low compare to other continents due to less population in this area.


![horizontal](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/horizontal.png)

The diagram above give information of the top 10 affected countries in divided into 4 conditions of confirmed, active, death and recoverd cases in Covid-19 pandemic.
According to charts above, United State, India and Brazil are most concentration of Covid-19 in confirmed and death cases but they also have enormous recovered. This may be due to they had plenty of case to start off with.

Ukraine has climb up to 4.9 million active cases the highest of all country recently, this may due to people living in Ukraine are suffering from depression, food and financial insecurity since Russia started its war with Ukraine at the end of February. People who are concerned about residence and food security or household finances may not be able to take the same pandemic precautions as those with stable condition and good financial security.These concerns can obstruct efforts to stop the spread of Covid-19.

![map](https://github.com/AnsonL11/Coronavirus-Analysis-and-Visualization/blob/main/graphs/map.png)

