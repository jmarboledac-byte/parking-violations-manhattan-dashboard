# parking-violations-manhattan-dashboard

This repository contains resources for a Power BI dashboard analyzing parking violation tickets issued in Manhattan, New York City from 2016–2023. The dashboard shows how many tickets were issued each year, how much revenue those tickets generated, and which NYPD precincts issued the most tickets.

## Features

- Number of parking tickets issued per year (2016–2023).
- Total revenue collected from parking tickets each year.
- Breakdown by NYPD precinct and year.
- Interactive filters for year and precinct.

## Files

- **PBIX report** – The Power BI Desktop file (.pbix) containing the dashboard and data model. Because of GitHub’s file‑size limits, it’s hosted on Google Drive. Download it here: [Parking Violations Dashboard PBIX](REPLACE_WITH_GOOGLE_DRIVE_LINK).
- **README.md** – Project description and data source information.

## Data Sources

The dashboard uses data from the NYC Open Data “Parking Violations Issued – Fiscal Year 2016–2023” datasets. These public datasets include every parking summons issued in New York City and contain fields like:
- *Summons Number* – unique identifier for each ticket.
- *Issue Date* – date the ticket was issued.
- *Precinct* – NYPD precinct that issued the ticket.
- *Violation Location* and related fields.
- *Fine Amount* – monetary value of the ticket.

For this project, only records where the `borough` is “MANHATTAN” were loaded. Aggregations (ticket counts and revenue totals) were calculated in Power BI.

## How to View the Dashboard

1. Download the PBIX file from the link above.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open the PBIX file in Power BI Desktop and explore the visuals.
4. To refresh the data or make modifications, connect to updated NYC Open Data CSV files for each fiscal year and refresh in Power BI.

Feel free to clone this repository and adapt the dashboard for other boroughs or additional years.
