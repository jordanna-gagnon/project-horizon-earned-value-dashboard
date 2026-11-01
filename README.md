# Project HORIZON: Earned Value Dashboard

*All data in this project is AI-synthesized for practice. It does not represent a real program.*

**Live dashboard:** [View on Tableau Public](PASTE-YOUR-LINK-HERE)

![Executive Summary dashboard](images/dashboard-1-executive-summary.png)

## Problem
A program manager needs to know what is late, what is over budget, and what the project will cost at completion.

## Data
A simulated 12-month flight research campaign: 8 work packages, a $5M budget, 56 monthly cost records, 40 tasks, and 15 risks. Cost performance was designed with a spending curve and performance factors so that some packages are on track and others are behind or over budget.

## Method
- Related four tables in Tableau on a shared key (WP_ID).
- Calculated earned value metrics: SPI, CPI, EAC, and VAC, driven by a status-month parameter.
- Rated each package Red, Yellow, or Green (thresholds: 0.90 and 0.97).
- Built a task timeline, a risk heatmap, and a top-risks view.

## Key findings (Month 7)
1. The project is 7% behind schedule and 5% over cost efficiency, forecasting a $271K overrun.
2. The Flight Simulator (SPI 0.85, CPI 0.80) is the highest-risk package.
3. The top-scored risk (late sensors) sits in Airborne Measurements, which is behind schedule.

## Limitations
- Performance factors are constant over time.
- Earned value is derived from planned value, not measured from task progress.
- The data is synthetic.

## Files
- `Project-HORIZON_Earned Value Dashboard.twbx`: the data model
- `Project_HORIZON_Executive-Summary.pptx`: one-page summary slide
- `Executive_Summary_Basboard_Schedule_&_Risk_Dashboard.pdf`: dashboard screenshots
