# plot.ly-challenge




Belly Button Biodiversity
![image](https://user-images.githubusercontent.com/75258480/118373206-315ab380-b5e8-11eb-993e-4d13ec90627f.png)




In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Step 1: Plotly


Use the D3 library to read in samples.json.


Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.




Use sample_values as the values for the bar chart.


Use otu_ids as the labels for the bar chart.


Use otu_labels as the hovertext for the chart.


![image](https://user-images.githubusercontent.com/75258480/118373217-3f103900-b5e8-11eb-8133-87cc760a5752.png)


Create a bubble chart that displays each sample.



Use otu_ids for the x values.


Use sample_values for the y values.


Use sample_values for the marker size.


Use otu_ids for the marker colors.


Use otu_labels for the text values.


![image](https://user-images.githubusercontent.com/75258480/118373220-49323780-b5e8-11eb-80de-10ae41ab2a25.png)



Display the sample metadata, i.e., an individual's demographic information.


Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/75258480/118373230-52230900-b5e8-11eb-97cb-eb748934d292.png)



Update all of the plots any time that a new sample is selected.

Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:

![image](https://user-images.githubusercontent.com/75258480/118373243-5f3ff800-b5e8-11eb-8716-e13e673638df.png)


Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.


Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.


You will need to modify the example gauge code to account for values ranging from 0 through 9.


Update the chart whenever a new sample is selected.


![image](https://user-images.githubusercontent.com/75258480/118373260-767ee580-b5e8-11eb-9ac3-772feb5c5369.png)


Deployment
Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.

Hints


Use console.log inside of your JavaScript code to see what your data looks like at each step.


Refer to the Plotly.js documentation when building the plots.
