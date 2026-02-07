# ✈️ Airline Pricing Strategy & Customer Behavior Analysis

## 📌 Project Overview
This project performs an in-depth exploratory data analysis (EDA) on a dataset of over 120,000 flight records. The goal is to identify pricing trends and the impact of various features (amenities, timing, and flight duration) to provide actionable insights for a travel agency.

## 📊 Key Business Questions Answered
* **What is the "Weekend Premium"?** Identifying how much more customers pay for Saturday/Sunday travel.
* **Are Amenities Worth It?** Quantifying the price increase associated with Wi-Fi, meals, and entertainment.
* **Redeye Savings:** Determining if overnight flights offer a consistent discount across different days of the week.
* **Pricing Correlation:** Analyzing the relationship between Coach and First-Class ticket tiers.

## 🛠️ Tech Stack & Skills
* **Python:** Core data processing.
* **Pandas:** Data cleaning and subsetting for performance.
* **Seaborn & Matplotlib:** Advanced data visualization, including:
    * **Jittering & Alpha Blending** to handle high-density data (Overplotting).
    * **Multivariate Box Plots** for temporal analysis.
    * **Regression Modeling** (`lmplot`) to visualize pricing correlations.

## 📈 Featured Visualizations

### 1. The Redeye Discount (Multivariate Analysis)

Using categorical color encoding, we identified that while Redeye flights are cheaper, the "Weekend Effect" is a more powerful driver of price than the time of day.

### 2. Feature Value Analysis

A comparative study of amenities showed that while meals are often bundled into the base price, Wi-Fi is a significant indicator of a premium price bracket.

## 💡 Top 3 Insights for Stakeholders
1. **Strategic Booking:** The "upgrade gap" between Coach and First-Class is narrowest on Tuesdays and Wednesdays, offering the best value for luxury travelers.
2. **Amenity Optimization:** Travelers looking for the absolute lowest fare should specifically filter for flights without Wi-Fi, as these show the most significant price separation from the mean.
3. **Operational Consistency:** Despite variations in flight length (1-8 hours), passenger volume remains stable, suggesting consistent aircraft utilization across the fleet.

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have `pandas`, `seaborn`, and `matplotlib` installed.
3. Open `flight_revenue_insights.ipynb` in Jupyter Notebook or VS Code.

4. ### 🚀 Future Improvements & Next Steps
If given more time or data, I would expand this project in the following ways:
* **Predictive Modeling:** Use the features identified in this EDA (weekend status, amenities, redeye) to build a Linear Regression model that predicts ticket prices with an estimated margin of error.
* **Geographic Analysis:** Incorporate origin and destination data to see if certain "hubs" have higher premiums regardless of amenities.
* **Time-Series Forecasting:** Analyze seasonality by looking at data across months (Summer vs. Winter) to identify the best time of year to book.
