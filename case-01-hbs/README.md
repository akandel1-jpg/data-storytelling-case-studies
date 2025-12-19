# Case 1: Harvard Business School Online — Data Storytelling

## Source
HBS Online  
Source: Harvard Business School Online — “Data Storytelling: How to Effectively Tell a Story with Data”
 https://online.hbs.edu/blog/post/data-storytelling

Kaggle — Retail Sales Dataset (synthetic retail transactions, 1,000 records)
 https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset



---

## 1. Business Context

In today’s business environment, companies generate more data than ever before, including customer transactions, website clicks, financial reports, and operational metrics. Despite the availability of sophisticated tools to collect and analyze this information, many organizations still struggle to turn raw numbers into meaningful action. Spreadsheets and dashboards can highlight patterns, but they often fail to capture attention or persuade decision makers to act. 

This is where data storytelling comes in. Business leaders need more than statistics. They need a clear explanation that conveys what the data means, why it matters, and what should be done next. Harvard Business School Online, in its article “Data Storytelling: How to Effectively Tell a Story with Data,” argues that data only leaves an impact when it is framed as part of a story. By combining analysis, narrative, and visuals, data storytelling transforms abstract information into insights that inspire decisions. 
To illustrate this, we apply HBS’s storytelling principles to a real dataset: a synthetic Retail Sales Dataset from Kaggle. The dataset contains 1,000 records of transactions, including variables such as date, product category, quantity, and sales amount. By combining the HBS framework with concrete retail data, this case study demonstrates how context, conflict, and resolution form the backbone of effective business decision-making.

---

## 2.  Communication Goals
The goal of the case study is two-fold:

Conceptual
The communication goal in this case study is to demonstrate why storytelling is a critical skill for business leaders and to show how data storytelling can transform business analysis into strategic decision-making. The article emphasizes that storytelling is not merely a “nice to have” but a core management skill. It enables analysts, managers, and executives to:
Align cross-functional teams around a shared understanding.
Persuade senior leadership to approve projects or funding.
Drive cultural change toward evidence-based decision-making.

Applied — Use the Kaggle retail dataset to illustrate how raw data can be reframed into a narrative that highlights a problem, creates urgency, and drives a recommendation.


---

## 3. Intended Audience

The primary audience for this case study, as defined by HBS, includes:
Business leaders and managers - To make strategic decisions.
Data analysts and professionals - To learn how to communicate technical findings to non-technical colleagues.
Students and learners -  Preparing for careers where data-driven decision-making is central.
A secondary audience includes educators and consultants who design training programs to teach storytelling with data.


---

## 4. Narrative Structure / Key Story Elements

According to the HBS article, the most effective way to communicate data is to present it as a story. A compelling data story has three essential parts: context, conflict, and resolution.

Context (the “why”): In the business setting, context ensures “why” the data matters in the first place. This helps to clearly define the problem or question that the data is trying to answer. For example, “(Why) the sales have been declining for three consecutive quarters. Etc.”

Conflict (the “tension”): In data storytelling, conflicts come through identifying risks, gaps, and unusual patterns in the data. For example, Flat revenue growth despite the heavy traffic on the website. Therefore, highlighting the conflicts creates a sense of urgency and keeps the audience engaged.

Resolution (the “so what”): Ultimately, a data story must provide a clear direction for moving forward. This is where analysis and visualization come into action. Resolution connects the analysis back to decision-making, ensuring the story leads to clear recommendations.


---

## 5. Visualizations and Analytical Questions
For this case study, I combined insights from the Harvard Business School Online article “Data Storytelling: How to Effectively Tell a Story with Data” with a synthetic retail dataset from Kaggle – Retail Sales Dataset. The dataset comprises 1,000 retail transactions, including details such as date, customer age and gender, product category (Beauty, Clothing, Electronics), and total purchase amount. It provides a realistic yet manageable foundation for business analysis. Using Jupyter Notebook with Python, I worked only with basic libraries—datascience, numpy, and matplotlib—to process the data and create simple visualizations. These included monthly sales trends, average order values, category revenues, and age group contributions.

