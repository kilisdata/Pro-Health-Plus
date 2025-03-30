# Pro Health Plus
## The objective of this project is to analyze the effectiveness of marketing campaigns at Pro Health Plus and provide recommendations for future marketing budget allocation across various campaign categories.
With over ten years in business, Pro Health is a medical insurance company serving thousands of clients across the country. As part of the company's 2019 marketing campaign, wellness tips, affordable health care plans, and preventive care topics were featured. There are four different plans available to customers: bronze, silver, gold, and platinum, each with varying premiums and levels of coverage.

The new data team at Pro Health and the upcoming strategizing of their marketing budget this year will support their efforts to better understand the impact of these campaign categories on customer signups and claims. There are two primary objectives for the marketing budget: 1) increase the number of customers, and 2) raise awareness of Row Health nationwide.

# Data Structure
The dataset consisted of three tables, including information about campaigns, signups, and user demographics, as well as claims filed by customers and related claim information.

![image](https://github.com/user-attachments/assets/5ebffa95-6952-4b61-8ebf-44ca648b398c)

# Analytical Deep Dive
### To evaluate campaign performance, we focused on the following key metrics:
**Signup Rate**: The percent of people who see a campaign and subsequently sign up for a Row Health plan.

**Cost per Signup**: The average dollars spent to acquire a signup from each campaign.

**Click Through Rate**: The percent of people who see a campaign and click on the associated link.

### **Signup Rate**
- The "Health for All" campaigns stood out for their exceptional performance, achieving the highest signup rate of **2.9%**. This translated to an impressive **3,500 total signups**, making it the most successful campaign category in terms of rate.
- Within the "Health for All" campaigns, the Health Awareness campaign type demonstrated its effectiveness, boasting the **highest signup rate across all campaign types at 3.72%**. This underscores the strong interest in health-related content.
- Surprisingly, the #HealthyLiving campaign category, which accumulated the **highest total number of signups**, had a comparatively low signup rate of **0.3%**, indicating that while it attracted large numbers, it was less efficient in converting interest into action.

### **Click-Through Rate (CTR)**
- The "Health for All" campaigns achieved an impressive **36% CTR**, far outperforming the average. This indicates that the campaigns successfully engaged viewers and encouraged them to click.
- Similarly, the "Benefit Updates" campaigns had a strong performance with a **22% CTR**, highlighting their appeal and effectiveness.
- Within these two high-performing categories, however, product promotion campaigns struggled to maintain engagement, recording significantly lower CTRs of **0%** ("Health for All") and **7%** ("Benefit Updates").
- The Family Coverage Plan drew substantial attention, evidenced by high impressions. However, it failed to convert this interest into clicks, generating **no engagement at all**. This result raises concerns about potential underlying issues, such as missing data or flaws in the campaign design, requiring further analysis to address the problem.

### **Cost per Signup**
- The "Golden Years Security" campaign proved to be the most expensive in terms of customer acquisition, with a **cost per signup of $124**, dramatically higher than the average of **$2.20**. This campaign also had the lowest total signups, achieving only **23**, highlighting its inefficiency and raising questions about resource allocation.
- Info-based campaign types, such as those focusing on offers and policy information, contributed significantly to higher customer acquisition costs. This suggests that informative campaigns may require more resources to drive engagement and conversions.
- COVID-related campaigns reported extraordinarily high customer acquisition costs, ranging from **$1,200 to $1,300**. These figures suggest challenges in targeting and engaging audiences effectively during sensitive periods.

## Dashboard
The dashboard can be found in Tableau Public. This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

![image](https://github.com/user-attachments/assets/44f77e7d-c3cb-4059-bf90-f7dd2092238c)

