# Room Occupancy Dashboard in Tableau

This project presents an interactive Tableau dashboard designed to analyze room usage across a 24-hour cycle. The dashboard uses a synthetic occupancy dataset to classify each hour as low, moderate, or high usage based on occupancy rate.

The goal of the project is to show how facilities, operations, or administrative teams can use a simple dashboard to monitor space utilization, identify peak demand periods, and spot underused time blocks.

## Project Overview

The dashboard includes:

- A 24-hour room usage timeline
- Green, amber, and red occupancy status classifications
- A selected-hour detail view
- An occupancy trend line
- A summary of hours by usage status
- A date filter for reviewing usage across multiple days

## Tools Used

- Tableau
- CSV data
- Synthetic data design
- Data visualization
- Dashboard design

## Dataset

The dataset was synthetically created for portfolio and demonstration purposes. It includes hourly room occupancy records across multiple days, with fields for date, hour, room capacity, occupancy count, occupancy rate, booking type, and usage status.

## Occupancy Status Logic

| Status | Occupancy Rate | Meaning |
|---|---:|---|
| Low Usage | 0%–49% | Room is lightly used |
| Moderate Usage | 50%–79% | Room has steady usage |
| High Usage | 80%–100% | Room is near or at capacity |

## Dashboard Purpose

This dashboard helps users quickly understand when a room is underused, moderately used, or highly occupied. It is intended as a lightweight space utilization tool for facilities planning, scheduling review, and operational decision-making.
