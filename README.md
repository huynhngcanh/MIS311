**1.Data Overview**
   
**Dataset name:** “Shoe Price”

**Source:** Provided as part of the MIS311 – Basic Statistics in Business Analytics course materials.

**Description:** The dataset contains information about different shoe products, including brand, category, gender, size, and price.

**Number of rows and columns:** The dataset includes approximately 200 rows and 5 columns.

**Background:** The dataset represents a small sample of shoe products from various local and international brands. It is used to analyze pricing patterns, evaluate how brand and category influence price levels, and understand overall market variability in shoe prices

**2.Data Cleaning**

<img width="1336" height="286" alt="image" src="https://github.com/user-attachments/assets/2cc48cc5-1165-475a-ac4d-487293188910" />

The dataset originally had **two missing values** including one in Color and one in Price.

The missing Color was filled with **“Black”**, the most frequent color.

→ This keeps the dataset consistent but does **not affect the price analysis**, since Color is not a variable used in statistics.

The missing Price was replaced with the **average price** of all shoes.

→ This prevents the missing data from **reducing the dataset size** and helps maintain the overall mean.

No duplicate rows were found: After cleaning, the dataset is **complete and accurate**, and the adjustments made have **minimal impact on the final analysis results.**

**3. Descriptive Statistics**

The analysis focused on both **numerical data (Price)** and **categorical data (Color)** to identify meaningful insights.

***Key Insight 1: Shoe Color Distribution**

<img width="794" height="682" alt="image" src="https://github.com/user-attachments/assets/6b9ce545-7ecc-4f25-bb88-45fdea819172" />

The bar chart shows that **Black** is the most common shoe color **(49 pairs)**, followed by **Brown (35)** and **Blue (24).**
This suggests that **neutral** and **classic tones** are preferred by customers, likely because they are **easy to match and suitable for daily wear.**

 =>The bar chart is appropriate for this categorical variable because it clearly shows **the frequency of each color** and allows quick comparison between color groups.

***Key Insight 2: Shoe Price Summary**

<img width="552" height="588" alt="image" src="https://github.com/user-attachments/assets/4cce7601-798e-40bc-8c0f-8e8642295c5c" />

The average shoe price is about **$213**, with **a median of $211** and **a standard deviation of 79.**
This indicates **moderate variability**, meaning most shoe prices are close to the average and there are **no extreme outliers.**

=> The histogram is appropriate for this numerical variable because it effectively displays **the distribution, central tendency, and variation of shoe prices in the dataset.**
