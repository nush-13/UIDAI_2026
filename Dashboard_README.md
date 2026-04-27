# Aadhaar Temporal & Seasonal Analysis Dashboard

This project is a comprehensive data visualization dashboard designed to analyze Aadhaar enrolment and update trends across different dimensions like time, age, and geography. It utilizes multiple visualization libraries to provide a rich, interactive experience.

## Tech Stack
- **D3.js**: Used for custom, highly interactive visualizations like the monthly trend and seasonal heatmap.
- **Google Charts**: Leveraged for specialized charts like the India GeoChart and the demographic pie chart.
- **CanvasJS**: Used for high-performance charting of biometric and demographic update trends.
- **Vanilla CSS**: Custom styling with a modern, glassmorphic aesthetic.

## Dashboard Overview

### Key Performance Indicators (KPIs)
The top section displays aggregate metrics for the year 2023:
- **Total Enrolments**: 94.7M (Jan–Dec 2023)
- **Demographic Updates**: 31.2M updates across all states.
- **Biometric Updates**: 18.5M updates (Fingerprint + Iris).
- **Peak Month**: October, identifying the highest single-month activity.

### Visualizations

#### 1. Monthly Enrolment Trend (D3.js)
- **Description**: A smooth line/area chart with interactive data points.
- **Display**: Shows the volume of Aadhaar enrolments (in millions) for each month from January to December.
- **Insights**: Helps identify growth patterns and peak enrolment periods throughout the year.

#### 2. Age Group Distribution (Google Charts)
- **Description**: A donut chart showing the breakdown of the user base.
- **Display**: Categorizes enrolments into five age brackets: 0–18, 19–35, 36–50, 51–65, and 65+.
- **Insights**: Visualizes which demographic segments are most active in the Aadhaar ecosystem.

#### 3. Biometric Updates by Type (CanvasJS)
- **Description**: A stacked bar chart.
- **Display**: Breaks down biometric updates into two categories: **Fingerprint** and **Iris**, plotted across the 12 months.
- **Insights**: Useful for tracking which biometric modalities are most frequently updated and identifying seasonal spikes in biometric maintenance.

#### 4. Seasonal Heatmap (D3.js)
- **Description**: A grid-based heatmap (Age Groups vs. Months).
- **Display**: Each cell represents the intensity of activity (in thousands) for a specific age group in a specific month.
- **Insights**: Reveals complex correlations between user age and seasonal behavior (e.g., higher activity in school-age groups during specific months).

#### 5. State-wise Enrolments (Google GeoChart)
- **Description**: An interactive choropleth map of India.
- **Display**: Highlights states with varying shades of blue based on the volume of enrolments.
- **Insights**: Provides a geographic distribution of Aadhaar adoption, highlighting states with the highest density of new enrolments like Uttar Pradesh and Maharashtra.

#### 6. Demographic Updates Trend (CanvasJS)
- **Description**: A spline area chart with a vibrant pink aesthetic.
- **Display**: Tracks the monthly trend of demographic updates (name, address, date of birth, etc.).
- **Insights**: Monitors the consistency of data maintenance by citizens over the course of the year.

## How to Run
Simply open the `index(1).html` file in any modern web browser. The dashboard is fully self-contained and uses CDN-hosted libraries.
