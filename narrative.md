--- 
layout: page 
title: Narrative 
subtitle: null 
--- 

### Analysis 


<details>
  <summary><b>Question 1: </b></summary>

To start off our narrative, we first thought of finding out what the happiest and unhappiest countries/regions are in the world from the data. The dataset includes responses from 153 countries and tracks different numeric indexes across them, most notably the Cantril Ladder (Happiness) Score. Therefore, as a baseline to allow for further exploration into other patterns/trends of happiness, we present a global choropleth map that displays the Cantril Ladder score (scale of 1-10) on a green gold color gradient from 2.567 (the minimum average recorded) to 7.809 (the maximum average recorded). A darker green indicates a higher average ladder score for the country, while a yellow gold color indicates a lower average ladder score.

<div class='tableauPlaceholder' id='viz1785123122085' style='position: relative'><noscript><a href='#'><img alt='Sheet 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17849471301450&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book2_17849471301450&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17849471301450&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1785123122085');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';
    vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
</script>

Figure 1: Choropleth map of Average Cantril Ladder Scores across 153 Countries

On the map, in addition to the color scale, we can hover the cursor above each country to get their exact average score. While this map is valuable for seeing overall larger trends, we can also use bar graphs to show the average ladder score by region, as well as the top 15 and bottom 15 (roughly top and bottom 10%) of countries in terms of average ladder score.

<div class='tableauPlaceholder' id='viz1785207834984' style='position: relative'><noscript><a href='#'><img alt='Average Ladder Score by Region ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AverageLadderScorebyRegion&#47;Sheet5&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AverageLadderScorebyRegion&#47;Sheet5' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AverageLadderScorebyRegion&#47;Sheet5&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                

<script type='text/javascript'>
    var divElement = document.getElementById('viz1785207834984');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class='tableauPlaceholder' id='viz1785207985157' style='position: relative'><noscript><a href='#'><img alt='Top 15 Countries by Average Cantril Ladder Score ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top15CountriesbyAvgCantrilLadderScore&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Top15CountriesbyAvgCantrilLadderScore&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top15CountriesbyAvgCantrilLadderScore&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

<script type='text/javascript'>var divElement = document.getElementById('viz1785207985157');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class='tableauPlaceholder' id='viz1785208044443' style='position: relative'><noscript><a href='#'><img alt='Bottom 15 Countries by Average Cantril Ladder Score ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Bottom15CountriesbyAvgCantrilLadderScore&#47;Sheet4&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Bottom15CountriesbyAvgCantrilLadderScore&#47;Sheet4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Bottom15CountriesbyAvgCantrilLadderScore&#47;Sheet4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1785208044443');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Figures 2, 3, and 4: Bar Graphs showing the Average Ladder Score by Region, the Top 15 and Bottom 15 Countries by Average Ladder Score Respectively.

Overall, these bar plots are very telling. Firstly, the two regions with by far the highest average ladder score are Western Europe and North America/Australia and New Zealand. This lines up with how the top 15 countries are dominated by countries in those regions. The bottom 15 countries also reveal a striking pattern: it is predominantly made up of Sub Saharan African countries, with them taking up 11 of the 15 spots. 2 South Asian countries appear as well, and the region itself also has the second lowest average ladder score by region.

Additionally, this opens the doors for many questions. In figure 3, all of the Nordic countries appear in the top 7, which as discussed in Martela’s The Nordic Exceptionalism: What Explains Why the Nordic Countries Are Constantly Among the Happiest in the World, appears due to “well-functioning democracy, generous and effective social welfare benefits, low levels of crime and corruption, and satisfied citizens who feel free and trust each other and governmental institutions” (Martela et al. 2020, 139). This lines up with how the dataset utilizes explanatory variables, like perceptions of corruption and logged GDP per capita as mentioned earlier. While we can use the data to explore how these variables correlate to happiness on average, it also begs the question if they are an all telling way to measure happiness, and if the data set leaves out any other potential explanatory variables of happiness, which are questions that we will delve into later.

</details>






<details>
  <summary><b>Question 5: </b></summary>
 
  After identifying the countries and regions with the highest and lowest scores, as well as the factors that appear to explain those scores, it is important to consider what the dataset actually means when it comes to the term “happiness.” Despite its name, the World Happiness Report does not directly ask respondents how frequently they feel joyful or emotionally positive. Instead, its main score comes from the Cantril Ladder, which asks people to imagine a ladder ranging from zero, which represents the worst possible for them, to ten, which represents the best possible life. The respondents then select the step that best represents their current life. Therefore, the dataset primarily measures life evaluation, or how people judge the overall quality of their lives, rather than a complete measure of happiness. 

This distinction matters because evaluating life positively is not exactly the same as believing that life has meaning or purpose. Research has found that income and material prosperity share a stronger connection to how people evaluate their lives, while positive feelings are more closely related to psychological and social conditions, such as autonomy and having people to depend on (Diener et al. 52-53). Kahneman and Deaton similarly found that income had a stronger relationship with life evaluation than with daily emotional well-being, which was more affected by experiences such as loneliness or poor health (Kahneman and Deaton 16489-90). This means that the World Happiness Report captures an important part of well-being, but the term “happiness” may make its measurement appear broader than it actually is. 

The answers would likely differ if respondents were asked whether their lives had meaning or purpose. Someone facing financial stress or difficult living conditions might give their current life a low ladder score while still finding deep meaning through family, religion, community involvement, or personal responsibility. The opposite could also occur: a person may have financial security and personal freedom while still feeling that life lacks direction. Oishi and Westgate argue that happiness and meaning represent different versions of a good life. Happiness emphasizes comfort and positive experiences, while meaning is connected to purpose and contributing to something beyond oneself. (Oishi and Westgate 790-92). 

Changing the wording could also affect comparisons between countries because cultures do not always define a good life in the same way. Some societies may emphasize independence and personal achievement, while others may place a greater value on family obligations or belonging within your community. Culture can influence both how people experience well-being and how they interpret international survey questions (Exton, Smith, Vandendriessche 5). Therefore, a question focused on meaning or purpose could produce different responses and possibly a different ordering of countries. 

Ultimately, the World Happiness Report should be understood as measuring one important dimension of well-being instead of every aspect of a good life. Its rankings demonstrate how positively people evaluate their current circumstances, but they do not directly show whether people experience the greatest sense of purpose or the most meaningful lives. A purpose-based question would likely produce different results because it would direct attention towards more personal factors, such as family, identity, religion, responsibility, and long-term goals. This reveals that conclusions about global happiness depend partly on how researchers define happiness and which dimensions of well-being their questions make visible. 

</details>
