# Advanced Excel (advanced-excel)
Advanced Excel is a subject-matter topic encompassing Microsoft Excel's programmatic capabilities for data analysis, formula execution, workbook management, chart generation, and automation. This topic index covers REST APIs, open data schemas, and developer tools for working with Excel workbooks programmatically, including Microsoft Graph Excel API, open-source spreadsheet libraries, and data interchange formats used in business intelligence and automation workflows.

**URL:** [Visit Advanced Excel](https://learn.microsoft.com/en-us/graph/excel-concept-overview)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Business Intelligence, Data Analysis, Data Processing, Excel, Microsoft, Spreadsheets

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Microsoft Graph Excel API
The Microsoft Graph Excel API provides REST access to Excel workbooks stored in OneDrive, SharePoint, or Teams. Supports reading and writing cell values, executing formulas, managing worksheets, creating charts and tables, and running workbook sessions for transactional batch operations on Excel files.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/excel](https://learn.microsoft.com/en-us/graph/api/resources/excel)

#### Tags:

 - Excel, Microsoft, OneDrive, REST API, Spreadsheets

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [OpenAPI](openapi/microsoft-graph-excel-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/microsoft-graph-excel-api-context.jsonld)
- [Vocabulary](vocabulary/advanced-excel-vocabulary.yaml)

## Common Properties

- [Website](https://www.microsoft.com/en-us/microsoft-365/excel)
- [Documentation](https://learn.microsoft.com/en-us/graph/excel-concept-overview)
- [GettingStarted](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [TermsOfService](https://www.microsoft.com/en-us/servicesagreement)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHubOrganization](https://github.com/OfficeDev)

## Features

| Name | Description |
|------|-------------|
| Workbook and Worksheet Management | Create, read, update, and delete Excel workbooks and worksheets via REST API calls. |
| Formula Execution | Execute Excel formulas and retrieve computed values programmatically via the Microsoft Graph API. |
| Range and Cell Operations | Read and write cell values, apply formatting, and manipulate named ranges and tables. |
| Chart Generation | Create and configure charts from worksheet data including column, line, pie, and bar chart types. |
| Table and PivotTable Operations | Create, query, and manipulate Excel tables and pivot tables via API. |
| Session Management | Manage persistent workbook sessions for transactional multi-step operations on Excel files. |
| Named Items and Functions | Access named ranges, defined names, and custom functions within Excel workbooks. |
| Conditional Formatting | Apply and query conditional formatting rules on cell ranges via the REST API. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Reporting | Generate Excel-based financial, operational, or analytical reports programmatically from business data. |
| Data Import and Export | Read data from Excel workbooks into business applications or write application data into Excel formats. |
| Spreadsheet Automation | Automate repetitive Excel tasks such as data cleanup, formula recalculation, and sheet formatting. |
| Business Intelligence Pipelines | Extract and transform Excel data for loading into data warehouses and BI tools. |
| Financial Modeling | Execute complex financial models stored in Excel and retrieve results via API for application integration. |
| Form and Survey Data Collection | Use Excel as a data store for forms and survey responses collected via web or mobile applications. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Power Automate | No-code automation flows that read and write Excel data using the Excel Online Business connector. |
| Microsoft Power BI | Publish Excel workbooks to Power BI for interactive dashboards and data visualization. |
| Azure Logic Apps | Enterprise workflow automation that connects Excel data to Azure services and external APIs. |
| Python openpyxl | Open-source Python library for reading and writing Excel 2010+ files without Microsoft Office. |
| Apache POI | Java library for reading and writing Microsoft Office formats including Excel XLSX files. |
| ExcelJS | Node.js library for reading, manipulating, and writing Excel workbook files. |
| Google Sheets API | Google's spreadsheet REST API offering similar capabilities for Sheets-based workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Microsoft Graph Excel API](openapi/microsoft-graph-excel-api-openapi.yml)

### JSON Schema

- 13 schema files in [json-schema/](json-schema/)

### JSON Structure

- 13 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Microsoft Graph Excel API Context](json-ld/microsoft-graph-excel-api-context.jsonld)

## Vocabulary

- [Advanced Excel Vocabulary](vocabulary/advanced-excel-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, and 3 personas across the Excel API operational dimension

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
