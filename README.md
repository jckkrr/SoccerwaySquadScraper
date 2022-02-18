# SoccerwaySquadScraper
### A script to scrape player line-ups and additional basic information (such as minutes played) for matches listed on the Soccerway website. 


The website <a href="https://int.soccerway.com/" target="_blank">soccerway.com</a> sits on top of an almost endless database of football matches from all points of the globe. As someone who reports on and investigates football, and also a football fan, it's one of my go-to sources for information.

This is one of many scripts I have written over to collect information from the site, which then makes the data infinitely more accessible for carrying out data analytics.

This script focusses on getting the basic player line-ups from a match: the home team, the away team and their substitutes. It includes other basic and important data such as the minutes played and whether the player was on the home or away team. 

An exhaustive assmebler of data from a match it is not, but as a tool for seeing who played when, it proved incredibly helpful as I investigated the recruitment of Brazilians for the national side of Timor-Leste in mid 2010s, <a href="https://www.nytimes.com/2015/10/02/sports/soccer/how-did-east-timor-soccer-improve-so-much-brazilians.html" target="_blank">a story I broke for the New York Times</a>. 

![image](https://user-images.githubusercontent.com/69304112/154632941-3e49af72-95c8-4417-8877-6c85d96f9c68.png)

In this example, the script is set up to scrape games from the World Cup 2018 qualfication campaign in which Timor used Brazilian players.

Once collated and analysed,  <a href="https://plotly.com/~constituentanalytics/77/" target="_blank">I produced the following Sankey diagram using Plotly</a>.

 <div>
      <a href="https://plotly.com/~constituentanalytics/77/" target="_blank" title="TimorSankey660x500" style="display: block; text-align: center;">
       <img src="https://plotly.com/~constituentanalytics/77.png" alt="TimorSankey660x500" style="max-width: 100%;width: 660px;"  width="660" onerror="this.onerror=null;this.src='https://plotly.com/404.png';" />
  </a>
    <script data-plotly="constituentanalytics:77" src="https://plotly.com/embed.js" async></script>  
 </div>
