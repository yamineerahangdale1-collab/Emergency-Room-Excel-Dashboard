# Hospital Emergency Room Dashboard

An interactive Excel dashboard built to track monthly emergency room performance for a hospital. It brings together patient volume, wait times, satisfaction scores, and department referrals into a single view that updates by year and month selection

(./excel_1st_dashboard.png)

## Overview

The dashboard summarizes emergency room activity on a monthly basis. A hospital administrator or operations manager can select a year and month from the slicers on the left and instantly see how the ER performed during that period, from patient count to how many cases were delayed versus attended on time.

## Key Metrics Tracked

The dashboard surfaces three headline numbers at the top: total patient count for the selected period, average wait time, and patient satisfaction score. Each of these sits above a sparkline trend so you can see the pattern across the month at a glance, not just the final number.

Below that, an admission status table breaks down how many patients were admitted versus not admitted, with a percentage split and an inline bar visualization for quick comparison.

The right side of the dashboard covers two donut and pie charts: one showing the share of patients attended within time versus delayed, and another showing the gender split of patients treated. A department referral chart lists out patient counts by department, from General Practice and Orthopedics down to smaller volumes like Renal and Gastroenterology, so bottlenecks or high-demand departments are easy to spot.

At the bottom, a bar chart breaks patient volume down by age group, in ten-year bands from 0-9 up to 70-79.

## Tools and Techniques Used

This dashboard was built entirely in Excel using PivotTables and PivotCharts as the data source for each visual. Slicers connect the year and month selectors to every chart and table, so the whole dashboard reacts to a single click. Sparklines were used for the trend indicators under each KPI card, and conditional formatting was applied to the admission status bars for a clean, dashboard-native look rather than relying on a standard chart type.

## Sample Insight

For January 2024, the data shows 513 patients treated with an average wait time of about 3632 seconds and a satisfaction score of 495.92. Roughly 62% of patients were attended within the target time, while General Practice and Orthopedics accounted for the largest share of department referrals.

## Files in This Repository

The repository includes the Excel workbook with all PivotTables, PivotCharts, and slicers, along with the dashboard image used in this README.

## Connect

If you'd like to discuss this project or explore the workbook in more detail, feel free to reach out on [LinkedIn](https://linkedin.com/in/yaminee-rahangdale-96b754397) or check out more of my work on [GitHub](https://github.com/yamineerahangdale1-collab).
