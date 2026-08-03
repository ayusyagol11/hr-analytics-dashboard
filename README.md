# HR Analytics Dashboard

An interactive HR analytics dashboard built in **Tableau Public**, giving a single-view snapshot of workforce composition, hiring/attrition trends, department distribution, location split, demographics, and compensation.

🔗 **Live dashboard:** [Tableau Public — HR Analytics Dashboard](https://public.tableau.com/app/profile/aayush.yagol/viz/HR-dashboard_17581424319570/HRsummary)
📁 **Source workbook:** [HR_Dashboard.twbx](HR_Dashboard.twbx) — open in Tableau Desktop or Tableau Public to explore the underlying build

---

## Overview

![Dashboard Overview](screenshots/01-dashboard-overview.png)

The workbook ships with **two dashboards** built on **21 worksheets**:

- **HR | Summary** (featured above) — the main landing view covering Overview, Demographics, and Income panels.
- **HR | Details** — a supporting detail-level view for drilling into individual records.

The Summary dashboard is organised into three panels:

- **Overview** — Active employee count, hired vs. terminated trend lines, a department-level breakdown (headcount + terminations), and a US location map split by HQ vs. Branch.
- **Demographics** — Gender split, an Education x Age distribution grid, and an Education x Performance rating matrix.
- **Income** — Education x Gender salary bands (with adjustable range sliders) and an Age x Salary scatter plot labelled by job role.

## Key Features

- **Cross-filtering / highlight actions** — clicking any mark (e.g. a department bar) dynamically highlights related data and dims everything else across all panels.

![Cross-filter highlight](screenshots/02-cross-filter-highlight.png)

- **Global filter controls** — Gender, Status, Location, and Hire Date filters that can be toggled on to slice the entire dashboard.

![Filters panel](screenshots/03-filters-panel.png)

- **Interactive salary range sliders** — drag the Education-level income sliders to constrain the salary bands shown in the Age x Salary scatter plot.

![Income slider interaction](screenshots/04-income-slider-interaction.png)

## Tech Stack

- **Tableau Public / Desktop** for dashboard design, calculated fields, and dashboard actions
- Data source: **HumanResources** — a Tableau Hyper extract built from a HumanResources.csv dataset

## Data

The underlying dataset covers ~8,900 employee records across 7 departments (Operations, Sales, Customer Service, IT, Marketing, Finance, HR), with fields spanning demographics, education, performance ratings, compensation, and location.

## Repository Contents

| File | Description |
|---|---|
| `HR_Dashboard.twbx` | Packaged Tableau workbook — open directly in Tableau Desktop/Public |
| `screenshots/` | Dashboard screenshots used in this README |
| `README.md` | This file |

## Author

**Aayush Yagol**
- Portfolio: [aayushyagol.com](https://aayushyagol.com)
- Tableau Public: [public.tableau.com/app/profile/aayush.yagol](https://public.tableau.com/app/profile/aayush.yagol/vizzes)
- LinkedIn: [linkedin.com/in/aayush-yagol-046874145](https://linkedin.com/in/aayush-yagol-046874145/)
- GitHub: [@ayusyagol11](https://github.com/ayusyagol11)
