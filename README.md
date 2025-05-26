# Alteryx-Portfolio

## 1. [User-Driven Decision Paths in Workflow Automation](https://medium.com/@shrutingr001/alteryx-series-part-i-analytic-apps-ca79d4e30400)
![Conditional Routing](https://github.com/Shruti-Nagar/pictures/blob/main/Conditional%20Routing.PNG)
### This case study explores how dynamic user inputs can drive the execution of distinct workflow paths within an automated data process. By allowing users to select their preferred analysis route—such as filtering data by origin airport or airline—the workflow intelligently adapts in real time, enabling or disabling specific processing streams based on conditional logic. The result is a flexible, user-centric workflow that enhances efficiency, reduces unnecessary computation, and improves the overall user experience in data-driven decision-making environments.
[Alteryx File](https://github.com/Shruti-Nagar/Alteryx-Portfolio/blob/main/conditional%20routing.yxwz)

## 2. [Insurance Claims Using Alteryx Workflow](https://github.com/Shruti-Nagar/Alteryx-Portfolio/blob/main/Parsing%20Insurance%20Claims.yxmd)
### Project Summary:
This project demonstrates how to parse and transform complex PDF-converted insurance data using Alteryx Designer. The input consists of a claims experience record from a group health insurance policy across three underwriting years. Each page of the original PDF is represented as a single row of unstructured data.

### Goal:
To extract and summarize claim amounts based on Accident Month while aligning them with the Inception Date of the insurance policy.

![Alteryx Workflow](https://github.com/Shruti-Nagar/pictures/blob/main/Insurance%20Claims.PNG)

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

## 3. 
###
