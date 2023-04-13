# User-churn-Analysis-PowerBI
## **Introduction:**   
we have dataset of a telecommuncation in US. The stakeholder of the company want to know the situation of their churn user, based on that information generate the strategy to tackle the increase of churn user/decrease the churn user. Why churn analysis is crucial? -> It help firms know number of customer stop using service (doing business) as well as the causes of the churn and with those infors they implement effective strategies for retention of customers. The indicator is hightly important cause it affect directly to revenue and profit. Imagine that you have a bucket with a leaking crack, you keep adding water (or new clients), but your revenue will not improve if existing customers leave. Beside that, it's more costly to acquire new customers than to retain existing ones. ---> It's crucial to know your customer churn and find ways to reduce it. 

## **Dataset structure:**

| **Field**     | **Meaning**   | **Example**   | 
| ------------- | ------------- | ------------- | 
| Customer ID | ID of customer (unique)
| Churn label | state "YES" if customer is a churn user and "NO" if not
| Account lenght | the lenght of the account, it's calcilated by month
| Local Calls |Local call - service product of the company
| Local Mins | Total time of local call that is made by customer
| Intl Calls | International call - service product of the company
| Intl Mins | Total time of international call that is made by customer
|	Intl Active	| state of the account whether the customer register for the International call service or not.
| Extra International Charges | charges (fee) for International call service
| Customer Service calls | Number of calls to that's made by client
| Avg Monthly GB Download | 
| Unlimited Data Plan | state of the customer account whether they use Unlimited Data Plan service or not
| Extra Data charge | charges (fee) for Unlimited Data Plan
| State | state where the customer live
| Phone number | phone number of the customer
| Gender | gender of the customer
| Age Under 30 | state of the customer, if they are under 30 then the result is 'YES', if not it's 'NO'
| Group | state of the customer whether they registered as a group or not
| Number of customer in group| corresponding with 'group' indicator
| Device Protection & Online Backup| state of the customer account whether they use Device Protection & Online Backup or not
|	Contract Type	| types of contract | Month-to-Month, One Year, Two Year
| Payment Method | types of payment | credit card, cash...
| Monthly Charge |	
| Total Charges	|
| Churn Category | categories of churn reason | Attitude, Price....
| Churn Reason | sub-categories, corresponding with 'churn category' indicator | Attitude of support person, Attitude of customer service.....

## **Note:**
Please first read file ***"Procedure of applying Design Thinking into Problem Solving Telecommunication firm case"*** to see how this method tackle the task question related to Bank X case. After that you can open and read PowerBi Dashboard

## **Insight about the effectiveness of debt collection:**
  1. The current churn rate (~27%) is higher than the average churn rate (21%) in Telecom industry (according to Statista, 2020) and assosiated revenue loss by churn users is ~19% (1.4M) ->> A signal for the company to take action on churn issue.

  2. Demographic analysis for churn users: 
 - Gender: mostly equal ->> No notable issues - discarded from dashboard
 - Age: Old adulthood (36-55) group is the 2nd largest users but has the highest churn rate (~32%), followed by Middle age (36-55) group, then Young adulthood (18-35) group (both around 23%) ->> More actions needed for people aged 36-55.
 - Location: User group living in CA state has an outstanding churn rate (nearly double than the other following top churn rate states) - >> Find out what is happening in CA state.

  3. Most important trigger for churn users is Competitor (~45%) whether filtering by Agegroup or Station(Location). It causes a 45% loss in revenue as well which is also the biggest proportion in Total revenue loss by churn users

## **Recomendation for telecommuncation firm based on generated insights:**

All the reasons regardless of category (Competitor, Attitude, Disatisfaction, Price) fall into three issues: 
  1. Providing products

  2. Customer services
 
  3. Price

(1) The product: (Need more information about the company to give recommendations)
     - Which products the company are providing? 
     - What are the disatisfaction of the product? ->> Survey for deeper research
     - How to improve the current product? ->> R&D department

(2) Customer services: 
     - Need more data to analyze how customer services team is doing?
     - Can they improve their quality by new rules or incentives?

(3) Price: 
     - Do competitor analysis
     - Re-evaluate pricing model: could be "customized price" by giving promo by user ages

=> The most important trigger for churn users are "Competitors"  ->> Do competitor analysis thoroughly for further brainstorming ideas" and make deeper analysis for age (36-55) group and CA state location.

***Please make proper credit if you want to use all my content (except the dataset)**

