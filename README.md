
# A/B Testing Using Python

A/B Testing means analyzing two marketing strategies to choose the best marketing strategy that can convert more traffic into sales 
(or more traffic into your desired goal) effectively and efficiently.
A/B testing is one of the valuable concepts that every Data Science professional should know.

## Overview
This project demonstrates A/B testing using Python to compare the effectiveness of two marketing campaigns: the Control Campaign and the Test Campaign. The dataset contains key performance metrics such as impressions, reach, website clicks, searches, content viewed, items added to the cart, and purchases. The goal is to analyze and determine which campaign is more effective based on various engagement and conversion metrics.

## Dataset
The dataset consists of two CSV files:
- **control_group.csv**: Data for the control campaign
- **test_group.csv**: Data for the test campaign

Each dataset contains the following columns:
- `Campaign Name`: Name of the campaign (Control or Test)
- `Date`: Date of the campaign activity
- `Spend [USD]`: Amount spent on the campaign
- `# of Impressions`: Number of times the ad was displayed
- `Reach`: Number of unique users who saw the ad
- `# of Website Clicks`: Number of clicks on the ad
- `# of Searches`: Number of searches performed on the website
- `# of View Content`: Number of times content was viewed
- `# of Add to Cart`: Number of items added to the cart
- `# of Purchase`: Number of successful purchases

## Data Preparation
- Renamed columns for consistency.
- Checked for missing values and imputed missing values using the mean.
- Merged both datasets into a single dataset for comparative analysis.
- Verified that both campaigns have an equal number of samples.

## A/B Testing Analysis
1. **Impressions vs. Amount Spent**
   - The control campaign generated more impressions for the same amount spent.
2. **Website Searches**
   - The test campaign led to a higher number of searches on the website.
3. **Website Clicks**
   - The test campaign resulted in more website clicks.
4. **Content Viewed**
   - The control campaign audience engaged more with the website content.
5. **Items Added to Cart**
   - Despite fewer website clicks, more products were added to the cart from the control campaign.
6. **Total Amount Spent**
   - The test campaign had a higher total spend compared to the control campaign.
7. **Total Purchases**
   - The control campaign led to a higher number of total purchases.

## Metrics Analysis
- **Website Clicks vs. Content Viewed**: Engagement from website clicks was higher in the control campaign.
- **Content Viewed vs. Items Added to Cart**: More content views led to more items in the cart for the control campaign.
- **Items Added to Cart vs. Purchases**: The test campaign had a higher conversion rate from cart to purchase.

## Conclusion
- The **Control Campaign** resulted in **more total sales** and higher overall engagement.
- The **Test Campaign** had a **higher conversion rate**, making it suitable for targeting specific products and audiences.
- The control campaign is more effective for **broad marketing efforts**, while the test campaign is better suited for **focused promotions**.

## Tools Used
- **Python**
- **Pandas** for data manipulation
- **Plotly** for data visualization

## How to Run the Analysis
1. Install the required Python libraries:
   ```bash
   pip install pandas plotly
   ```
2. Run the Jupyter Notebook `AB Testing using Python.ipynb` to execute the analysis and visualize results.


