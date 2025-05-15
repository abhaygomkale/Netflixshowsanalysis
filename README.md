# 📊 Netflix Data Analysis with Python

Welcome to **Netflix Data Analysis**, a project that explores Netflix’s dataset to extract meaningful insights about movies, directors, content trends, and country distribution using Python libraries like **Pandas** and **Matplotlib**. The notebook performs cleaning, transformation, and visualization — ideal for beginner to intermediate data analysts building their portfolios.

---

## 🔍 Project Overview

In this project, I cleaned and analyzed a Netflix dataset to answer questions such as:

* Which countries produce the most Netflix content?
* Who are the top 15 directors on Netflix?
* What is the distribution of content by type and rating?
* How does the release year of content trend over time?

Visualizations were created using **Matplotlib**, and the dataset was transformed using **Pandas** to allow deeper insights and professional presentation.

---

## 📦 Dataset Details

* **Source**: Netflix Titles Dataset (available from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows))
* **Format**: CSV
* **Attributes Used**:

  * `title`, `director`, `country`, `release_year`, `rating`, `duration`, `type`, etc.

---

## 📚 Libraries and Tools Used

| Tool         | Purpose                           |
| ------------ | --------------------------------- |
| `pandas`     | Data manipulation and cleaning    |
| `matplotlib` | Data visualization                |
| `numpy`      | Numerical operations              |
| `Jupyter`    | Code development and presentation |

Install all packages with:

```bash
pip install -r requirements.txt
```

---

## 🧹 Data Cleaning Performed

* Removed missing and duplicate values
* Standardized column names (e.g., `release_year` as integer)
* Split multiple countries/directors for frequency count
* Converted `duration` and `rating` into clean numeric/categorical fields

---

## 📊 Visualizations

### 1. 🎬 Top 15 Directors by Number of Works

Shows directors with the most contributions to Netflix.

![Top Directors]("C:\Users\om\Desktop\15topdirectbar.png")

---

### 2. 🌍 Countries with Most Movie Count

Bar chart showing the countries that produced the most Netflix content.

![Country-wise Movie Count]("C:\Users\om\Desktop\countmpviebar.jpg")



---

## 📂 Folder Structure

```
Netflix-Analysis/
│
├── Netflixanalysis.ipynb       # Complete analysis in Jupyter Notebook
├── images/                     # Plots and graphs
│   ├── 15topdirectbar.png
│   └── movie_country_barh.png
├── dataset.csv                 # Netflix dataset (optional - follow license)
├── README.md                   # This file
└── requirements.txt            # Python dependencies
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Netflix-Data-Analysis.git
   cd Netflix-Data-Analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Netflixanalysis.ipynb
   ```

4. Run all cells to see the full analysis and charts.

---

## 💡 Insights You’ll Gain

* How to clean and preprocess real-world data
* How to use `groupby`, `value_counts`, and `apply` in Pandas
* How to build meaningful plots (bar, horizontal bar, etc.)
* How to prepare a notebook for GitHub portfolio use

---

## 👤 Author

**Abhay Gomkale**
📍 Jhulelal Institute of Technology, Computer Science
🔭 Aspiring Data Analyst | Python & SQL Enthusiast
📧 abhaygomkale0@gmail.com

---

## 🌟 Support

If you found this project helpful:

* ⭐ Star this repository
* 🍴 Fork it
* 🗣️ Share it with friends
* 📝 Connect on LinkedIn or GitHub

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share it.
