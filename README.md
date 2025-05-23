# 💻 Laptop Dataset Analysis

This project focuses on analyzing a comprehensive laptop dataset to uncover key insights into laptop specifications, performance, and pricing. The analysis serves both consumers and manufacturers by helping them understand trends, preferences, and strategic opportunities in the laptop market.

---

## 📂 Dataset Overview

The dataset includes various attributes related to laptops such as brand, technical specifications, and pricing details. Each record in the dataset represents a unique laptop model with the following features:

| Feature           | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Company`         | Manufacturer or brand of the laptop                                         |
| `TypeName`        | Type/category (e.g., Gaming, Ultrabook)                                     |
| `Inches`          | Screen size in inches                                                       |
| `ScreenResolution`| Resolution and display technology                                           |
| `Cpu`             | Processor (CPU) model                                                       |
| `Ram`             | RAM size                                                                    |
| `Memory`          | Storage capacity (HDD/SSD)                                                  |
| `Gpu`             | Graphics processor (GPU) model                                              |
| `OpSys`           | Operating system                                                            |
| `Weight`          | Weight in kilograms                                                         |
| `Price`           | Price in local currency                                                     |

---

## ✅ Project Objectives

1. **Data Cleaning & Preprocessing**
   - Handle missing values using imputation/removal.
   - Fix inconsistencies (e.g., typos, irregular formatting).

2. **Exploratory Data Analysis (EDA)**
   - **Univariate Analysis**: Distribution of individual variables.
   - **Bivariate Analysis**: Relationships like `Price vs RAM`, `Weight vs Screen Size`.
   - **Multivariate Analysis**: Interactions and dependencies among features.

3. **Data Visualization**
   - Generate histograms, box plots, scatter plots, and heatmaps.
   - Visualize trends, brand preferences, and market dynamics.

4. **Feature Engineering**
   - Extract new features like brand reputation or processor generation.
   - Apply dimensionality reduction (if required).

5. **Analysis & Interpretation**
   - Identify key drivers of pricing and performance.
   - Spot market trends and customer preferences.
   - Provide actionable insights for manufacturers and marketers.

6. **Documentation**
   - Clear documentation of each step: cleaning, EDA, visualization, and insights.
   - Designed to be accessible to both technical and non-technical audiences.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Markdown / Word for documentation
- GitHub for version control

---

## 📊 Example Visualizations

- 💸 **Price distribution by brand**
- ⚙️ **Price vs RAM/CPU/GPU**
- 🖥️ **Screen size vs Weight**
- 🔍 **Correlation heatmap for numerical features**

---

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/laptop-analysis.git
   cd laptop-analysis
