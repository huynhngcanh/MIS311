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

The chart shows that **Black (49 pairs), Brown (35 pairs), and Blue (24 pairs)** are the three most common shoe colors in the dataset.

These colors are **neutral and classic**, making them highly versatile and appealing to a wide range of customers.

Because of their popularity, brands tend to **produce these colors in larger quantities**, using them as **core products** to maintain stable sales volume.

When compared with the price data, these popular colors generally have **average or slightly lower prices** than rare colors like **Silver, Red, or Navy & Red**, which appear in smaller numbers.

This suggests **a negative relationship between color frequency and price** as a color becomes more common, it is often priced lower to remain competitive in the mass market, while limited or unique colors can be priced higher to emphasize exclusivity and brand differentiation.

This relationship is meaningful because it helps companies **balance between volume and profit:**

- Popular colors (e.g., Black, Brown) → used to drive sales volume with affordable pricing.

- Rare colors (e.g., Red, Silver) → positioned as premium items with higher prices and lower stock.

Such insights are valuable for **Marketing, Merchandising, and Product Managers,**

who can use this analysis to:

* Plan **inventory and color mix** based on customer demand trends.
* Adjust **pricing strategies** by product color.
* Design **marketing campaigns** that align with customer preferences (e.g., neutrals for everyday wear, bright tones for limited editions).
  
The bar chart is appropriate for this categorical variable (Color) because it clearly displays the frequency of each color, making it easy to identify which colors dominate the dataset and how they may influence pricing and consumer behavior.

**I chose this insight because it shows a clear connection between color popularity and pricing strategy. Neutral tones like black and brown are priced to sell in large volumes, while rare colors are priced higher for exclusivity. This helps brands decide how to balance production, pricing, and marketing focus for different customer segments.**

***Key Insight 2: Shoe Price Summary**

<img width="552" height="588" alt="image" src="https://github.com/user-attachments/assets/4cce7601-798e-40bc-8c0f-8e8642295c5c" />

The analysis shows that the average shoe price is **about $213**, with a **median of $211** and a **standard deviation of around 79.**

This means that **most shoes are priced around the same level,** and there are **no big price gaps** in the dataset.

The **minimum price ($80)** and **maximum price ($350)** show that brands offer both affordable and premium options, but overall the market is quite **balanced.**
Because **skewness (0.03)** is very close to zero, the price data is almost symmetrical, meaning there are **no extreme cheap or expensive outliers.**
The **kurtosis (-1.23)** being negative means the price spread is flatter than a normal curve, so prices are **spread out but stable** — not clustered tightly in one range.

In real life, this tells us that **the shoe market is very competitive.**

Most brands are trying to stay near **the average price point (~$210)** to attract as many customers as possible.
Since prices are already similar, brands can’t rely on lowering prices to win customers — instead, they need to compete on design, comfort, color choice, and brand image.

This insight would be most useful for **marketing teams, pricing analysts, and retail managers:**

* **Marketing teams** can focus on promoting **brand value and product uniqueness**, rather than just offering discounts.
* **Pricing analysts** can use this information to plan **promotions or seasonal pricing** around the average price (e.g., small discounts near $200 can make products stand out).
* **Retail or product managers** can see that there’s an opportunity to **create premium lines above $300** or **budget lines below $150**, since most products are stuck in the middle range.

In short, this insight shows that the shoe market keeps prices stable and similar across brands, which helps companies understand how to adjust their pricing strategy and position products effectively without hurting profit margins.

The **descriptive statistics table** is the best visualization for this insight because it clearly summarizes **the average, variation, and spread** of numerical data (price).It helps both students and managers quickly understand the **overall pricing pattern** in the market.
