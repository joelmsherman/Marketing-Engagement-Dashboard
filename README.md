# Marketing Engagements Dashboard
![image]()

## Background
Brandship Inc is a print and digital media marketing firm with global reach.  The company's outreach team is responsible for generating and converting contacts into leads.  The team does this through a variety of engagement activities, and tracks a number of different data points in this effort.  Unfortunately, the data hasn't been accessible to management, making it difficult to do strategic planning and program evaluation.   

## Project Objectives
This project integrates data from Brandship's CMS and Marketing databases, to provide key metrics and insights related to the company's global marketing engagement activities. The solution allows managers to view total activities, durations and contacts made by year and across locations. Brandship managers can track contact targets, and view statistics by staff member, engagement topic, level and type of engagement.  Brandship outreach staff can plan upcoming engagements based on a number of attributes, such as revenue growth potential, online engagement and other metrics to have the greatest impact.

## Report
A link to the live report is available [here](https://app.powerbi.com/view?r=eyJrIjoiNGUzMzY4YWYtZTViNC00Y2YzLWI5YTEtODRkYmU3YTExM2Q2IiwidCI6IjEwMmY4MzcyLTBlMWUtNDFhMy04ZWU4LTZhOTQ5NzAyZjcxNCJ9).

## Administration & Governance

### Workspace
My Workspace

### Distribution
Publish to web

### Sensitivity Label
Public

### Permissions
Public

## Repository Organization
The repository is organized into the following folders:

### 1. Data Pipeline
Storage of all SQL scripts governing the ETL process from source system to warehouse.

### 2. Marketing Engagements.Dataset
A collection of files and folders that represent a Power BI dataset. It contains some of the most important files you're likely to work on, like model.bim. To learn more about the files and subfolders and files in here, see [Project Dataset folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-dataset).

### 3. Marketing Engagements.Report
A collection of files and folders that represent a Power BI report. To learn more about the files and subfolders and files in here, see [Project report folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-report).

### 4. .gitignore
Specifies intentionally untracked files Git should ignore. Dataset and report subfolders each have default git ignored files specified in .gitIgnore:

* Dataset
    - .pbi\localSettings.json
    - .pbi\cache.abf

* Report
    - .pbi\localSettings.json

In addition to these, all client project docs (project plans, sketches, wireframes, etc), data and ux artifacts are ignored.

### 5. Marketing Engagements.pbip
The PBIP file contains a pointer to a report folder, opening a PBIP opens the targeted report and model for authoring. For more information, refer to the [pbip schema document](https://github.com/microsoft/powerbi-desktop-samples/blob/main/item-schemas/common/pbip.md).