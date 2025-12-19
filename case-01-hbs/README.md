# Case 1: Harvard Business School Online — *Data Storytelling: How to Effectively Tell a Story with Data*
**Source:** [HBS Online](https://online.hbs.edu/blog/post/data-storytelling)

---

Source: Harvard Business School Online — “Data Storytelling: How to Effectively Tell a Story with Data”
 https://online.hbs.edu/blog/post/data-storytelling

Kaggle — Retail Sales Dataset (synthetic retail transactions, 1,000 records)
 https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

Business Context
In today’s business environment, companies generate more data than ever before, including customer transactions, website clicks, financial reports, and operational metrics. Despite the availability of sophisticated tools to collect and analyze this information, many organizations still struggle to turn raw numbers into meaningful action. Spreadsheets and dashboards can highlight patterns, but they often fail to capture attention or persuade decision makers to act. 

This is where data storytelling comes in. Business leaders need more than statistics. They need a clear explanation that conveys what the data means, why it matters, and what should be done next. Harvard Business School Online, in its article “Data Storytelling: How to Effectively Tell a Story with Data,” argues that data only leaves an impact when it is framed as part of a story. By combining analysis, narrative, and visuals, data storytelling transforms abstract information into insights that inspire decisions. 
To illustrate this, we apply HBS’s storytelling principles to a real dataset: a synthetic Retail Sales Dataset from Kaggle. The dataset contains 1,000 records of transactions, including variables such as date, product category, quantity, and sales amount. By combining the HBS framework with concrete retail data, this case study demonstrates how context, conflict, and resolution form the backbone of effective business decision-making.
Communication Goals
The goal of the case study is two-fold:

Conceptual
The communication goal in this case study is to demonstrate why storytelling is a critical skill for business leaders and to show how data storytelling can transform business analysis into strategic decision-making. The article emphasizes that storytelling is not merely a “nice to have” but a core management skill. It enables analysts, managers, and executives to:
Align cross-functional teams around a shared understanding.
Persuade senior leadership to approve projects or funding.
Drive cultural change toward evidence-based decision-making.

Applied — Use the Kaggle retail dataset to illustrate how raw data can be reframed into a narrative that highlights a problem, creates urgency, and drives a recommendation.


Audience

The primary audience for this case study, as defined by HBS, includes:
Business leaders and managers - To make strategic decisions.
Data analysts and professionals - To learn how to communicate technical findings to non-technical colleagues.
Students and learners -  Preparing for careers where data-driven decision-making is central.
A secondary audience includes educators and consultants who design training programs to teach storytelling with data.

Key story elements 

According to the HBS article, the most effective way to communicate data is to present it as a story. A compelling data story has three essential parts: context, conflict, and resolution.

Context (the “why”): In the business setting, context ensures “why” the data matters in the first place. This helps to clearly define the problem or question that the data is trying to answer. For example, “(Why) the sales have been declining for three consecutive quarters. Etc.”

Conflict (the “tension”): In data storytelling, conflicts come through identifying risks, gaps, and unusual patterns in the data. For example, Flat revenue growth despite the heavy traffic on the website. Therefore, highlighting the conflicts creates a sense of urgency and keeps the audience engaged.

Resolution (the “so what”): Ultimately, a data story must provide a clear direction for moving forward. This is where analysis and visualization come into action. Resolution connects the analysis back to decision-making, ensuring the story leads to clear recommendations.

Visualization
For this case study, I combined insights from the Harvard Business School Online article “Data Storytelling: How to Effectively Tell a Story with Data” with a synthetic retail dataset from Kaggle – Retail Sales Dataset. The dataset comprises 1,000 retail transactions, including details such as date, customer age and gender, product category (Beauty, Clothing, Electronics), and total purchase amount. It provides a realistic yet manageable foundation for business analysis. Using Jupyter Notebook with Python, I worked only with basic libraries—datascience, numpy, and matplotlib—to process the data and create simple visualizations. These included monthly sales trends, average order values, category revenues, and age group contributions.
Figure 1 – Monthly Total Sales
Question:
 “How do total sales fluctuate month to month, and what seasonal or promotional patterns can be identified to guide sales and inventory planning?”





















The company’s revenue fluctuates significantly across months, with May showing the strongest sales and January the weakest. This volatility suggests seasonal or promotional effects. The decline toward the end of the year highlights a potential conflict — high customer activity doesn’t always translate into sustained revenue. The story here points managers to investigate why sales momentum is inconsistent.

Figure 2 – Monthly Average Order Value (AOV)
Question:
 “How does the average order value change over time, and what does this indicate about customer spending behavior and pricing effectiveness?”


























While total sales are declining in some months, the average order value is trending upward. This means fewer customers are making purchases, but those who do are spending more per transaction. The tension between shrinking transaction volume and rising order values points to a strategic need: should the business focus on attracting more customers, or continue maximizing revenue from existing ones?




Figure 3 – Revenue by Product Category
Question:
 “Which product categories contribute most to overall revenue, and how can this insight shape product-mix and marketing strategies?”

Electronics leads overall revenue, followed closely by Clothing and Beauty. This distribution shows that while Electronics is the top-performing category, the other segments remain important contributors. The insight suggests a balanced portfolio strategy: continue investing in Electronics while using promotions to boost underperforming categories.



Figure 4: Revenue by Age Group and Product Category
Question: “Are certain customer segments (by age group) driving revenue growth in specific product categories, and what does this reveal for business strategy?” 

The stacked bar chart shows total revenue by age group, broken down into product categories (Beauty, Clothing, Electronics). Each bar represents an age segment (18–25, 26–35, 36–45, 46–60, 60+), while the colored segments show how much each product category contributes to that group’s total revenue.
The analysis of revenue by age group reveals distinct spending patterns across customer segments. The high-value group aged 46–60 contributes the largest overall revenue, with purchases balanced across Beauty, Clothing, and Electronics, and particularly strong performance in Electronics. Younger consumers aged 18–25 and 26–35 show noticeable spending on Clothing and Beauty but contribute less to Electronics, reflecting trend-driven, fashion-oriented buying behavior rather than big-ticket purchases.  In contrast, the 60+ segment generates the least revenue overall, which may indicate a smaller customer base or reduced purchasing power in this dataset. Finally, the mid-segment aged 36–45 shows a balanced distribution across categories but does not reach the same spending levels as the 46–60 group, highlighting their role as steady but moderate contributors.
Figure 5 – Average Order Value (AOV) by Product Category
Question:
 “Do customers spend differently across product categories, and what opportunities exist to optimize pricing, bundling, or cross-selling?”















The chart shows that Beauty, Clothing, and Electronics categories have nearly the same Average order values. This shows a balanced spending pattern across the product mix. This depicts that no single product is significantly outperformed by other categories, and customers perceive a similar value product. The company can leverage this by maintaining a consistent pricing strategy and cross-category promotions like bundling beauty items with clothing, to encourage multi-category purchase without disrupting the current stability. 

Figure 6 – Cumulative Revenue Share by Customers (Pareto Analysis)
Question:
 “What proportion of total revenue is generated by the top-spending customers, and how concentrated is the company’s customer base in terms of profitability?”


The Pareto chart shows that roughly 20% of customers account for about 65–70% of total revenue, confirming the classic 80/20 principle often seen in retail. This means a small group of loyal, high-value customers is driving the majority of business performance. The remaining 80% of customers together contribute only the last 30–35% of sales, showing much lower spending or purchase frequency.
From a business perspective, this highlights the importance of retaining and nurturing the top customer segment through loyalty programs, early-access deals, and personalized experiences. At the same time, the company should focus on converting more casual buyers into repeat customers through re-engagement campaigns, email marketing, or bundle offers. Therefore, keeping the top 20% happy and gradually lifting the rest could significantly increase overall profitability.


Figure 7 – New vs. Repeat Customers Over Time
Question:
 “How is the balance between new and repeat customers evolving, and what does this reveal about the company’s customer acquisition and retention effectiveness?”


The chart shows the clear transition from customer acquisition to retention over time.  In the early months, most customers are new (blue line) depicts that the business was focused on attracting first-time buyers. During the mid-year, repeat customers steadily increased as those early buyers returned, as shown by the rising orange line. Towards the end, repeat segment dominates while new customer inflow slows - suggesting that the company has built a strong returning customer base. This seems healthy for a growing business. Early marketing drove the customers, and by mid-year, the retention and loyalty program started paying off. The goal now should be to sustain steady new customer acquisition. 




Business Strategy
The seven visualizations together tell a clear story of a business that’s growing steadily and learning to use its data more intelligently. The numbers show that sales patterns, customer behavior, and product trends are all connected. 
The sales and average order value charts show a healthy pattern of ups and downs, with clear mid-year peaks that likely match marketing campaigns or seasonal promotions. This means the business has predictable cycles it can plan around. To make the most of that, marketing and inventory should work together.  They should push for stronger promotions during peak seasons and offer loyalty rewards or targeted discounts in quieter months to keep customers engaged.
Across categories, spending looks surprisingly balanced.  Customers spend about the same amount on Beauty, Clothing, and Electronics. That balance is a strength because it means buyers trust all categories equally. It also opens up cross-selling opportunities like bundling a skincare product with fashion accessories, or pairing gadgets with lifestyle items to lift average order values without changing prices. The age-based insights deepen the story where customers aged 46–60 are the most consistent and high-value group, while younger buyers (18–35) are more trend-driven. That calls for two different tones in marketing: influencer-based campaigns for younger audiences, and quality- or value-based messaging for older, established buyers.
The Pareto analysis reminds us that a small number of loyal customers, about twenty percent, drive most of the revenue. Those are the people worth holding onto. Loyalty programs, exclusive offers, and personalized communication can keep them coming back, while re-engagement campaigns can gradually turn smaller spenders into more frequent buyers.
Lastly, the new versus repeat customer trend depicts a very positive picture. The business has moved from relying on new customer acquisition early in the year to building real loyalty by the end of it. That’s what every retail company wants to see — a solid base of repeat customers who keep the business stable. Going forward, the focus should be on maintaining that loyalty while still keeping the flow of new customers alive through social media engagement, referral incentives, and consistent brand storytelling.


References
Harvard Business School Online. (2022, March 22). Data storytelling: How to effectively tell a story with data. Harvard Business School. https://online.hbs.edu/blog/post/data-storytelling
Talib, M. (2023). Retail sales dataset (synthetic retail transactions) [Data set]. Kaggle. https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset
OpenAI. (2025). ChatGPT (October 2025 version) [Large language model]. Used for coding assistance and data visualization guidance in Python. https://chat.openai.com
Project Jupyter. (2015). Jupyter Notebook [Computer software]. https://jupyter.org

---

## Notes for Repository
- Save this README.md inside the folder: `case-01-hbs/`.  
- Add a `visuals/` subfolder with at least 2–3 charts demonstrating the sequence above.  
- Add a `data/` subfolder with either the real dataset link or a simulated CSV.  
