# HISTORY_OF_THE_FIFAWC
This is a report on the history of the World Cup since inception, Team performance and an in-depth look into the current Holders of the Title.
## TABLE OF CONTENT<br>
> INTRODUCTION
---
> Tournaments From 1930 till 2022
---
> How Has Host Nations fared during the Tournaments
---
> FIFA WORLD CUP 2022
---
> HOW ABOUT THE TEAMS RESPECTIVE AGE GROUP
---
> DOMINANCE OF ARGENTINA IN TOURNAMENTS
---
> Okay Let's dig In!!
### INTRODUCTION<br>
> The World Cup is the most prestigious association football tournament in the world, and it's thought to be the most widely viewed and followed single sporting event in the world. To participate in this tournament, a world cup qualifier is organized for countries in their respective continents and this has been the case since 1930 till date. <br>
I decided to analyse and visualize this data due to my interest in football, i am an ardent lover of the game of football and i am going to walk you through the steps taken.<br><br>![f_](https://github.com/Kaybhee/HISTORY_OF_THE_FIFAWC/assets/106836064/b7b50bff-6041-4cf8-ac53-0c93548eab40)<br>

### TOURNAMENTS FROM 1930 TILL 2022<br>
>The FIFA World Cup occurs every 4 years and 22 tournaments have been hosted, between 1930 and 2022 it is observed that the tournament should have happened 23 times, so why did my data only indicate 22 tournaments?<br>
>I had to validate the data obtained which eventually explained the reason for this omission, the year missing was 1942-1946 which was due to world war that happened during that period.
>The data shows that several teams had hosted the world cup twice but never happened multiple times with Bazil, Germany, Mexico, France and Italy the only nations to have done it twice.<br>There is no doubt Brazil has been the most successful team in the WC followed by Germany surprisingly Germany also comes first in the runners-up categories with 4 silver medal, Argentina and Netherland closely followed with 3.<br> It is also important to understand almost all Gold medalist have also been runners-up except for teams like Spain, Uruguay and England.
### HOST NATIONS PERFORMANCE<br>
> Being the host nation doesn't guarantee anything, infact the last time a host country won the WC was far back as the late 90's, the last team being the french team of 98.<br>There are only 6 teams who hosted the WC and also emerged victorious; the teams were Uruguay, Italy, England, Germany, Argentina and then France.<br><br>
This result was obtained writing **"DAX"** expressions in POWERBI.<br><br>
```HostCountryWinners =``` <br> ```VAR HostCountriesWithWins = SUMMARIZE(FILTER(world_cups,world_cups[Host Country] = world_cups[Winner])```<br>```RETURN```<br>
```CONCATENATEX(HostCountriesWithWins,world_cups[Host Country], ",")```<br><br>![Capture1](https://github.com/Kaybhee/HISTORY_OF_THE_FIFAWC/assets/106836064/9b5c67c2-ae49-4a43-8540-736471293700)


### FIFA WORLD CUP 2022<br>
> The FIFA WC Was hosted by Qatar although they are not regarded as a powerhouse in any sports competition they produced one of the best WC tournament in History, the dramas, goals scored and the mouth watering Finale.<br>This analysis was carried out strictly for teams which qualified for the 2022 FIFA WC, Brazil were ranked #1 while Ghana were the Least ranked team #50.Portugal went into the tournament as a team who has the most capped individuals, the experience wasn't enough to surmount their opposition.<br><br>
![fifa](https://github.com/Kaybhee/HISTORY_OF_THE_FIFAWC/assets/106836064/3c425b47-d103-4f48-ae51-6a1c313b42fb)<br>
> The Ghanian team went into the competition as the youngest squad with an average age of 25 years and Iran has the oldest squad with 29 years.<br>
### DOMINANCE OF ARGENTINA IN TOURNAMENTS<br>
> Argentina were WC 2022 victors, so i feel it's quite relevant to take a deep dive into Argentina's dominance internationally.<br><br>  ![Arg](https://github.com/Kaybhee/HISTORY_OF_THE_FIFAWC/assets/106836064/e9921c7e-44cd-4a00-9021-3cfe108d32d2)<br><br>
The data visualized were performances of the teams and players enroute the FIFA 2022 WC, No surprises the Messi and DiMaria are only the players in the squad to have WC goals the rest of the team are having their first WC apperance.This obtained by performing some data cleaning, transformation and manipulation of the data in-order to obtain these insights. 








