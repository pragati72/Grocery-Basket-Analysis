# Grocery-Basket-Analysis

This project performs **exploratory data analysis (EDA)** on a large-scale grocery transaction dataset from Instacart. The aim is to uncover simple, clear patterns in customer purchasing behavior using Python and Jupyter Notebook.

---

##  Dataset Overview

The dataset consists of real transactional data from an online grocery store. Due to GitHub’s 25MB file limit, the main data files are hosted externally via Google Drive.

### Download Links for Dataset (Google Drive):

| File Name                  | Description                             | Download Link |
|---------------------------|-----------------------------------------|----------------|
| `orders.csv`              | Order metadata (user, time, order ID)   | [Download](https://drive.google.com/file/d/1KHse29silmNmdAa-rEpJMWBgGbdT0wNh/view?usp=drive_link) |
| `order_products__prior.csv` | Product transactions per order        | [Download](https://drive.google.com/file/d/1mQk6Han42B1j4CIYb5W3gBzkX926ftVv/view?usp=sharing) |
| `products.csv`            | Product names and IDs                   | [Download](https://drive.google.com/file/d/1yt1Dh_qv63-88uFeUbRC6LcNNH4OTBqk/view?usp=drive_link) |
| `departments.csv`         | Product department categories           | [Download](https://drive.google.com/file/d/1tXa-gRvMakBJIiBz9JsOlCWNQFsIo9FU/view?usp=drive_link) |

>  Place all CSVs in the same folder as the Jupyter notebook after downloading.


## Technologies Used

- **Python**
- **Pandas** – data analysis
- **Matplotlib & Seaborn** – data visualization
- **WordCloud** – text-based plots
- **Jupyter Notebook** – project workflow

---

##  Key Insights Extracted

Here are some of the 25+ easy-to-understand insights included:

-  Top 10 most frequently ordered products
-  Most active users (by number of orders)
-  Distribution of basket sizes
-  Popular shopping days and hours
-  Frequently reordered items
-  Most popular product departments
-  Product pairs that appear together
-  Word cloud of top products
-  Reordered vs New purchases
-  Scatter and bar plots for trends


---

##  How to Run

1. Clone the repository or download the `.ipynb` notebook
2. Download all CSVs from the above Drive links
3. Place them in the same folder as the notebook
4. Open with Jupyter Notebook or VS Code
5. Run all cells (`Kernel > Restart & Run All`)

---

## Conclusion

The project demonstrates that customer shopping patterns can be analyzed easily using simple Python techniques. We can predict shopping trends such as:

- Most popular items
- When people shop the most
- Which items are often reordered
- Which products are commonly bought together

These insights help retailers design better offers, bundles, and recommendations.
