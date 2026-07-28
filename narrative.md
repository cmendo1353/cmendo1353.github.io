--- 
layout: page 
title: Narrative 
subtitle: null 
--- 

### Analysis 


<details>
  <summary><b>Question 1: What are the happiest and unhappiest countries and regions in the world?</b></summary>

<p>To start off our narrative, we first thought of finding out what the happiest and unhappiest countries and regions are in the world from the data. The dataset includes responses from 153 countries and tracks Cantril Ladder scores, which reflect how people evaluate their lives overall.</p>

<div class='tableauPlaceholder' id='viz1785219215367' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Average Cantril Ladder/Happiness Score by Country (World Happiness Report 2020)' src='https://public.tableau.com/...'>
    </a>
  </noscript>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1785219215367');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<p>Figure 1.1: Choropleth map of Average Cantril Ladder Scores across 153 Countries</p>

<p>On the map, in addition to the color scale, we can hover the cursor above each country to get their exact average score. While this map is valuable for seeing overall larger trends, we can also use bar charts to compare regions and the highest- and lowest-scoring countries more directly.</p>

<div class='tableauPlaceholder' id='viz1785219285875' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Average Ladder Score by Region' src='https://public.tableau.com/...'>
    </a>
  </noscript>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1785219285875');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<p>Figure 1.2: Bar Graph showing the Average Ladder Score by Region</p>

<div class='tableauPlaceholder' id='viz1785219326374' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Top 15 Countries by Average Cantril Ladder Score' src='https://public.tableau.com/...'>
    </a>
  </noscript>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1785219326374');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<p>Figure 1.3: Bar Graph showing the Top 15 Countries by Average Cantril Ladder Score</p>

<div class='tableauPlaceholder' id='viz1785219363485' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Bottom 15 Countries by Average Cantril Ladder Score' src='https://public.tableau.com/...'>
    </a>
  </noscript>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1785219363485');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<p>Figure 1.4: Bar Graph showing the Bottom 15 Countries by Average Ladder Score.</p>

<p>Overall, these bar plots are very telling. Firstly, the two regions with by far the highest average ladder score are Western Europe and North America/Australia and New Zealand. This lines up with how the top 15 countries are dominated by countries in those regions. The bottom 15 countries also reveal a striking pattern: it is predominantly made up of Sub-Saharan African countries, with them taking up 11 of the 15 spots. Two South Asian countries appear as well, and the region itself also has the second lowest average ladder score by region.</p>

<p>Overall, this opens the doors for many questions. In figure 3, all of the Nordic countries appear in the top 7, which as discussed in Martela’s <i>The Nordic Exceptionalism: What Explains Why the Nordic Countries Are Constantly Among the Happiest in the World?</i> appears due to “well-functioning democracy, generous and effective social welfare benefits, low levels of crime and corruption, and satisfied citizens who feel free and trust each other and governmental institutions” (Martela et al. 2020, 139).</p>

<p>This lines up with how the dataset utilizes explanatory variables, like perceptions of corruption and logged GDP per capita as mentioned earlier. While we can use the data to explore how these variables correlate to happiness on average, it also raises the question of whether they are enough to measure happiness on their own, and whether the dataset leaves out other important explanatory variables. We will explore those questions later.</p>
</details>

<br>

<details>
  <summary><b>Question 2: What commonalities do the happiest and unhappiest countries share in their respective groups?</b></summary>
</details>

<br>

<details>
  <summary><b>Question 3: Which of the explanatory factors (GDP, social support, life expectancy, freedom, generosity, and perception of corruption) tend to explain a country's happiness the most?</b></summary>
</details>

<br>

<details>
  <summary><b>Question 4: Are there any countries that are outliers (such as being very happy or unhappy despite factors that would usually suggest otherwise)? If so, what might be some factors that explain this?</b></summary>
</details>

<br>

<details>
  <summary><b>Question 5: What does the report mean by the term happiness, and if the specific query changed to one related to meaning or purpose, would the answers differ?</b></summary>

  <p>After identifying the countries and regions with the highest and lowest scores, as well as the factors that appear to explain those scores, it is important to consider what the dataset actually measures.</p>

  <p>This distinction matters because evaluating life positively is not exactly the same as believing that life has meaning or purpose. Research has found that income and material prosperity share a strong relationship with life evaluation, while other dimensions of well-being can behave differently.</p>

  <p>The answers would likely differ if respondents were asked whether their lives had meaning or purpose. Someone facing financial stress or difficult living conditions might give their current life a lower evaluation, but still feel that their life is meaningful in some way.</p>

  <p>Changing the wording could also affect comparisons between countries because cultures do not always define a good life in the same way. Some societies may emphasize independence and personal achievement, while others may value family, duty, or community more strongly.</p>

  <p>Ultimately, the World Happiness Report should be understood as measuring one important dimension of well-being instead of every aspect of a good life. Its rankings demonstrate how positively people evaluate their lives, not a complete definition of happiness itself.</p>
</details>

<br>

<details>
  <summary><b>Question 6: What is left out of the dataset that can potentially explain happiness/wellbeing?</b></summary>
</details>
