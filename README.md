# Grap Editor in Vue.js

The goal of this repository is to develop a graph editor from scratch using Vue.js

The graph will be used to set the evolution of a budget over time
  * The X axis represents the time (1 point correspond to 1 month).
  * The Y axis represents the percentage of the bugdet allowed over the total budget.
  
In order to improve user experience, dotted lines are used to separate the years (if > 12 months)
The Y axis has a specific precision and the values "snap" to this precision.


Ideas for the future:
  * Proposing predefined curves that the user can select (linear pos/neg, exp, sqr...)
  * Possibility to display the percentage of the selected month to set it directly with the keyboard
  * Zoom to a specific year
