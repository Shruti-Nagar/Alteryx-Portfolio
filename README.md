# Alteryx-Portfolio

## 1. [User-Driven Decision Paths in Workflow Automation](https://medium.com/@shrutingr001/alteryx-series-part-i-analytic-apps-ca79d4e30400)
![Conditional Routing](https://github.com/Shruti-Nagar/pictures/blob/main/Conditional%20Routing.PNG)
### [Workflow](https://github.com/Shruti-Nagar/Alteryx-Portfolio/blob/main/conditional%20routing.yxwz)

### Project Summary:
This project highlights the power of interactive, user-controlled automation within Alteryx. It utilizes a flexible and dynamic workflow to analyze airline performance data, allowing users to choose their own path of analysis—either by Airport or Airline—through interface tools.

### Goal:
To enable dynamic and customizable data exploration based on user selections, without modifying the core workflow logic.

### Key Workflow Highlights:
#### Interface Tools Integration:
Used List Box, Radio Button, and Action tools to create a user-friendly interface for choosing between different decision paths (by Airport or Airline).
#### Conditional Workflow Execution:
Implemented Enable/Disable Container logic to conditionally run different parts of the workflow based on user inputs.
#### Customizable Analysis Paths:
Airport Path: Filters by selected airport codes and shows the top 10 airports based on domestic flight volume.
Airline Path: Filters by selected airline(s) and displays the first 10 records in ascending date order.
#### Data Summarization & Filtering:
Applied Summarize and Sample tools to show only the most relevant records per user selection.

### Tools & Techniques Used:
- Interface tools for user interaction
- Conditional logic containers
- Dynamic filtering with action updates
- Data sorting and summarization

### Outcome:
Created a seamless, interactive Alteryx workflow where end users can drive the direction of analysis with minimal technical knowledge. This approach significantly enhances flexibility and user engagement in data analysis processes.

***

## 2. [Insurance Claims Using Alteryx Workflow](https://github.com/Shruti-Nagar/Alteryx-Portfolio/blob/main/Parsing%20Insurance%20Claims.yxmd)
### Project Summary:
This project demonstrates how to parse and transform complex PDF-converted insurance data using Alteryx Designer. The input consists of a claims experience record from a group health insurance policy across three underwriting years. Each page of the original PDF is represented as a single row of unstructured data.

### Goal:
To extract and summarize claim amounts based on Accident Month while aligning them with the Inception Date of the insurance policy.
![Alteryx Workflow](https://github.com/Shruti-Nagar/pictures/blob/main/Insurance%20Claims.PNG)
### [Workflow](https://github.com/Shruti-Nagar/Alteryx-Portfolio/blob/main/Parsing%20Insurance%20Claims.yxmd)

### Key Workflow Highlights:
#### Data Preprocessing:
Cleaned and normalized unstructured PDF data by replacing special characters and handling null or empty fields.
#### Parsing Logic:
Utilized conditional logic and filters to isolate key fields like "Inception Date" and "Accident Month". Applied string manipulation to derive month-level data.
#### Data Transformation:
Transformed values into numeric formats, parsed date fields, and created structured outputs from originally messy PDF data.
#### Aggregation & Summarization:
Grouped data by Accident Month and summarized total amounts, further sorting and aligning them with policy inception timelines.

### Tools & Techniques Used:
- Multi-row formula and conditional logic
- String parsing and field cleansing
- Date formatting and conversion
- Aggregation using Summarize tool
- Data sorting and output preparation

### Outcome:
Successfully transformed unstructured PDF-based claim data into a clean, analyzable format. The final output allows stakeholders to track monthly accident claims and understand trends based on policy inception.

***
