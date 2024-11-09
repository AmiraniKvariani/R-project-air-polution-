# R-project-air-polution-
Exploring topics of air polution and global warming using statistical analysis in R
Subject
Climate change causes changes in many other indicators on our planet. Observing it and 
finding information about it allows us to assess the current situation on Earth and determine 
what problems it causes. almost every data that are on internet has problems and clear 
boxes, maybe because data about climate, temperature, air pollution is not easy to collect, 
but I try to make maximum and try to identify any connection between air quality, pollution, 
people death and healthy environment. 

• first of it is necessary to understand the general situation about the air quality and 
question is in which countries are the most problematic toward the air pollution. It is 
measured by AQI index and I choose this important column a value from the main 
dataset. AQI is a yardstick that runs from 0 to 500. The higher the AQI value, the 
greater the level of air pollution and the greater the health concern. For example, an 
AQI value of 50 or below represents good air quality, while an AQI value over 300 
represents hazardous air quality. From my dataset in Korea there is terrible situation 
but Korea is separated from other world so I do not have information about the 
cause ‘seasons. Besides there are too many countries and difficult to see chart to 
select first 30 largest countries to make analyse more specific. I have one categorical 
and one numeric vector so use bar chart. As the result, in Saudi Arabia, Pakistan, in 
Mauritania, in India, and China is terrible situation. Reasons are: industrial emissions,
vehicular pollution, open burning of agricultural residues, construction activities, 
inefficient household energy sources, and dust from construction sites and roads. I 
also make chart in shiny app so user can control the number of countries.
Source from here: https://www.worldometers.info/geography/largest-countries-inthe-world/
• In second part I tried to find, is there connection between earth surface temperature 
change and death numbers in population? Data was hard to tidy because there are 
so many missing values. Still there are too many countries and try to make more 
specific. I choose g20 countries. Group of 20 is an intergovernmental forum 
comprising 19 countries and the European Union. It works to address major issues 
related to the global economy, such as climate change mitigation, and sustainable 
development etc. there is not full 20 because the values was missing. Chart type is 
timeline. Data was about last 30 years to 2020 and let’s say that there no changes 
through this years, very little bit decrease but they are almost horizontal which is 
quit interesting. That might mean that even these countries who are responsible and 
try to solve problems for example climate change mitigation, have no big change and 
the results every year are the same. Highest death percentage among these 
countries have again, India, Saudi Arabia and Indonesia, and the main reason is in my 
previous chart, because in this countries air pollution index is very high. 
Next chart is the scatterplot because I wanted to understand if there is any correlation 
between temperature change and death percentages? Temperature change is from 0 to 
maximum3. From 0 to 1 is normal/good. +-3 is quite bad for global warming for 
example. Most countries have around 0 to +-1 changes and death rate is low. Even in 
Canada for example the temperature change was +3 degree, but have the low death 
percentage. Such category can consider countries such as: Germany, Italy, USA. France. 
The reason might be that these are strong and developed countries and health care and 
technologies are improved. But in Indonesia, Saudi Arabia and India there is worse 
situation. to conclude, the surface temperature change is one of the reasons of global 
warming, air pollution and deaths but not only reason to die the people. (Canada 
situation)
• And the last part it is important to identify the forest area and “tree number” in 
several countries and are the lack of green territory is the reason of too much air 
pollution. First of all, have a again 30 largest countries to identify in which countries 
have the big share of forest and I choose to select countries by size to identify what 
happened in big territory countries. There is a bar chart and among big countries, 
Peru, Congo, Columbia, Brazil and Angola has highest share of forests. Interesting is 
that even in Indonesia there is hight percentage, +50, there is still problems about 
pollution and deaths. Again, user can use shiny app and select desired numbers of 
countries. Lastly, make a scatterplot again to see is there any correlation between 
forests share area and temperature quality index? Every chart is connected to each 
other, but climate is not depended only one thins and it is hart to strongly agree that 
there is correlation or not. As you can see, in Brazil, Peru, Russia, USA, Columbia, 
there are very high percentage of forest and quite normal and green situation. In 
Congo there is +60 but not green are so there are other problems. But in Libya, south 
Africa, India, Saudi Arabia, Pakistan there are hazardous situation of air pollution and 
very low percentage of forest, so as a recommendation it might help to clean the 
areas an expand the forest territory for more oxygen. 
Note: as I already mentioned above these data are maybe very had to collect or have the 
exact answer during research so in data there are so many problems, missing values and 
NAs. First time I thought that clear the code to be good to see, but I decide to remain 
everything what I did and how can I clear and make everything to see my work.


Sources
https://climatedata.imf.org/pages/climatechange-data
https://ourworldindata.org/air-pollution
https://ourworldindata.org/air-pollution#air-pollution-is-one-of-the-world-s-leading-riskfactors-for-death
analysis
