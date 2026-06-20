# 🚀 SpaceX Launch Dashboard

An interactive dashboard built with **Python, Dash, and Plotly** for visualizing and analyzing SpaceX launch records.

## 📌 Overview

This project provides interactive data visualizations for SpaceX launches. Users can explore launch success rates, filter by launch site, and analyze the relationship between payload mass and launch outcomes.

## ✨ Features

* 📍 Launch site selection using a dropdown menu
* 🥧 Pie chart showing launch success distribution
* 🎚 Payload mass range slider
* 📈 Scatter plot showing payload mass vs. launch success
* 🎨 Color-coded booster version categories
* ⚡ Interactive charts powered by Plotly

## 🛠 Technologies Used

* Python
* Dash
* Plotly Express
* Pandas

## 📂 Project Structure

```text
spacex-launch-dashboard/
│
├── app.py
├── spacex_launch_dash.csv
├── requirements.txt
├── README.md
└── screenshots/
```

## 📊 Dashboard Components

### 1. Launch Site Dropdown

Allows users to:

* View results for all launch sites
* Select a specific launch site

### 2. Success Pie Chart

Displays:

* Total successful launches across all sites
* Success vs. failure for a selected site

### 3. Payload Range Slider

Filters launches based on payload mass.

### 4. Scatter Plot

Shows the correlation between:

* Payload Mass (kg)
* Launch Success
* Booster Version Category

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spacex-launch-dashboard.git
cd spacex-launch-dashboard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶ Running the Application

```bash
python app.py
```

Open your browser and navigate to:

```text
http://127.0.0.1:8050/
```

## 📦 Requirements

```text
dash
pandas
plotly
```

or install manually:

```bash
pip install dash pandas plotly
```

## 📸 Screenshots

Add screenshots of the dashboard inside the `screenshots/` folder and reference them here.

## 🎯 Learning Objectives

This project demonstrates:

* Building interactive dashboards with Dash
* Working with Pandas DataFrames
* Creating dynamic visualizations with Plotly
* Using callbacks and reactive components
* Data exploration and analytics

## 📄 License

This project is intended for educational and portfolio purposes.

