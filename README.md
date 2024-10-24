
---

# EV Analytics Dashboard

## Overview

This project presents an analytical dashboard that visualizes key insights from an Electric Vehicle (EV) population dataset. The dashboard is designed to provide a comprehensive view of EV adoption trends, vehicle types, manufacturer statistics, and much more. It allows users to interact with the data through charts, tables, and insightful key metrics.

You can view the live dashboard here: [EV Analytics Dashboard](https://ev-analytic-dashboard.vercel.app/).

## Folder Structure

- **data-to-visualize/**  
  Contains the CSV file that was converted into JSON using Node.js's `fs` module and `csv-parse` library. This JSON data is the basis for all visualizations on the dashboard.

- **components/**  
  This folder contains reusable React components:
  - **BarChart.jsx**: Displays bar charts for various data points.
  - **PieChart.jsx**: Visualizes proportions in the dataset with pie charts.
  - **RangeDistribution.jsx**: Visualizes the distribution of electric vehicle ranges.
  - **DashboardCard.jsx**: Displays key metrics in card format.
  - **EvTable.jsx**: A table component with search, sorting, and pagination functionality to present the dataset.
  - **KeyInsight.jsx**: Summarizes key insights and findings from the data.

- **public/**  
  Contains public assets, including icons and static images.

- **src/**  
  Contains main application logic, configuration, and UI components.

## Features

### Dashboard

The EV Analytics Dashboard presents the following insights:
- **Total Vehicles**: Shows the total number of vehicles in the dataset.
- **Average Electric Range**: Provides the average electric range of vehicles.
- **Top Manufacturer**: Displays the manufacturer with the most vehicles.
- **Top Model**: Highlights the most common vehicle model in the dataset.

### Charts and Graphs

- **Electric Vehicle Types**: A pie chart that shows the distribution of different EV types.
- **Top 5 Counties**: A bar chart that highlights the counties with the highest number of EVs.
- **Top 5 Manufacturers**: A bar chart visualizing the manufacturers with the most vehicles in the dataset.
- **CAFV Eligibility**: A pie chart displaying Clean Alternative Fuel Vehicle (CAFV) eligibility among vehicles.

### Table

The table provides an interactive way to explore the data with search, sort, and pagination features, allowing users to easily find specific records or trends.

### Key Insights

The `KeyInsight` component summarizes useful information derived from the dataset, such as:
- Notable trends in electric vehicle adoption.
- Insights into model year distributions and manufacturer dominance.

## Installation

### Prerequisites

Ensure you have the following installed on your machine:
- Node.js (v16+)
- npm or yarn

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Pritam-Git01/mapup-analytic-dashboard.git
   ```

2. Navigate into the project directory:
   ```bash
   cd mapup-analytic-dashboard
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

### Run the Project

To run the project locally, use the following command:
```bash
npm run dev
```
or
```bash
yarn dev
```
This will start the development server on `http://localhost:3000`.

### Deployment

The project has been deployed using Vercel. To deploy it yourself, follow these steps:

1. Push the repository to your GitHub account.
2. Connect the GitHub repository to Vercel.
3. Set up the build and deploy the project on Vercel.

Your dashboard will then be live and accessible through the Vercel link.

## License

This project is licensed under the MIT License.

---
