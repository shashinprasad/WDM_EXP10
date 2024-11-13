### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">
Sentiment analysis is the process of using computational techniques to determine the sentiment expressed in text data, such as positive, negative, or neutral. It helps businesses understand customer opinions and make data-driven decisions based on public sentiment.

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![326148171-563e2378-9c07-4478-aab2-f9ba8bb61917](https://github.com/user-attachments/assets/e5116a7d-4f2b-49c3-9c6a-86b33de51842)
![326148180-70b5c021-0de6-4dbe-8503-d545e5072c57](https://github.com/user-attachments/assets/d29eacb1-da3d-4543-a7b6-7190edb4bfde)
![326148192-1344c1a2-e0c1-442f-871a-6a63cba73ee2](https://github.com/user-attachments/assets/13075dcf-8c1b-48a1-8126-cd23064ad3fe)

### Result:
Thus, sentimental analysis for twitter data using Rapidminer is done successfully.
