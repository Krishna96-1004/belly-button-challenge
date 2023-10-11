# belly-button-challenge

This project consists of a single JavaScript file that contains several functions to draw interactive charts and retrieve data from a JSON file. Heres a brief overview of the functions:

draw(id): This function reads data from a JSON file and uses it to draw a bar chart and a bubble chart. The id parameter specifies the ID of the sample to be used for the charts.

retrieveData(id): This function reads data from the same JSON file and retrives demographic informatoin for a specific sample. The id parameter specifies the ID of the sample.

optionChanged(id): This function is called when the selected option in the dropdown menu changes. It calls the draw and retrieveData functions with the new id.

init(): This function is called when te page loads. It populates the dropdown menu with the sample IDs.

The JSON file used in this project is hosted on an external server and can be accessed at this URL: [https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json]
