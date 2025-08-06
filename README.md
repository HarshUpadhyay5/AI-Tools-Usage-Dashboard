# 📊 AI Tools Usage Dashboard

An interactive Excel dashboard project analyzing student behavior, preferences, and institutional acceptance of modern AI tools like ChatGPT, Bard, Copilot, and Gemini. This project walks through a full end-to-end data analytics pipeline — from raw survey data to actionable visual insights.

---

## 🎯 Objective

To explore how students across different regions and digital accessibility levels are using AI tools in academics — focusing on tool awareness, daily usage, academic impact, and institutional restrictions.

---

## 🧩 Project Workflow

This project reflects a real-world analytics workflow involving data cleaning, transformation, and visualization:

1. **Data Cleaning in SQL Server**
   - Minor cleaning of two raw survey datasets using **MS SQL Server**.
   - Verified consistency, removed obvious duplicates, and standardized formats.

2. **Transformation with Power Query**
   - Imported cleaned datasets into **Power Query**.
   - Replaced/remedied null and blank values.
   - Renamed and reshaped data variables for clarity.
   - Applied filters to remove incomplete rows.
   - Appended both datasets into one consolidated dataset.

3. **Data Modeling & Visualization**
   - Built a dynamic dashboard using **Pivot Tables**, slicers, and Excel formulas.
   - Designed intuitive visuals to highlight KPIs like usage, popularity, and professor permissions.

---

## 📈 Key KPIs & Visuals

The dashboard includes the following visual and analytical components:

- 📊 **Average Daily Usage** per AI tool
- 📌 **Awareness Levels** shown via radar/spider chart
- 🥇 **Most Popular Tools** across demographics
- 🎓 **Impact on Grades** comparison
- 🚫 **Professors’ Restrictions** against tools
- 🧮 Dynamic filters by:
  - State
  - Internet Access Level
  - Device Used (Mobile / Laptop / Tablet)

---

## 🌟 Results & Insights

- **ChatGPT** emerged as the most used and most well-known tool.
- Tools like **Gemini** and **Copilot** have niche but rising popularity.
- Students reported **positive grade impact** from responsible tool usage.
- Significant variance was observed in **institutional policies** — some professors allow tool usage, others strongly discourage it.
- Mobile users showed lower tool awareness than laptop users — highlighting a possible digital divide.

---

## ⚙️ Tech Stack

- **MS SQL Server** – Initial cleaning and filtering of survey data.
- **Microsoft Excel** – Dashboard creation with PivotTables, slicers, formulas.
- **Power Query Editor** – Data transformation and consolidation.

---

## 📁 Repository Structure



- `datasets.zip`: Contains original cleaned CSVs (2 files)
- `AI_Tools_Usage_Dashboard.xlsx`: Final Excel dashboard
- `dashboard_screenshot.png`: Preview image of dashboard
- `README.md`: Project documentation


---

## 📬 Contact

For questions, collaboration, or feedback, feel free to reach out:

- [GitHub](https://github.com/HarshUpadhyay5)

---

⭐ If you found this project useful, feel free to **star this repo** or leave feedback!
