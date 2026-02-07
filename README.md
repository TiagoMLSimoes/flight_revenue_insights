# flight_revenue_insights

# ✈️ Airline Pricing Strategy: Exploratory Data Analysis
**An investigation into ticket price drivers using Python and Seaborn.**

## 📌 Project Overview
This project analyzes a dataset of over 120,000 flight records to uncover how different factors influence airline ticket prices. By performing Exploratory Data Analysis (EDA), I identified key trends in seating tiers, timing, and passenger amenities to provide actionable insights for travel agencies and budget-conscious travelers.

## 🚀 Key Business Insights
* **The Weekend Premium:** Weekend travel shows a consistent price surge. I quantified the "gap" between weekday and weekend flights to identify optimal booking windows.
* **Amenity Impact:** Analysis revealed that while inflight meals are often "price-neutral," features like **Inflight Wi-Fi** and **Entertainment** are primary indicators of premium pricing tiers.
* **Redeye Efficiency:** Overnight flights offer a reliable discount across all days of the week, though the "Weekend Effect" remains the dominant price driver.

## 🛠️ Technical Skills Demonstrated
* **Data Cleaning & Sampling:** Handled a large dataset (120k+ rows) by utilizing strategic random sampling (`flight_sub`) to maintain performance and visual clarity.
* **Multivariate Visualization:** * Used `sns.lmplot` with `hue` to compare regression trends between different groups.
    * Applied **Jittering** and **Alpha Blending** to scatter plots to reveal data density and avoid overplotting.
    * Created grouped **Box Plots** to analyze price distributions across categorical variables.
* **Reproducible Research:** Established a clean project structure with a `requirements.txt` and clear Markdown documentation.

## 📊 Featured Visualizations

### 1. Pricing Trends: Weekends vs. Weekdays

*This chart shows the distinct "lift" in First-Class pricing relative to Coach prices during weekend travel.*

### 2. The Redeye Discount Distribution

*A visualization of how overnight flights consistently underprice daytime flights across a 7-day schedule.*

## 📂 Repository Structure
* `airline_analysis.ipynb`: The primary Jupyter Notebook containing all code and visualizations.
* `requirements.txt`: List of dependencies (Pandas, Seaborn, Matplotlib).
* `images/`: Exported high-resolution plots for reporting.

---
**Author:** [Your Name]
**LinkedIn:** [Your Link Here]
