# Belly Button Biodiversity
````Link to access:
https://tucamdang.github.io/Interactive-Visualisation-and-Dashboard-BellyButton-W15/
````

In this assignment, we build interactive dashboard to explore the Belly Button Biodiversity dataset, refers to the microbes that colonise human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

As index.html and data samples (samples.json) provided, we edit/code the app.js to display the chart - information:
![image](https://user-images.githubusercontent.com/99168697/171572806-9955bce5-0eb9-4bd2-8fc9-af9d49adc51f.png)
![image](https://user-images.githubusercontent.com/99168697/171572851-a9fa51ea-46ea-4444-9e8a-dfe5585b727e.png)

There are three charts which will be presented, one table to demonstrate each key-value: 
1. Now we can apply the D3 library to read in samples.json

2. To generate a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
- Edit ``sample_values`` as the values in bar chart.
- Edit ``otu_ids`` as the labels in bar chart.
- Edit ``otu_labels`` as the hovertext in chart.
![image](https://user-images.githubusercontent.com/99168697/171576121-49499cfe-2dff-4a00-b85f-a1bef54c1396.png)

3. We generate a bubble chart that displays each sample.
- Edit ``otu_ids`` for the x values, ``sample_values`` for the y values.
- Edit ``sample_values`` for the marker size, ``otu_ids`` for the marker colours.
- Edit ``otu_labels`` for the text values.
![image](https://user-images.githubusercontent.com/99168697/171577223-91ce78d8-1595-4f0e-bc8d-f6dfed01ba9e.png)

4. Demonstrate the sample metadata, i.e., an individual's demographic information.

5. In the Bonus section:
By using the provided link, Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.
We can apply example gauge code to account for values ranging from 0 to 9.
![image](https://user-images.githubusercontent.com/99168697/171577762-a8b14914-c5e7-44aa-ac1c-61bca40b42d9.png)

![image](https://user-images.githubusercontent.com/99168697/171571824-d7807443-96e5-4231-a674-2756365cceea.png)
