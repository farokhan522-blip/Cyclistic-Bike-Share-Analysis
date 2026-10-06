# Cyclistic Bike-Share Analysis

## 📋 Project Overview
Comprehensive analysis of Cyclistic bike-sharing service to understand behavioral differences between **Member** and **Casual** users. This data-driven project identifies key usage patterns and provides actionable business recommendations for targeted marketing strategies.

## 📊 Dataset
- **Source**: Divvy Trips (2019 Q1 & 2020 Q1 data)
- **Records**: 365,289 bike rides
- **Time Period**: Q1 2019 and Q1 2020
- **Key Metrics**: Ride duration, user type, day of week, start/end times

## 🔍 Analysis Performed

### Data Cleaning & Preparation
- Combined datasets from two years (2019 Q1, 2020 Q1)
- Standardized column names across datasets
- Removed invalid rides (negative duration)
- Converted timestamps and calculated ride duration metrics
- Extracted day-of-week patterns

### Exploratory Data Analysis
- **User Type Distribution**: Members vs Casual riders
- **Ride Length Analysis**: Duration patterns by user type
- **Weekly Trends**: Usage patterns by day of week
- **Comparative Analysis**: Member vs Casual behavior metrics

### Key Findings
✅ **Members** take shorter, more frequent rides (weekday commuting pattern)  
✅ **Casual users** take longer rides with strong weekend preference  
✅ **Peak Usage**: Thursday highest for members, weekends for casual users  
✅ **Average Ride Length**: Casual users ride 2x longer than members  
✅ **Weekend Surge**: 40% more casual rides on weekends  

## 📊 Visualizations & Dashboard

**Tableau Dashboard includes:**
1. **Total Rides by Day of Week** - Stacked bar chart (Member vs Casual)
2. **Average Ride Length by User Type** - Comparative bar chart
3. **Total Rides Distribution** - Pie chart (Member vs Casual split)
4. **Day-wise Trend Analysis** - Rides throughout the week
5. **Member vs Casual by Day** - Grouped bar chart showing daily patterns

Dashboard published and embedded for interactive exploration.

## 💻 Technologies Used
- **Python** - Data cleaning, processing, analysis (Pandas, NumPy)
- **Jupyter Notebook** - Analysis documentation and reproducibility
- **Tableau** - Professional dashboard & visualization
- **Libraries**: Pandas, NumPy for data manipulation

## 🎯 Business Recommendations

### For Marketing Team
1. **Target Casual Users with Weekend Promotions**
   - Weekend-specific membership discounts
   - Longer ride duration packages

2. **Develop Weekday Membership Benefits**
   - Commuter-focused membership plans
   - Quick-trip incentives for members

3. **Seasonal Campaign Strategy**
   - Q1 data shows seasonal patterns
   - Design campaigns based on quarterly trends

4. **Geographic Targeting**
   - Popular stations for casual vs members differ
   - Station-specific marketing campaigns

## 📁 Project Structure

Cyclistic-Bike-Share-Analysis/
├── Code.ipynb # Python analysis & data cleaning
├── Dashboard.png # Tableau dashboard screenshot
├── report.docx # Detailed findings report
├── .gitignore # Exclude large CSV files
└── README.md # Project documentation


## 📈 Methodology

**Data Processing Pipeline:**
1. Load and merge datasets (2019 Q1 + 2020 Q1)
2. Standardize column names and data types
3. Calculate derived metrics (ride_length, day_of_week)
4. Remove invalid records
5. Aggregate and analyze by user type and day
6. Create visualizations and dashboards

## 🚀 Key Insights for Business Strategy

- **Member Profile**: Weekday commuters, consistent usage, shorter rides
- **Casual Profile**: Weekend explorers, longer average rides, leisure-focused
- **Opportunity**: Convert casual weekend users to full members
- **Data**: Supports targeted, data-driven marketing approach

## 👤 Author
**Muhammad Farooq Adnan Khan**  
Data Science Student | GIFT University  
Portfolio Project: Bike-Share User Behavior Analysis

---

**Project Status**: ✅ Complete  
**Last Updated**: October 2026  
**Dashboard**: Published & Interactive
