# Booking Analytics Dashboard

## Project Overview
The **Booking Analytics Dashboard** is an interactive web application designed to analyze and visualize booking trends for a multi-service business. It provides insights into booking trends over time and revenue distribution across different services. The dashboard is built using **Dash, Plotly, and Pandas**, making it interactive and user-friendly.

## Features
- 📊 **Booking Trend Visualization** – A histogram displaying booking trends over time.
- 🥧 **Revenue Breakdown** – A pie chart showing revenue distribution by service type.
- 🎛️ **Interactive Filtering** – Users can filter data by booking type.
- 🔄 **Real-Time Updates** – Graphs update dynamically based on user selection.

## Technologies Used
- **Python** 🐍
- **Dash** (for building the web application)
- **Plotly Express** (for interactive visualizations)
- **Pandas** (for data manipulation)
- **OpenPyXL** (for reading Excel files)

## Dataset Information
The dataset contains booking records for various services, including:
- **Booking Type:** Class, Facility Rental, Subscription, Birthday Party
- **Booking Date & Status:** Confirmed, Pending, or Canceled
- **Service Name, Instructor, Duration, and Price**

## Installation and Setup

### 1️⃣ Install Dependencies
Before running the dashboard, install the required Python libraries:

```bash
pip install dash plotly pandas openpyxl
