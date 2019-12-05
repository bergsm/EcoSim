This project represents an Ecosystem Simulation.

It specifically focuses on the population of a generic species of deer and how the population of that deer interacts with available food resources.

There are 5 interacting variables in this simulation. The population of the deer, the availability of food for the deer (represented as grain height) and the amount of deer waste, the temperature, and the amount of precipitation. More deer leads to more grain eaten, which leads to more deer waste, which can lead to better grain growth. Grain growth is also affected by precipitation and temperature to represent growth cycles.

From a technical perspective, the calculations are made in 3 parallel sections. The population of the deer, the height of the grain, and the impact of deer waste are calculated in parallel to ensure impacts and effects of interacting variables are calculated accurately. Each parallel section includes barriers to ensure all sections move in concert with one another.

The program outputs the data from the collection period into a .csv file for future processing or graphing.

![Sim through 2025](https://github.com/bergsm/EcoSim/blob/master/2025.png)
![Sim through 2100](https://github.com/bergsm/EcoSim/blob/master/2100.png)
