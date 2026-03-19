# 🎬 Netflix Dashboard – Power BI

An **interactive Power BI dashboard** built using Netflix titles data, combined with **Python-based data cleaning and exploratory analysis**.  
This project delivers **insightful visual analytics** across Movies and TV Shows to help understand trends, distribution, and content patterns.

---

## 🔍 Dashboard Features

### 🏠 **Home Page**

- 📊 **KPI Cards**
  - Total Shows
  - Total Directors
  - Total Genres
  - Total Locations
  - Year Range  

- 🌍 **World Map**
  - Displays total shows by country  

- 📊 **Visual Insights**
  - Bar Chart → Rating distribution  
  - Donut Chart → Movies vs TV Shows split  
    - **70.85% Movies / 29.15% TV Shows**
  - Line Chart → Content trend by release year  
  - Bar Chart → Genre-wise distribution  

- 🎛️ **Interactive Filters (Slicers)**
  - Genre  
  - Release Year Range  

---

### 🎬 **Movies Page**

- 📋 **Detailed Table View**
  - Title  
  - Genre  
  - Lead Actor  
  - Director  
  - Duration  
  - Release Year  
  - Rating  

- ⭐ **Top Insights**
  - **Top Director**
  - **Top Actor:** Shah Rukh Khan  
  - **Top Genre:** Dramas  

---

### 📺 **TV Shows Page**

- 📋 **Filterable Table**
  - Title  
  - Seasons  
  - Rating  

- ⭐ **Top Insights**
  - **Top Directors:** Alastair Fothergill, Raúl Campos & Jan Suter  
  - **Top Actor:** David Attenborough  
  - **Top Genre:** International TV Shows  

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|--------|
| **Power BI** | Dashboard & Data Visualization |
| **Python (Pandas)** | Data Cleaning & Preprocessing |
| **NumPy** | Numerical Computation |
| **Matplotlib / Seaborn** | Exploratory Data Analysis |
| **Jupyter Notebook** | Data Exploration |

---

## 🚀 Getting Started

### ✅ Prerequisites

- Power BI Desktop (Free)
- Python 3.x
- Jupyter Notebook / JupyterLab

---

### ⚙️ Setup Steps

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/netflix-dashboard.git
cd netflix-dashboard
2️⃣ Run Data Cleaning Notebook
jupyter notebook Netflix_dataCleaning.ipynb
3️⃣ Open Power BI Dashboard

Open dashboard.pbix in Power BI Desktop

Refresh dataset if prompted
