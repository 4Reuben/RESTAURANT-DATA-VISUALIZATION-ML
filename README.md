# 🌍 RESTAURANT-DATA-VISUALIZATION-ML-PROJECT

🙋‍♂️ **Author**
Reuben Thomas John

Intern @ Cognifyz Technologies

📅 **Project Duration:** 4 Weeks

---

## 🧠 TASK - 3: Restaurant Data Analysis & Visualization

This project focuses on the **visual exploration and geographic distribution** of restaurants using real-world data. With the help of **interactive maps, bar plots, and scatter plots**, it highlights trends based on **location, ratings, pricing, and cuisines**. The aim is to deliver actionable insights for users and businesses through data-driven visual storytelling.

---

## 📌 Objective

To explore and visualize restaurant data using **Pandas**, **Folium**, and **Plotly**, and derive insights on:

* Top cities/localities with most restaurants
* Areas with highest average ratings
* Distribution of restaurants across the globe
* Common cuisines and price trends

---

## 🧾 Dataset Overview

* 📂 **Total Records:** 9,551

* 🏷️ **Columns:** 21

* 📊 **Sample Features:**

  * Restaurant Name
  * City, Locality
  * Latitude & Longitude
  * Cuisines
  * Price Range
  * Aggregate Rating
  * Votes
  * Delivery and Table Booking availability

* 🧹 **Preprocessing**:

  * Missing coordinates dropped
  * Column names cleaned (stripped of extra spaces)
  * Missing values handled using standard techniques
  * City and Locality grouped for analysis

---

## 🛠️ Technologies & Tools Used

* Python
* Google Colab
* Pandas, NumPy
* Seaborn, Matplotlib
* Folium, Plotly

---

## 🔍 Visualizations & Insights

### 🗺️ 1. Interactive World Map with Restaurant Clusters

* Created using **Folium + MarkerCluster**
* Displays restaurant locations with **name and rating** in popups
* Zoomable to explore restaurants across cities/countries
* World view set to zoom level 2

### 📊 2. Top 10 Cities by Restaurant Count

* Bar graph showing cities with the most listed restaurants
* Useful for market targeting and competitive analysis

### ⭐ 3. Top Areas by Average Rating

* Average ratings per city/locality displayed using a bar chart
* Shows where customer satisfaction is highest

### 🌐 4. Global Scatter Plot of Restaurants by Rating

* Created using **Plotly's scatter\_mapbox**
* Visualizes geographic distribution with color-coded ratings
* Fully interactive for zoom, pan, and hover details

---

## ✨ Sample Output

```text
Top 10 Cities by Restaurant Count:
    City           restaurant_count
    New Delhi        5473
    Gurgaon          1118
    Noida            1080
    Faridabad         251
    Ghaziabad          25
    Bhubaneshwar       21
    Lucknow            21
    Guwahati           21
    Ahmedabad          21
    Amritsar           21
```

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install pandas numpy folium plotly matplotlib seaborn
```

---

## 🚀 How to Run

1. 📂 Upload the dataset to your Google Drive
2. 🔗 Mount Google Drive in Colab
3. ▶️ Run all cells in order
4. 📌 Zoom in on **Folium map** to view restaurant clusters
5. 📈 Explore graphs and plots for insights

---

## ✅ Future Improvements

* Add filters by **cuisine, city, or rating** in map interactivity
* Generate **PDF reports** of key findings
* Integrate with **real-time data APIs** (e.g., Zomato or Yelp)
* Build an interactive **dashboard** using Dash or Streamlit

---

## 🏁 Conclusion

This project showcases the power of **visual analytics in the restaurant industry**, allowing us to explore trends, identify top-performing cities, and understand customer preferences. Interactive maps and visuals make the insights accessible to both data scientists and business stakeholders.
