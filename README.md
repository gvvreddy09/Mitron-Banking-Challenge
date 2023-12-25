# Provide Insights to the Product Strategy Team In the Banking Domain
## Problem Statement
**Mitron Bank** is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards to broaden their product offerings and reach the financial market.

**AtliQ Data Services** came to know about this through an internal link and approached **Mitron Bank** with a proposal to implement this project. However, the strategy director of Mitron Bank, **Mr. Bashnir Rover** is skeptical and asked them to do a pilot project with the sample data before handing over the full project. They provided a sample dataset of **4000 customers** across five cities on their online spending and other details.

The analysis is expected to guide the product strategy team of Mitron Bank in tailoring credit cards based on customer needs and market trends.

### Dataset
1. **dim_customers** 
   + customer_id
   + age_group
   + city
   + gender
   + marital_status
   + avg_monthly_income
2. **fact_spends**
   + customer_id
   + months
   + category
   + payment_type
   + spend

For further details please refer to [Codebasics RPC8](https://codebasics.io/challenge/codebasics-resume-project-challenge)

### Approach
Imported datasets to Power BI and built a dashboard. Constructed a Star-schema data model.

+ To interact with [Live dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmNmNzc3NGItZjFiYi00NWM3LTk3NjItNzNkMjA1MTc2MzIzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).
+ [Presentation Link](https://www.linkedin.com/feed/update/urn:li:activity:7145044697097379840/).

### Top Level Insights by customer's demographics
1. **Age Group**
   + 25-34 and 35-45 are high-value customers for new credit cards(bills, groceries, electronics, travel, food, and health and wellness)
   + 21-24 for category-wise credit cards(entertainment, electronics, and apparel) and 45+ for bills, groceries, and health and wellness
2. **City**
   + Mumbai, Delhi, and Bengaluru are high-value customers for new credit cards for all categories - more importantly (bills, groceries, electronics, health and wellness, and travel)
   + Chennai and Hyderabad are also eligible for specific category-wise credit cards (bills, groceries, and electronics...)
3. **Gender**
   + Males are high-value customers for new credit cards for all categories - more importantly (bills, groceries, electronics, travel, food, and entertainment)
   + Females are also eligible for specific category-wise credit cards (Health and wellness and apparel)
4. **Marital Status**
   + Married are high-value customers for new credit cards for all categories - more importantly (bills, groceries, electronics, health and wellness, and travel)
   + Singles are also eligible for specific category-wise credit cards (electronics, bills, and entertainment...)
5. **Occupation**
   + Salaried IT employees, Business owners, and other employees are high-value customers for new credit cards
     + IT employees for all categories - more importantly (bills, groceries, electronics, health and wellness, and travel)
     + Business owners for categories (bills, groceries, electronics, travel and entertainment)
     + Salaried Other employees for categories (bills, groceries, electronics, health and wellness, and food)
   + Freelancers and Government employees are also eligible for specific category-wise credit cards (bills, groceries, and electronics...)









