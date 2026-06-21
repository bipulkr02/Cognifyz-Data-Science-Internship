# Cognifyz Technologies - Data Science Internship

This repository contains my submission for the **Data Science Internship** at **Cognifyz Technologies**. As part of the internship, I completed **Level 1** and **Level 2** tasks using a real-world restaurant dataset.

## 📁 Repository Structure

```
├── Level1/
│   ├── Level1_Data_Exploration_Preprocessing_Analysis.ipynb
│   ├── Level1_Data_Exploration_Preprocessing_Analysis.py
│   ├── Level1_Results_Log.txt
│   ├── Dataset_.csv
│   └── charts (PNG files)
│
├── Level2/
│   ├── Level2_TableBooking_PriceRange_FeatureEngineering.ipynb
│   ├── Level2_TableBooking_PriceRange_FeatureEngineering.py
│   ├── Level2_Results_Log.txt
│   ├── task3_engineered_features.csv
│   ├── Dataset_.csv
│   └── charts (PNG files)
```

## 📊 About the Dataset

The dataset contains information about **9,551 restaurants** across 21 columns, including details like restaurant name, location (latitude/longitude), cuisines, price range, ratings, votes, table booking, and online delivery availability.

## ✅ Level 1 - Data Exploration, Preprocessing & Analysis

**Task 1: Data Exploration and Preprocessing**
- Explored dataset shape and structure (rows/columns)
- Identified and handled missing values (`Cuisines` column)
- Performed data type conversions
- Analyzed the distribution of the target variable (`Aggregate rating`) and identified class imbalance

**Task 2: Descriptive Analysis**
- Calculated statistical measures (mean, median, std) for numerical columns
- Explored distribution of categorical variables (Country Code, City, Cuisines)
- Identified top cuisines and cities by restaurant count

**Task 3: Geospatial Analysis**
- Visualized restaurant locations using latitude/longitude
- Analyzed restaurant distribution across cities/countries
- Checked correlation between location and rating

### Key Findings
- The dataset shows strong class imbalance — many restaurants have a 0 rating (not yet rated)
- **North Indian** cuisine and **New Delhi** city have the highest restaurant counts
- No strong correlation found between raw geographic coordinates and rating

## ✅ Level 2 - Business Insights & Feature Engineering

**Task 1: Table Booking and Online Delivery**
- Calculated percentage of restaurants offering table booking and online delivery
- Compared average ratings between restaurants with/without table booking
- Analyzed online delivery availability across price ranges

**Task 2: Price Range Analysis**
- Determined most common price range
- Calculated average rating per price range
- Identified the rating color associated with highest average rating

**Task 3: Feature Engineering**
- Created new features: `Restaurant Name Length`, `Address Length`
- Encoded categorical Yes/No columns into binary features

### Key Findings
- Restaurants with table booking have higher average ratings
- Online delivery is more common in lower-to-mid price ranges
- Average rating increases with price range; "Dark Green" rating color corresponds to the highest-rated restaurants

## 🛠️ Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

## 🙌 Acknowledgment
Special thanks to **Cognifyz Technologies** for this learning opportunity.

#cognifyz #cognifyzTech #cognifyzTechnologies
