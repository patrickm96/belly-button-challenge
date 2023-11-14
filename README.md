# belly-button-challenge
Module 14 Challenge

Static page hosting service page URL: https://patrickm96.github.io/belly-button-challenge/

The following resources were referenced to complete this challenge:

1. Javascript map array - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
2. ForEach array loop - https://www.w3schools.com/jsref/jsref_foreach.asp
3. Slice and reverse array - https://stackoverflow.com/questions/30610523/reverse-an-array-in-javascript-without-mutating-the-original-array
4. Create bubble chart using Plotly - https://plotly.com/javascript/bubble-charts/
5. Create bar chart using Plotly - Instructor Eli covered this during class.
6. Populate metadata key value pairs using Object.entries() - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries
7. Modify javascript code to be dynamic based on selected sample - ChatGPT
8. Debugging dropdown menu population function - ChatGPT

## Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.


Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
