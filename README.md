# Improving Cloud Security Posture With Azure Sentinel: A Real Time Threat Detection Solution

## KQL Queries
This folder contains a complete list of KQL (Kusto Query Language) queries used for various security use cases, including:

* Blocked Malicious IP Addresses
* Blocking User Privileges
* Infected Virtual Machine Logs
* Blocking Non-Legitimate Users
Analysis of Multifactor Authentication (MFA) and Microsoft Entra ID Logs
**Note:** .kql is not a valid file format for sharing KQL queries. Instead, Azure Sentinel queries are typically stored and shared in plain text files. KQL is an Azure-specific language developed by Microsoft for querying data in Azure Data Explorer (Kusto).

## Data Files
This folder includes:

* Power BI Visualizations (PDF Format): A full extract of all Power BI visualizations used in the project.
* Security Log Data Files: A collection of CSV and JSON files used to load security logs into Azure Sentinel.

## PowerShell Scripts
This folder contains:

* Script to Load Data into Azure Log Analytics Workspace: The script is responsible for transferring data into Azure Log Analytics Workspace, which is then pushed into Azure Sentinel. (Adjust the JSON data as needed.)
* CSV to JSON Conversion Script: A script used to convert CSV files into JSON format to ensure compatibility with Microsoft Sentinel.
**Note:**

* JSON (JavaScript Object Notation) is a lightweight data format that uses key-value pairs to represent structured data.
* CSV (Comma-Separated Values) is a text-based format where data is organized in rows and columns, commonly used in spreadsheets.
* Converting CSV to JSON enables easier data ingestion, parsing, and organization within Microsoft Sentinel, allowing for more efficient querying, monitoring, and alerting.

## Project Documentation
This folder includes key project-related documents:

* Project Proposal File
* Project Diagram
* PPTX Presentation: "Improving Cloud Security Posture with Azure Sentinel"
* Final Report Docx
