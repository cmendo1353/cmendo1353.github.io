--- 
layout: page 
title: Narrative 
subtitle: null 
--- 

### Analysis 


<details>
  <summary><b>Question 1:  What are the happiest and unhappiest countries and regions in the world? </b></summary>

To start off our narrative, we first thought of finding out what the happiest and unhappiest countries/regions are in the world from the data. The dataset includes responses from 153 countries and tracks different numeric indexes across them, most notably the Cantril Ladder (Happiness) Score. Therefore, as a baseline to allow for further exploration into other patterns/trends of happiness, we present a global choropleth map that displays the Cantril Ladder score (scale of 1-10) on a green gold color gradient from 2.567 (the minimum average recorded) to 7.809 (the maximum average recorded). A darker green indicates a higher average ladder score for the country, while a yellow gold color indicates a lower average ladder score.

<iframe src="https://public.tableau.com/views/Book2_17536544021750/Sheet2?:showVizHome=no&:embed=true" width="100%" height="650" frameborder="0" allowfullscreen> </iframe>

# <div class='tableauPlaceholder' id='viz1785123122085' style='position: relative'><noscript><a href='#'><img alt='Sheet 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;[...]'

# <script type='text/javascript'>
    # var divElement = document.getElementById('viz1785123122085');
    # var vizElement = divElement.getElementsByTagName('object')[0];
    # vizElement.style.width='100%';
    # vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
# </script>

<br>

Figure 1.1: Choropleth map of Average Cantril Ladder Scores across 153 Countries

<br>

On the map, in addition to the color scale, we can hover the cursor above each country to get their exact average score. While this map is valuable for seeing overall larger trends, we can also use bar graphs to show the average ladder score by region, as well as the top 15 and bottom 15 (roughly top and bottom 10%) of countries in terms of average ladder score.

<div class='tableauPlaceholder' id='viz1785207834984' style='position: relative'><noscript><a href='#'><img alt='Average Ladder Score by Region ' src='https:&#47;&#47;public.tableau.com&#47;static[...]'

<script type='text/javascript'>
    var divElement = document.getElementById('viz1785207834984');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class='tableauPlaceholder' id='viz1785207985157' style='position: relative'><noscript><a href='#'><img alt='Top 15 Countries by Average Cantril Ladder Score ' src='https:&#47;&#47;public.tabl[...]'

<script type='text/javascript'>var divElement = document.getElementById('viz1785207985157');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class='tableauPlaceholder' id='viz1785208044443' style='position: relative'><noscript><a href='#'><img alt='Bottom 15 Countries by Average Cantril Ladder Score ' src='https:&#47;&#47;public.t[...]/'
<script type='text/javascript'>
    var divElement = document.getElementById('viz1785208044443');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
<br>
  
Figures 1.2, 1.3, and 1.4: Bar Graphs showing the Average Ladder Score by Region, the Top 15 and Bottom 15 Countries by Average Ladder Score Respectively.

<br>

Overall, these bar plots are very telling. Firstly, the two regions with by far the highest average ladder score are Western Europe and North America/Australia and New Zealand. This lines up with how the top 15 countries are dominated by countries in those regions. The bottom 15 countries also reveal a striking pattern: it is predominantly made up of Sub Saharan African countries, with them taking up 11 of the 15 spots. 2 South Asian countries appear as well, and the region itself also has the second lowest average ladder score by region.

Overall, this opens the doors for many questions. In figure 3, all of the Nordic countries appear in the top 7, which as discussed in Martela’s The Nordic Exceptionalism: What Explains Why the Nordic Countries Are Constantly Among the Happiest in the World, appears due to “well-functioning democracy, generous and effective social welfare benefits, low levels of crime and corruption, and satisfied citizens who feel free and trust each other and governmental institutions” (Martela et al. 2020, 139). This lines up with how the dataset utilizes explanatory variables, like perceptions of corruption and logged GDP per capita as mentioned earlier. While we can use the data to explore how these variables correlate to happiness on average, it also begs the question if they are an all telling way to measure happiness, and if the data set leaves out any other potential explanatory variables of happiness, which are questions that we will delve into later.

</details>


<details>
  <summary><b>Question 2: What commonalities do the happiest and unhappiest countries share in their respective groups? </b></summary>
 

</details>

<details>
  <summary><b>Question 3: Which of the explanatory factors (GDP, social support, life expectancy, freedom, generosity, and perception of corruption) tend to explain a country's happiness the most? </b></summary>
 

</details>

<details>
  <summary><b>Question 4: Are there any countries that are outliers (such as being very happy or unhappy despite factors that would usually suggest otherwise)? If so, what might be some factors that explain this?</b></summary>
 

</details>

<details>
  <summary><b>Question 5: What does the report mean by the term happiness, and if the specific query changed to one related to meaning or purpose, would the answers differ? </b></summary>
 
  After identifying the countries and regions with the highest and lowest scores, as well as the factors that appear to explain those scores, it is important to consider what the dataset actually [...]

This distinction matters because evaluating life positively is not exactly the same as believing that life has meaning or purpose. Research has found that income and material prosperity share a st[...]

The answers would likely differ if respondents were asked whether their lives had meaning or purpose. Someone facing financial stress or difficult living conditions might give their current life a[...]

Changing the wording could also affect comparisons between countries because cultures do not always define a good life in the same way. Some societies may emphasize independence and personal achie[...]

Ultimately, the World Happiness Report should be understood as measuring one important dimension of well-being instead of every aspect of a good life. Its rankings demonstrate how positively peopl[...]

</details>

<details>
  <summary><b>Question 6: What is left out of the dataset that can potentially explain happiness/wellbeing? </b></summary>
 

</details>
