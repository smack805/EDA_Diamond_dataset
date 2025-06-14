# EDA_Diamond_dataset                     
# 💎 Diamonds Dataset EDA

This project performs an **Exploratory Data Analysis (EDA)** on the **Diamonds dataset** available in the `seaborn` library. The goal is to understand the features that influence the price of diamonds through univariate, bivariate, and multivariate visualizations.

---

## 📂 Dataset Information

The Diamonds dataset contains the prices and other attributes of **53,940** round-cut diamonds. It is commonly used for regression and classification practice and is included with the seaborn Python package.

### 📌 Source

- Loaded via `sns.load_dataset('diamonds')`
- Originally from [ggplot2 in R](https://ggplot2.tidyverse.org/reference/diamonds.html)

---

## 🧾 Column Descriptions

| Column   | Data Type | Description |
|----------|-----------|-------------|
| `carat`  | float     | Weight of the diamond (0.2–5.01 carats) |
| `cut`    | category  | Quality of the cut: *Fair*, *Good*, *Very Good*, *Premium*, *Ideal* |
| `color`  | category  | Diamond color, from *J* (worst) to *D* (best) |
| `clarity`| category  | A measurement of how clear the diamond is. Ranges from *I1* (worst) to *IF* (best) |
| `depth`  | float     | Total depth percentage = z / mean(x, y) = 2 * z / (x + y) |
| `table`  | float     | Width of the top of the diamond relative to the widest point |
| `price`  | int       | Price in US dollars (ranging from $326 to $18,823) |
| `x`      | float     | Length in mm |
| `y`      | float     | Width in mm |
| `z`      | float     | Depth in mm |

---

## 🔍 Key Characteristics

- **No missing values** in the dataset.
- Combination of **categorical and numerical features**.
- Strong correlation found between **carat** and **price**.
- Useful for regression tasks like **price prediction** based on physical and quality attributes.

---

## 📊 Use Cases

- Price prediction based on diamond attributes
- Outlier detection and handling
- Feature engineering and selection
- Data visualization and storytelling
- Supervised machine learning tasks

---

## 📌 License & Credits

- Dataset originally from **ggplot2** (R package) maintained by **Hadley Wickham**.
- Available under the MIT license.

---

