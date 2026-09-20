# Website Analysis Performance

## 📊 Project Overview

This project analyzes website performance and user engagement using website analytics data.

The analysis focuses on understanding website traffic, user behavior, engagement levels, and performance across different traffic channels and hours of the day.

The project is implemented in **Python using Jupyter Notebook** with data analysis and visualization libraries.

## 🎯 Objectives

* Analyze website users and sessions over time.
* Compare website traffic across different channel groups.
* Analyze average engagement time per session.
* Understand engagement rate across channels.
* Identify traffic patterns by hour of the day.
* Compare engagement rate with the number of sessions.
* Generate visual insights from website analytics data.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data loading, cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

## 📁 Project Structure

```text
Website-Analysis-Performance/
│
├── Website analysis performance project.ipynb
├── Data-export.csv
└── README.md
```

## 📌 Dataset

The project uses website analytics data stored in `Data-export.csv`.

The dataset contains metrics such as:

* Channel Group
* Date and Hour
* Users
* Sessions
* Engaged Sessions
* Average Engagement Time per Session
* Engaged Sessions per User
* Events per Session
* Engagement Rate
* Event Count

## 🔄 Data Preparation

The following preprocessing steps are performed:

1. Load the CSV dataset using Pandas.
2. Remove the unnecessary first row.
3. Rename the dataset columns for easier analysis.
4. Convert the `DateHour` column into a datetime format.
5. Convert numerical columns into appropriate numeric data types.
6. Extract the hour from the `DateHour` column.
7. Use descriptive statistics to understand the dataset.

## 📈 Analysis & Visualizations

### 1. Sessions & Users Over Time

A line chart is used to analyze how the number of users and sessions changes over time.

### 2. Total Users by Channel

A bar chart compares the total number of users coming from different channel groups.

### 3. Average Engagement Time by Session

The project compares the average engagement time across different traffic channels.

### 4. Engagement Rate Distribution by Channel

A box plot is used to examine the distribution of engagement rates for different channel groups.

### 5. Traffic by Hour & Channel

A heatmap shows website session traffic according to the hour of the day and channel group.

### 6. Engagement Rate vs Sessions Over Time

A time-series visualization compares engagement rate and sessions over time to observe their patterns.

## 🔍 Key Metrics

The project works with important website performance metrics including:

| Metric                  | Description                                |
| ----------------------- | ------------------------------------------ |
| Users                   | Number of website users                    |
| Sessions                | Number of website sessions                 |
| Engaged Sessions        | Sessions that meet the engagement criteria |
| Engagement Rate         | Percentage of sessions that were engaged   |
| Average Engagement Time | Average time spent during a session        |
| Events per Session      | Average number of events during a session  |
| Event Count             | Total number of recorded events            |

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project folder

```bash
cd Website-Analysis-Performance
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Website analysis performance project.ipynb
```

Make sure `Data-export.csv` is in the same project folder as the notebook.

## 💡 Project Outcome

This project demonstrates how website analytics data can be transformed into meaningful visual insights.

It helps understand:

* Website traffic patterns
* User activity
* Channel performance
* Engagement behavior
* Hourly traffic trends
* Relationship between sessions and engagement

## 👩‍💻 Author

**Anuja Bhadane**

Computer Engineering Student

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Data Analysis` `Data Visualization`