## Visualization 1 — Monthly Total Sales

Question:
How does total revenue change over time, and are there identifiable seasonal patterns?

Insight:
Sales fluctuate throughout the year, with identifiable peaks and dips that suggest seasonal demand cycles.

## Visualization 2 — Monthly Average Order Value (AOV)

Question:
Is customer spending per transaction increasing or declining over time?

Insight:
Average order value shows a gradual upward trend, indicating higher-value purchases even when total volume varies.

## Visualization 3 — Revenue by Product Category

Question:
Which product categories contribute most to overall revenue?

Insight:
Electronics leads revenue generation, while Clothing and Beauty remain strong secondary contributors.

## Visualization 4 — Revenue by Age Group and Category

Question:
Which customer age groups drive revenue across product categories?

Insight:
Customers aged 46–60 generate the highest revenue, while younger segments exhibit more category-specific spending behavior.

## Visualization 5 — Average Order Value by Category

Question:
Do customers spend differently depending on the product category?

Insight:
AOV remains relatively consistent across categories, enabling cross-category pricing and bundling strategies.

## Visualization 6 — Cumulative Revenue Share (Pareto Analysis)

Question:
Is revenue concentrated among a small group of customers?

Insight:
A small percentage of customers accounts for a disproportionately large share of total revenue, consistent with the Pareto principle.

## Visualization 7 — New vs. Repeat Customers Over Time

Question:
Is the business shifting toward customer retention?

Insight:
Repeat customers increasingly dominate total transactions, signaling a maturing customer base.

---

## 6. Business Insights and Strategy

The seven visualizations together tell a clear story of a business that’s growing steadily and learning to use its data more intelligently. The numbers show that sales patterns, customer behavior, and product trends are all connected. 
The sales and average order value charts show a healthy pattern of ups and downs, with clear mid-year peaks that likely match marketing campaigns or seasonal promotions. This means the business has predictable cycles it can plan around. To make the most of that, marketing and inventory should work together.  They should push for stronger promotions during peak seasons and offer loyalty rewards or targeted discounts in quieter months to keep customers engaged.
Across categories, spending looks surprisingly balanced.  Customers spend about the same amount on Beauty, Clothing, and Electronics. That balance is a strength because it means buyers trust all categories equally. It also opens up cross-selling opportunities like bundling a skincare product with fashion accessories, or pairing gadgets with lifestyle items to lift average order values without changing prices. The age-based insights deepen the story where customers aged 46–60 are the most consistent and high-value group, while younger buyers (18–35) are more trend-driven. That calls for two different tones in marketing: influencer-based campaigns for younger audiences, and quality- or value-based messaging for older, established buyers.
The Pareto analysis reminds us that a small number of loyal customers, about twenty percent, drive most of the revenue. Those are the people worth holding onto. Loyalty programs, exclusive offers, and personalized communication can keep them coming back, while re-engagement campaigns can gradually turn smaller spenders into more frequent buyers.
Lastly, the new versus repeat customer trend depicts a very positive picture. The business has moved from relying on new customer acquisition early in the year to building real loyalty by the end of it. That’s what every retail company wants to see — a solid base of repeat customers who keep the business stable. Going forward, the focus should be on maintaining that loyalty while still keeping the flow of new customers alive through social media engagement, referral incentives, and consistent brand storytelling.


---

## 8. References

Harvard Business School Online. (2022, March 22). Data storytelling: How to effectively tell a story with data. Harvard Business School. https://online.hbs.edu/blog/post/data-storytelling
Talib, M. (2023). Retail sales dataset (synthetic retail transactions) [Data set]. Kaggle. https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
OpenAI. (2025). ChatGPT (October 2025 version) [Large language model]. Used for coding assistance and data visualization guidance in Python. https://chat.openai.com
Project Jupyter. (2015). Jupyter Notebook [Computer software]. https://jupyter.org


