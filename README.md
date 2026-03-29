# 🥗 Healthy Meal Insights Dashboard — Power BI Project

A complete nutrition and meal analytics project built using **Microsoft Power BI** and **Excel**. The project involves exploring meal data across diet types, cuisines, and nutritional profiles, writing DAX measures, and designing an interactive dashboard to help health enthusiasts, dietitians, and food analysts uncover patterns in calorie distribution, macronutrients, and meal healthiness.

---

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-6B4FBB?style=for-the-badge&logo=microsoftpowerbi&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📁 Project Structure

```
Healthy-Meal-Insights-Dashboard/
│
├── Healthy_Meal_Insights_Dataset.xlsx    # Meal nutrition dataset (600 records)
├── Healthy_Meal_Insights_Dashboard.pbix  # Power BI dashboard file
└── README.md                             # Project documentation
```

---

## 📊 Dataset Overview

The dataset contains **600 meal records** with **16 columns** including:

| Column | Description |
|--------|-------------|
| Meal ID | Unique meal identifier |
| Meal Name | Name of the dish |
| Diet Type | Vegan / Vegetarian / Keto / Paleo / Mediterranean / Balanced / Low-Carb |
| Cuisine | Indian / Italian / Japanese / Mexican / Chinese / Thai / Greek |
| Calories | Total calories per serving (kcal) |
| Protein (g) | Protein content in grams |
| Carbs (g) | Carbohydrate content in grams |
| Fat (g) | Total fat content in grams |
| Fiber (g) | Dietary fiber in grams |
| Sugar (g) | Sugar content in grams |
| Cholesterol (mg) | Cholesterol in milligrams |
| Serving Size (g) | Serving size in grams |
| Prep Time (min) | Preparation time in minutes |
| Rating | User rating on a scale of 2.5–5.0 |
| Is Healthy | 1 = Healthy · 0 = Not Healthy (rule-based classification) |
| Allergens | Gluten / Dairy / Nuts / Soy / Eggs / None |

---

## 📈 Dashboard Visuals

The dashboard includes **9 interactive visuals** on a single-page layout:

| Visual | Description |
|--------|-------------|
| **KPI Card — Healthy Meals Count** | Total number of meals classified as healthy |
| **KPI Card — Average Rating** | Overall average user rating across all meals |
| **KPI Card — Total Calories Tracked** | Sum of all calories tracked across the dataset |
| **Clustered Column Chart** | Avg calories, protein, carbs & fat compared by diet type |
| **Line Chart** | Sugar vs fiber relationship across all meals |
| **Scatter Chart** | Preparation efficiency — rating vs prep time (sized by serving size) |
| **Clustered Column Chart** | Diet type and cuisine compatibility breakdown |
| **Pie Chart** | Healthy vs not-healthy meal share by rating |
| **Line Chart** | Average cholesterol levels compared by diet type |

---

## 🔍 Key Insights

- 🥦 **Vegan meals** score the highest on dietary fiber and lowest on cholesterol levels
- 🥩 **Keto and Paleo** diets have the highest fat content but the lowest carbohydrate levels
- 📉 There is a clear **negative correlation** between sugar and fiber content across all meals
- 🌍 **Mediterranean cuisine** has the highest proportion of healthy-rated meals overall
- ⏱️ Meals with **prep time under 20 minutes** do not significantly compromise nutritional quality
- 🏆 **Balanced diet** meals consistently achieve the highest average user ratings

---

## 🛠️ Tools & Features Used

- **Microsoft Power BI Desktop**
- **Microsoft Excel** — Data source & preparation
- **DAX (Data Analysis Expressions)** — Nutrition averages, health counts, custom measures
- **Power Query (M Language)** — Data cleaning, health classification logic & transformation
- **Data Modeling** — Column categorization and diet-type grouping
- KPI Cards, Line, Scatter, Pie & Clustered Column Charts, Slicers
- Interactive Dashboard with Diet Type cross-filtering

---

## 🚀 How to Use

1. Download both files (`Healthy_Meal_Insights_Dataset.xlsx` and the `.pbix` file)
2. Open `Healthy_Meal_Insights_Dashboard.pbix` in Power BI Desktop
3. If prompted, update the data source path to point to `Healthy_Meal_Insights_Dataset.xlsx`
4. Click **Refresh** to load the data
5. Use the **Diet Type slicer** to filter all charts by dietary preference
6. Hover over the **Scatter Chart** to explore individual meal-level nutritional details

---

## 👤 Author

> **[Your Name]**
>
> 🔗 [LinkedIn](https://www.linkedin.com/in/umarfaruk-shaikh/) | 🐙 [GitHub](https://github.com/Umarfaruk0123)

---

⭐ If you found this project helpful, give it a star!

