Belly Button Biodiversity Dashboard

Overview

This project focuses on building an interactive dashboard to explore the fascinating Belly Button Biodiversity dataset, which catalogs microbes found in human navels. The dataset reveals the microbial diversity in human belly buttons, with some species being common across the majority of individuals and others appearing far less frequently.

Using tools like Plotly.js and D3.js, we developed a fully interactive web application to visualize and analyze this data in a user-friendly way.

Results

Key Features of the Dashboard
Horizontal Bar Chart
Displays the top 10 OTUs (Operational Taxonomic Units) for each selected individual.
Includes:
Sample Values as the bar lengths.
OTU IDs as the labels.
OTU Labels as hover text for detailed descriptions.
Bubble Chart
Visualizes all OTUs for each sample.
Features:
OTU IDs as x-axis values.
Sample Values as y-axis values.
Marker size proportional to sample values.
Marker color coded by OTU IDs.
Hover text showing OTU labels for added context.
Demographic Information Panel
Displays metadata for each individual, including demographic data.
Dynamically updates based on the selected sample using a loop to parse and display key-value pairs from the dataset.
Dynamic Interactivity
The dashboard responds to user input through a dropdown menu.
Selecting a new sample updates:
Bar chart.
Bubble chart.
Demographic panel.
Technologies Used

Plotly.js: For creating dynamic and interactive visualizations.
D3.js: For reading and handling JSON data from an external URL.
HTML/CSS/JavaScript: To build and style the dashboard.
GitHub Pages: For deployment of the project.
Deployment

The dashboard was successfully deployed using GitHub Pages, providing an accessible and static hosting solution for this interactive web application. Regular commits were made throughout the development process to ensure proper version control.

Insights from the Dataset

Common Microbes
The dashboard highlights the most prevalent OTUs, providing insights into microbial species found in a majority of individuals.
Diversity Across Individuals
The variation in bubble chart patterns showcases the diversity of microbial populations among different samples.
Demographic Correlations
The demographic panel can help uncover potential relationships between metadata (e.g., age, gender) and microbial diversity, offering avenues for further exploration.
This project demonstrated the power of data visualization and interactivity in uncovering biological patterns. The dashboard serves as an engaging tool for exploring the hidden microbial world in our navels!
