# Project Title: Will a Customer Accept the Coupon?

This repository contains an analysis of customer behavior regarding coupon acceptance while driving. The project aims to understand the factors influencing whether a driver accepts a coupon delivered to their phone for various establishments, such as restaurants, bars, and coffee houses

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction: 

The scenarios revolve around hypothetical driving situations and whether the driver would accept the coupon immediately, later, or not at all based on factors like location, weather, time, passenger type, and more.

### Overview

The objective is to use visualization techniques and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.

### Data
The dataset sourced from the UCI Machine Learning repository through Amazon Mechanical Turk includes attributes like user demographics (gender, age, marital status, education, income), behavioral patterns (frequency of visiting various establishments), contextual attributes (driving destination, weather, time, passengers), and coupon specifics (expiration time, venue type).

### Deliverables
The final report highlights differences between customers who accepted and those who rejected coupons. The analysis involves statistical summaries, visualizations, and Python code to explore the dataset. The findings will be shared in a public GitHub repository as a portfolio piece.

### Data Description
The attributes in the dataset include user demographics, driving context, and coupon attributes, providing insights into user behaviors and preferences in accepting coupons.

### Hypotheses and Acceptance Rates for "Bar" coupon
#### Hypothesis: Drivers accepting Bar coupons might be influenced by factors like age, marital status, and frequency of visits.
#### Acceptance rate for drivers who go to Bar:
The drivers who accepted the bar coupons are most likely either:
-  Drivers who go to bars more than once a month and are under the age of 30 and (Acceptance rate = 71.32 %)
-  Drivers who go to bars more than once a month, passengers not kids, and not widowed (Acceptance rate = 72.17 %)

### Hypotheses and Acceptance Rates for "Coffee House" coupon
#### Hypothesis: Drivers accepting CoffeeHouse coupons might be influenced by factors like age, marital status, and frequency of visits.
#### Acceptance rate for drivers who go to CoffeeHouse:
The drivers who accepted the CoffeeHouse coupons are most likely either:
 - Less than 21 years old, single, visiting less than once or more (Acceptance rate = 74.157 %)
- Visiting at least once, at 10 AM, with income between $59K to $62.5K (Acceptance rate = 80 %)
- Female drivers with children and specific occupations (Construction & Extraction, Architecture & Engineering, Protective Service,  and Healthcare Support) (Acceptance rate = 75.00 %)

### Conclusion
The analysis explores several conditions affecting coupon acceptance, providing insights into customer behavior regarding various establishment coupons (Bar and Coffee ouse) while driving.



## Features

As follow the list of the main features/functionalities of our study:

- ### Problem Presentation:
  Includes: reading the data, Investigatation the dataset for missing or problematic data, Decidng what to do about your missing data (drop, replace, other etc.),  computation of the proportion of the total observations who chose to accept the coupon?, Use of a bar plot to visualize the coupon column,and use of a histogram to visualization to the temperature column.
- ### Investigating the Bar Coupons:
   Includes: creation of  a new DataFrame that contains just the bar coupons, computation of the proportion of the accepted bar coupons, comparison of the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more, comparison between the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others and disucession of the diiference between both, comparison of the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry and Comparsion of  the acceptance rates between different kind of drivers, and final conculusion about the drivers who accepted the bar coupons?)
- ### Independent Investigation: The Coffee House Coupons
  Used of the same methodoloy as the Bar coupons and study of the data to find new combinations of the acceptance rates for coffee house coupons drivers


## Installation

To use Kraftwerk, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/ahachani/kraftwerk.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd kraftwerk

## Usage

Once you have installed Kraftwerk, here's how you can use it:

1. **Import Kraftwerk:**
    First, import Kraftwerk into your Python script or Jupyter Notebook:
    ```python
    from kraftwerk import Kraftwerk
    ```

2. **Initialize Kraftwerk:**
    Create an instance of Kraftwerk:
    ```python
    kraftwerk_instance = Kraftwerk()
    ```

3. **Perform Operations:**
    Use the methods provided by Kraftwerk to perform various operations. 

4. **Customize as Needed:**
    Explore additional functionalities and parameters available in Kraftwerk to suit your specific use case. 

5. **Interpret Results:**
    After performing operations, interpret the results and use them according to your project requirements.

6. **Further Steps:**
    Continue refining your workflow and utilizing Kraftwerk's features as needed for your data processing and machine learning tasks.





