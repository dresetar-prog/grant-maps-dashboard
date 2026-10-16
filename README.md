# Grant Applications Analytics & Geo-Dashboard

Interactive maps, heatmaps, and analytical dashboards visualizing 43,111 grant applications across regions, funding cycles, business types, and revenue tiers.

## Dataset Overview
- **Records:** 43,111 applications
- **Primary Source:** Salesforce Export
- **Core Dimensions:**
  - **Geography:** Address, City, State, Zip, Zip Region, Grant Region
  - **Firmographics:** B2B vs. B2C, Employee Counts, Company Sector, Business Debt, Capital Raised
  - **Financials:** Qualifying Revenue, Last Year Revenue, Prior 12 Months Revenue
  - **Program Data:** Grant Name, Grant Program, Grant Year, Application Dates

## Project Structure
- `data/grant_applications.csv`: Cleaned grant export data.
- `index.html`: Web-based interactive dashboard with heatmaps and charts.
