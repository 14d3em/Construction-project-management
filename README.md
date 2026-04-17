# Construction Project Management Dashboard

An interactive Power BI dashboard providing end-to-end visibility into construction project performance, financials, and task management.

## Overview

This dashboard consolidates key project data across 100 projects and 300 tasks, offering stakeholders a centralized view of budget health, task progress, and profitability trends.

## Features

- **Cost & Budget by Month** – Line chart tracking actual costs vs. budget targets (Jan–Aug), including min/max budget and cost envelopes
- **Profit by Month** – Bar chart visualizing monthly profit fluctuations, highlighting peak ($3.9K) and trough (–$1.0K) periods
- **Projects by Status** – Donut chart breaking down projects across four statuses: Completed (26%), Behind (29%), On Track (25%), and On Hold (20%)
- **Tasks by Priority** – Horizontal bar chart categorizing 300 tasks into High (156), Medium (91), and Low (53) priority levels
- **Tasks by Progress Group** – Distribution of tasks across completion bands (0–20%, 21–40%, 41–60%, 61–80%, 81–100%)
- **Task by Project Type** – Toggle-style breakdown across Construction (20%), Renovation (26%), and other categories
- **Budget Utilization** – Gauge showing 30.73% of total budget consumed
- **Task Completion Rate** – Gauge displaying 64% overall task completion
- **Geographic Distribution** – US choropleth map showing tasks and projects by location
- **Project Manager Performance Table** – Tabular view with per-manager metrics including tasks, overdue tasks, cost, budget, profit, and utilization SVGs

## Tech Stack

- Power BI Desktop
- DAX for calculated measures
- Custom SVG visuals for completion and utilization indicators

## Use Case

Designed for construction project managers, PMO teams, and executive stakeholders who need real-time visibility into project delivery, financial performance, and resource allocation.
