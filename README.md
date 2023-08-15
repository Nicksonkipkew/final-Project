# National-Wheelchair Expense Analysis and Prediction

This project aims to develop an accurate predictive model for wheelchair services and outcomes costs across diverse regions of England using modern data-driven techniques. The project addresses the challenge of creating an innovative machine learning model that goes beyond traditional predictive methodologies in the healthcare domain.

## Problem Statement
The conventional predictive paradigms fall short in capturing the intricacies embedded within the healthcare domain. The goal of this project is to engineer a predictive framework that not only surpasses existing models but also delves deep into the complex interplay between medical services, patient outcomes, and resource allocation.

## Problem Objectives
1. Analyze the statistical significance and impact of features like region, patient sign-ups, and new referrals on target metrics.
2. Efficiently target specific patient groups to optimize the delivery of wheelchair services and improve outcomes.
3. Develop a predictive model to determine the cost incurred for providing wheelchair services to patients and facilities.

## Data Description
The dataset contains information about wheelchair service costs, accessibility, volume, and patient experiences. It was provided by NHS England to enhance benchmarking and transparency in wheelchair services. The data was gathered quarterly from Integrated Care Boards (ICBs) to improve wheelchair services between July 2015 and June 2022.

## Variable Description
1. Total number of patients currently registered with the service (split by adults and children).
2. Number of new patients referred to the service within the reporting period (split by adults and children).
3. Number of new patients whose episode of care was closed in the reporting period and assessed as low, medium, high, or specialist need.
4. Number of re-referred patients whose episode of care was closed in the reporting period and assessed as low, medium, high, or specialist need.
5. Current expenditure on wheelchair services annually by the clinical commissioning group.
6. Transition from a voucher system to personal wheelchair budgets for increased choice and control for patients.

## Code Explanation
1. Libraries like numpy, pandas, matplotlib, seaborn, and scikit-learn are imported.
2. The dataset is loaded using pandas from a CSV file.
3. The first five rows of the dataset are displayed using the `head()` function.

## Instructions
1. Make sure you have all the necessary libraries installed before running the code.
2. Download the dataset "National-Wheelchair-Data-Collection-Results-Data-April-June-2023.csv" and place it in the same directory as the code.
3. Run the code to load the dataset and view the first five rows.

Feel free to analyze the code, modify it, and use it for your own analysis or projects related to healthcare accessibility and predictive modeling.
