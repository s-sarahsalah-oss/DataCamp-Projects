# DataCamp-Projects
# Exploring Public School Test Result Scores 
[Exploring Public School Test Result Scores 📊](Exploring%20NYC%20Public%20School%20Test%20Result%20Scores/notebook.ipynb)

## Key Findings & Results

Based on the analysis of the New York City public school SAT performance dataset (`schools.csv`), here are the insights discovered:

### 1. Best Math Schools
The schools with the highest average math scores (where the average score is 640 or above), sorted from highest to lowest, are:

* **Stuyvesant High School** (Average Math: 754)
* **Bronx High School of Science** (Average Math: 714)
* **Staten Island Technical High School** (Average Math: 711)
* **Queens High School for the Sciences at York College** (Average Math: 701)
* **High School for Mathematics, Science, and Engineering at City College** (Average Math: 683)
* **Brooklyn Technical High School** (Average Math: 682)
* **Townsend Harris High School** (Average Math: 680)
* **High School of American Studies at Lehman College** (Average Math: 669)
* **New Explorations into Science, Technology and Math High School** (Average Math: 657)
* **Eleanor Roosevelt High School** (Average Math: 641)

---

### 2. Top 10 Performing Schools (Total SAT Scores)
By combining the average scores of all three sections (Reading, Writing, and Math), the top 10 public schools in NYC based on the total SAT scores are:

| Rank | School Name | Total SAT Score |
| :---: | :--- | :---: |
| 1 | Stuyvesant High School | 2144 |
| 2 | Bronx High School of Science | 2041 |
| 3 | Staten Island Technical High School | 2041 |
| 4 | High School of American Studies at Lehman College | 2013 |
| 5 | Townsend Harris High School | 1981 |
| 6 | Queens High School for the Sciences at York College | 1947 |
| 7 | Bard High School Early College | 1914 |
| 8 | Brooklyn Technical High School | 1896 |
| 9 | Eleanor Roosevelt High School | 1889 |
| 10 | High School for Mathematics, Science, and Engineering at City College | 1889 |

---

### 3. Borough with the Largest SAT Score Variation
When analyzing the performance variation across different NYC boroughs, **Manhattan** was found to have the highest standard deviation in total SAT scores. This indicates a significant disparity in performance among schools within this borough.

* **Borough:** Manhattan
* **Number of Schools:** 89
* **Average SAT Score:** 1340.13
* **Standard Deviation:** 230.29

# Data-Driven Product Management Conducting a Market Analysis 
[Data-Driven Product Management Conducting a Market Analysis  📊](Data-Driven%20Product%20Management%20Conducting%20a%20Market%20Analysis/notebook.ipynb)
This project analyzes a full year of electronics store sales data across multiple cities in the US to answer key business performance questions.

### 1. Best Month for Sales
* **The Best Month:** **December** was the top-performing month for sales, generating approximately **$4.61 million** in revenue.
* **The Lowest Month:** **January** had the lowest sales, with around **$1.82 million**.
* **Insight:** The massive spike in December is highly driven by holiday shopping and end-of-year gifting.

---

### 2. Top-Selling City
The city that generated the highest revenue by a significant margin is **San Francisco, CA**, followed by Los Angeles and New York City.

| Rank | City | Total Sales (USD) |
| :---: | :--- | :---: |
| 1 | San Francisco (CA) | ~$8.26M |
| 2 | Los Angeles (CA) | ~$5.45M |
| 3 | New York City (NY) | ~$4.66M |
| 4 | Boston (MA) | ~$3.66M |
| 5 | Atlanta (GA) | ~$2.80M |

---

### 3. Optimal Advertisement Timing
By analyzing the distribution of orders throughout the day, the data shows two distinct peak hours for customer purchases:
* **Primary Peak:** **11:00 AM – 12:00 PM** (Lunch hour shopping)
* **Secondary Peak:** **7:00 PM – 8:00 PM** (After-work evening shopping)

> 💡 **Recommendation:** Advertisements and promotional campaigns should be scheduled right before these peak hours (around **10:30 AM** and **6:30 PM**) to maximize visibility and conversion rates.

---

### 4. Most Frequently Bought Together Products
Using market basket analysis (identifying products frequently appearing in the same Order ID), the most common product combinations are:
1. **iPhone** and **Lightning Charging Cable** (Most common pair)
2. **Google Pixel** and **USB-C Charging Cable**
3. **iPhone** and **Wired Headphones**

---

### 5. Best-Selling Products (Volume vs. Price)
* **Most Sold Item:** **AAA Batteries (4-pack)** and **AA Batteries (4-pack)** were the top items sold by quantity.
* **Correlation:** There is a clear negative correlation between price and quantity ordered—high-volume items are cheap household essentials (batteries, cables), whereas high-revenue but low-volume items are premium electronics (MacBook Pro, iPhones).