# The Office - Visualizing Character Interaction

This program scrapes php files from [officequotes.net](officequotes.net) and stores the script in text files corresponding to each episode in The Office.

The extracted scripts are used to plot a "Character Interaction" heat map, calculated by measuring how many times each character has said another character's name in the show. The heat map generated is fairly symmetric, implying that the number of times Character A says Character B's name, is proportional to the number times that Character B says Character A's name. This is what is expected should the heat map be truly representative of character interaction.
The plots are shown below on a linear an logarithmic color scheme.
<p align="CENTER">
  <img src="/plots/linear_scale.png" width=430>
  <img src="/plots/log_scale.png" width=430>
</p>

Word clouds for each major character are also plotted. An example is shown below (word cloud for Michael Scott).
<p align="CENTER">
  <img src="/plots/wordcloud_michael.png" width=700>
</p>
