# The Office - Visualizing Character Interaction

This program scrapes webpages from [officequotes.net](https://officequotes.net) and stores the script in text files corresponding to each episode in The Office.

The extracted scripts are used to plot a "Character Interaction" heat map, calculated by measuring how many times each character has said another character's name in the show. The heat map generated is fairly symmetric, implying that the number of times A says B's name, is proportional to the number times that B says A's name. This is what is expected should the heat map be truly representative of character interaction.
The plots are shown below on linear and logarithmic color scales.
<p align="CENTER">
  <img src="/plots/linScale.png" width=430>
  <img src="/plots/logScale.png" width=430>
</p>

Word clouds for each major character are also plotted. An example is shown below (word cloud for Michael Scott).
<p align="CENTER">
  <img src="/plots/wordcloud_michael.png" width=700>
</p>
