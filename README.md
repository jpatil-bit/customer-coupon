# Customer Coupon Acceptance - Exploratory Data Analysis (EDA)

## Project Overview

This project focuese on performan an EDA on the dataset related to the coupon acceptance.
The goal is to analyse the dataset and understand the patterns for the coupon acceptance.
Focus is to study the Bar and Coffee coupon acceptance.
Analysis includes examing how **age** , **weather** , **income** , **temperature** , **coupon expiration** ,**marital status** and others impact the coupon acceptance rate.
Visualizations such as **bar plots** are used to gain insights from the data.

---

## Tools and Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For advanced statistical plots and visualization.
- **Jupyter Notebook**: For running and presenting the analysis interactively.
- **colorama** : Exploring this new library for styling and coloring the fonts for the hypothesis.

---

## Dataset
https://github.com/jpatil-bit/customer-coupon/blob/main/data/coupons.csv

### Key Features:

---

##  Analysis and hypothesis
########## **Hypothesize about drivers who accepted the bar coupons** ##########
1. Coupon rejection is more than coupon acceptance. 
2. Coupon acceptance rate is 56.8% , out of which 41.00% is the Bar coupon acceptance. 
3. Drivers over the age of 25 visit bars more frequently (more than once a month) compared to younger age groups.. 
4. Drivers with no kids and not in the occupation of farming, fishing, or forestry visit bars more frequently than parents in others.. 
5. Drivers with age <30 and income <50k , with passanger having no kids , not widowed , visits bar more frequently and visits restaurant < $20 4-8 times a months
   
########## **Hypothesize about drivers who accepted the coffee coupons** ##########
1. Coffee coupon acceptance rate is 49.92%. 
2. Sunny day with temperature of 30 F has more acceptance. 
3. 26 years old singles and 36 years old unmarried partner has more acceptance of coffee coupons. 
4. Male driving to non urgent destination has more acceptance than others. 

---

##  Visualizations

Various visualizations are used in this analysis to uncover insights from the data:

- **Bar Plots**: To compare coupon acceptance rates across different categories (e.g., age, marital status).
- **KDE (Kernel Density Estimate)**: To visualize the distribution of continuous features (e.g., age, income) against coupon acceptance.
- **Heatmaps**: To check correlations between numerical features.
- **Histograms**: To analyze the distribution of continuous features like age and income.
- **Box Plots**: For identifying outliers and examining the spread of data.

---

##  Getting Started

To run this project locally, follow the steps below:

### Prerequisites

Ensure you have Python 3.x installed and the necessary dependencies:

1. Clone the repository:

   ```bash
   git clone https://github.com/jpatil-bit/customer-coupon.git
