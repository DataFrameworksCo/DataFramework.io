
# DataFramework.io

A modern, browser-based Business Intelligence (BI) platform for
importing, cleaning, analyzing, querying, visualizing, and exporting
data --- all in one environment.

------------------------------------------------------------------------

## Overview

DataFramework.io is a fully client-side analytics platform built with
HTML, CSS, and JavaScript.

It allows users to:

-   Import datasets (CSV, Excel, JSON, .ddf)
-   View and edit data in spreadsheet format
-   Run SQL queries directly in the browser
-   Clean and transform data
-   Merge datasets
-   Build pivot tables
-   Create interactive charts
-   Build dashboards
-   Export results and projects

No backend required. No database server needed.

------------------------------------------------------------------------

##Downloading DataFramework & Patch Modules

- Open the source code and download the full all-in-one HTML file
- We recommend saving this file in a folder labled "DataFramework"
- Click to open the file in the browser of your choice
- No install needed
- The application can be wrapped into an installer if you wish you to do so (More information on that below)
- We have optional modules that can be installed to your application as a .path.json file
- Patch files must be installed using the patch manager.
- Modules can be requested by email from dataframework@gmail.com
- A list of requestable modules can be found under the MODULES.md documentation

------------------------------------------------------------------------

## Key Features

### Data Import

Supports: - CSV - TSV - Excel (.xlsx, .xls) - JSON - .ddf (DataFramework
project files)

Drag and drop supported.

------------------------------------------------------------------------

### Data View

Spreadsheet-style interface with:

-   Search across columns
-   Column filtering
-   Sorting
-   Inline editing
-   Formula bar (calculated columns)
-   Column statistics panel
-   SQL query panel

------------------------------------------------------------------------

### SQL Engine

Includes:

-   Manual SQL editor
-   Visual Query Builder
-   SQL snippets
-   Query history
-   Save results as new datasets
-   Export SQL results to CSV

Supported clauses: - SELECT - WHERE - GROUP BY - ORDER BY - LIMIT -
Aggregations (SUM, AVG, COUNT, etc.) - JOIN operations - CASE
statements - DISTINCT - LIKE

------------------------------------------------------------------------

### Chart Builder

Create interactive charts using:

-   Bar
-   Line
-   Area
-   Pie
-   Doughnut
-   Scatter
-   Radar
-   Polar
-   Bubble
-   Stacked Bar
-   Mixed charts

Features: - Live preview - Aggregations - Multiple Y axes - Reference
lines - Legend positioning - Style customization - Data labels - Grid
control - Category limits

------------------------------------------------------------------------

### Dashboard

Build dashboards using:

-   Charts
-   KPI cards
-   Text cards

Export dashboard as: - HTML - Excel

------------------------------------------------------------------------

### Merge / Join Datasets

Join multiple datasets using:

-   Inner Join
-   Left Join
-   Right Join
-   Full Outer Join
-   Append / Union

------------------------------------------------------------------------

### Data Cleaner

Transformation tools include:

-   Remove null rows
-   Remove duplicates
-   Trim whitespace
-   Change case (UPPER, lower, Title)
-   Fill nulls (mean, median, zero, custom)
-   Parse numbers
-   Remove / rename columns
-   Find & replace
-   Flag outliers
-   Split column
-   Merge columns
-   Round numbers
-   Delete filtered rows

Operation log included. Undo supported.

------------------------------------------------------------------------

### Pivot Tables

Generate summarized views:

-   Row groupings
-   Column groupings
-   Aggregations
-   Totals
-   Grand totals

------------------------------------------------------------------------

### Project Saving (.ddf)

Save full session state as:

`.ddf` (Data Framework File)

Preserves: - Datasets - Dashboard layout - Charts - Transformations -
SQL history

------------------------------------------------------------------------

## Running the Application

### Open Directly

Simply open the HTML file in a modern browser.

Recommended: - Chrome - Edge - Brave

### Run Locally (Optional)

Using a simple local server:

`npx serve`

or

`python -m http.server`

------------------------------------------------------------------------

## Packaging as Desktop App

This project can be packaged using:

-   Electron
-   Nativefier
-   Tauri

------------------------------------------------------------------------

## Recommended Workflow

1.  Import data\
2.  Clean data\
3.  Validate with Pivot Tables\
4.  Run SQL if needed\
5.  Build charts\
6.  Add to dashboard\
7.  Export or save as .ddf

------------------------------------------------------------------------

## License

Add your preferred license here (MIT recommended for open source).

------------------------------------------------------------------------

DataFramework.io\
Business Intelligence Platform
