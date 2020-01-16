# Belly-Button-Diversity
Belly-Button-Biodiversity-Analysis
The goal of this project was to use JavaScript to present interactive visualizations of belly button biodiversity data within a web page. Since the baseline data was provided in JSON format, D3 was used to import and process the data, while Plotly was used to generate the required visualizations.

Questions
What is the demographic information of the individual associated with each specific belly button sample?
What are the top ten Operational Taxonomic Units (OTUs) by concentration in each specific belly button sample?
What are the concentrations of all the Operational Taxonomic Units (OTUs) in each specific belly button sample?
What is the weekly wash frequency of each specific belly button sample?

Tasks
Import the belly button sample data from the JSON file and create a function for web page initialization.
Extract each sample ID number and append it to the HTML dropdown menu container.
Extract and process the demographic information and OTU data for the first sample.
Append demographic information for the first sample to the appropriate HTML container.
Generate a bar chart of the top ten OTUs by concentration in the first sample and connect it to the appropriate HTML container.
Generate a bubble chart of the concentrations of all of the OTUs in the first sample and connect it to the appropriate HTML container.
Generate a gauge chart of the weekly wash frequency of the first sample and connect it to the appropriate HTML container.
Create a function to monitor and extract the currently selected sample ID number from the HTML dropdown menu.
Repeat steps three through seven for the currently selected sample ID number.
