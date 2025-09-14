# Finding Untapped Self-Storage Markets in Phoenix 🗺📦

## 📌 Project Overview
This project explores how data science can help identify the best locations to open new self-storage facilities in **Phoenix, Arizona**. Self-storage is more than just extra space — it plays a crucial role in helping people manage life transitions, store assets, and optimize space. What started as a curiosity turned into a data-driven solution to predict where new self-storage businesses would thrive.

## 🧩 Business Problem
Can data science provide a smarter way to find optimal locations for self-storage units, going beyond guesswork and anecdotal advice?

## 🚀 Approach
I built an end-to-end solution that combines various public datasets to understand neighborhood characteristics and predict market competition using machine learning.

### Data Sources
- 🗺 **Geospatial Data**: Neighborhood boundaries from the US Census Bureau  
- 🏢 **Competitor Data**: Locations of existing self-storage facilities from OpenStreetMap  
- 📊 **Demographic Data**: Income levels, household sizes, renter vs. owner ratios, migration patterns from the Census API  
- 🚗 **Civic Data**: Daily traffic counts and zoning maps from the City of Phoenix’s open data portal

### Modeling
- Engineered features from diverse datasets  
- Trained a **Random Forest model** to predict market saturation  
- Boosted model performance (R² from 33% to over 71%) by adding traffic and proximity-based features  
- Identified opportunity gaps — neighborhoods with high potential but few competitors  
- Filtered results using zoning laws and land use constraints

## 📊 Key Insights
- Location context (traffic, proximity to apartments/universities) is more predictive than population or income alone  
- Data-driven recommendations can guide strategic business decisions  
- The final output is an interactive map highlighting the top untapped markets in Phoenix

## 📂 Repository Contents
- `notebook.ipynb`: The full step-by-step analysis and modeling workflow  
- `data/`: Processed datasets used for training and evaluation  
- `README.md`: This file explaining the project

