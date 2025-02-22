# Programming for Data Analytics (PFDA)

## Assignment Repository

This repository contains assignments completed as part of the *Programming for Data Analytics* module in the Higher Diploma in Science in Data Analytics.

---

## Assignments

### **Assignment 2: Weather**
- **Objective**: Create a notebook to plot temperature over time.
- **Key Steps**:
  - Load the CSV file using `pandas`.
  - Convert `reportStartDateTime` to `datetime` format.
  - Create scatter and line plots of temperature over time.

---

### **Assignment 3: Domains**
- **Objective**: Analyze and visualize email domains using a pie chart.
- **Key Steps**:
  - Load the dataset into a `pandas` DataFrame.
  - Extract email domains by splitting the `Email` column.
  - Count the frequency of each domain using `value_counts()`.
  - Plot a pie chart showing domain distribution with labels and percentages.

---

### **Assignment 5: Risk**
- **Objective**: Simulate 1000 Risk battle rounds (3 attackers vs. 2 defenders) and visualize the results.
- **Key Steps**:
  - Simulate battles using dice rolls to determine troop losses.
  - Plot the outcomes of 1000 battles in a bar chart (attacker wins, defender wins, ties).
  - For advanced marks, simulate full battles until one side is eliminated, and plot troop counts over time.

---

### **Assignment 6: Knock Airport Weather**
- **Objective**: Analyze weather data from Knock Airport and create visualizations.
- **Key Steps**:
  - Load and preprocess the dataset from the provided link.
  - Plot temperature trends over time, including daily and monthly means.
  - Analyze windspeed data:
    - Plot rolling windspeed (24-hour period).
    - Plot daily maximum and monthly mean of daily maximum windspeed.
  - Handle missing windspeed data using forward-fill.

---

## Project
I have chosen to do my project using the weather data for the Shannon Airport. Here I will be analysing the information broadly ebfore focusing in on two specific variables and their relationship with each other based on the data collectedf from 1945 - 2024. 

The variales I will be looking at are:
- Mean Temperature
- Mean Wind Speed

### Conclusion
The weak negative relationship between temperature and wind speed isn't strong enough to make predictions. Other factors, like location, time of year, pressure systems, or local weather, could be affecting both.

This weak correlation shows that weather patterns are complex and influenced by many things. Wind speed can be affected by storms, pressure, or geography, not just temperature.

To better understand the relationship between wind speed and temperature, more analysis is needed.
---

## Author
Emmet Devaney
