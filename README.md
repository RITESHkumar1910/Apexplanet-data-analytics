# Apexplanet-data-analytics

##  Task 1 - Foundation & EDA

### What I Did:
**Day 1-2: Environment Setup**
- Installed Python, VS Code, Jupyter Notebook
- Created GitHub repository with proper folder structure
- Installed libraries: pandas, numpy, matplotlib, seaborn

**Day 3-4: Data Cleaning**
- Loaded Superstore dataset (9994 rows, 21 columns)
- Checked and handled missing values (0 missing found)
- Removed duplicate entries
- Fixed date columns (Order Date, Ship Date) to datetime format
- Handled outliers in Sales column using IQR method

**Day 5-6: Exploratory Data Analysis**
- Generated statistical summary of all columns
- Created 4 visualizations:
  - Sales Distribution Histogram
  - Sales by Category Bar Chart
  - Sales by Region Bar Chart
  - Monthly Sales Trend Line Chart
- Created Correlation Heatmap
- Documented 5 key business insights

###  Key Insights Found:
1. **Total Sales:** $2,297,200.86
2. **Top Category:** Technology (highest revenue)
3. **Top Region:** West (best performing region)
4. **Avg Discount:** 15.62% across all orders
5. **Total Profit:** $286,397.02

###  Visualizations Created:
- `EDA_graphs.png` - 4 subplots (distribution, category, region, trend)
- `eda_plots.png` - Correlation between Sales, Profit, Discount, Quantity

###  Libraries Used:
python
import pandas as pd        
import numpy as np         
import matplotlib.pyplot   
import seaborn as sns      