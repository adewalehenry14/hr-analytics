# # HR Project — Power BI Report

A Power BI report tracking HR metrics across the organization.

## Report Pages

|Page                     |Description                                             |
|-------------------------|--------------------------------------------------------|
|**Final worth by Gender**|Pie chart visualizing final worth distribution by gender|
|**Page 1**               |Table and clustered bar chart with detailed HR data     |

## File Structure

```
hr_project/
├── Version                          # Report format version (1.28)
├── Metadata                         # Report metadata (created from Power BI Cloud, release 2024.11)
├── Settings                         # Query and report settings
├── DiagramLayout                    # Data model diagram layout
├── SecurityBindings                 # Report security configuration
├── DataModel                        # Compressed data model
├── [Content_Types].xml              # OOXML content types manifest
└── Report/
    ├── Layout                       # Report page layouts and visual definitions
    └── StaticResources/
        └── SharedResources/
            └── BaseThemes/
                └── CY24SU10.json   # Power BI theme (CY24SU10)
```

## Getting Started

1. Clone this repository
1. Open the project in **Power BI Desktop** (version 2024.11 or later)
1. The report was created from Power BI Cloud — you may need to reconnect data sources

## Requirements

- Power BI Desktop 2024.11+
- Appropriate data source credentials

## Notes

- This project uses the `.pbip` (Power BI Project) format, which stores report files as human-readable JSON for version control
- The `DataModel` file contains the compressed data model and is binary

## Author
Adetunji Adewale Henry
