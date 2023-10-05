# Google Sheets Data Transformation Automation

This project focuses on automating specific data transformation processes within Google Sheets. Utilizing Google Apps Script, the project enhances the sorting, transformation, and preparation of data for more effective analysis and visualization.

## Sources

### Google Apps Script: Spreadsheet Service

Provided by: Google

Web development: Google

https://developers.google.com/apps-script/reference/spreadsheet/

## Project Details

The automation tool aims to restructure and sort a given dataset. Some of the key functionalities include:

### Adding and Sorting a 'DATE' Column
This feature checks for an existing 'DATE' column in the "Raw Data" sheet and deletes it. A new 'DATE' column is then added, and the data gets sorted based on specified parameters.

```javascript
function sortRawData() { ... }
```

### Data Grouping and Error Highlighting
Groups data based on certain criteria and highlights errors (like missing usernames, invalid dates, and absent study fields).

```javascript
function SortGroup() { ... }
```

![Data Grouping Screenshot](https://github.com/YourUsername/GoogleSheets_DataTransformation/blob/main/images/data_grouping.png)

### Data Transformation
Processes the sorted data to provide total time computations for each group.

```javascript
function transformData() { ... }
```

![Data Transformation Screenshot](https://github.com/YourUsername/GoogleSheets_DataTransformation/blob/main/images/data_transformation.png)

### Data Preparation for Analysis
Creates a 'Prep Data' sheet with refined information, including total hours, check-in ID, and check-out ID.

```javascript
function preparePrepData() { ... }
```

![Data Preparation Screenshot](https://github.com/YourUsername/GoogleSheets_DataTransformation/blob/main/images/data_preparation.png)

### Creation of Monthly Data Sheets
Based on the 'Study' column in the 'Prep Data' sheet, separate monthly sheets are generated.

```javascript
function createMonthlySheets() { ... }
```

![Monthly Sheets Screenshot](https://github.com/YourUsername/GoogleSheets_DataTransformation/blob/main/images/monthly_sheets.png)

## How to Use

1. Open your Google Sheets document.
2. Click on "Extensions" and then "Apps Script."
3. Paste the provided script in the script editor.
4. Save and then reload your Google Sheet.
5. You'll find a new menu item titled "BIG RED BUTTON" with an option "CLICK HERE TO EXECUTE". Clicking on this option will execute all the automation functions.

## Future Plans

- Add more error-checking capabilities.
- Provide an undo functionality.
- Enhance performance for large datasets.

## Contributions
Contributions to enhance this script are welcome. Kindly open an issue or pull request on the [GitHub repo](https://github.com/YourUsername/GoogleSheets_DataTransformation).


## Authors

- Veronica Broadway (https://bwayvs.github.io/Professional_Portfolio/)

## 🚀 About Me
I'm Veronica, a results-driven Data Analyst with expertise in SAP and process improvement. With a background in translating complex requirements into actionable insights, I leverage SQL, data visualization tools, and Agile methodologies to optimize supply chains and drive business decisions. My passion lies in turning data into meaningful business strategies, ensuring organizational alignment, and fostering cross-functional collaboration.

## 🔗 LinkedIn Profile
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/veronicabroadway/)



