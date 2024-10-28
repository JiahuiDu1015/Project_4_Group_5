# Project_4_Group_5

![image](https://github.com/user-attachments/assets/89e01c71-358e-4214-be72-02ad85cd6564)


# Project proposal

The gym chain One Fitness is in the process of developing a customer interaction strategy driven by analytical data. One of the most significant challenges that gyms and similar services encounter is customer churn. But how can you determine if a customer has disengaged? You can calculate churn by tracking those who cancel their accounts or fail to renew their memberships. However, sometimes it’s not immediately clear that a client has left; they may quietly withdraw their engagement.

Churn indicators can differ across industries. For example, if a customer rarely makes a purchase from an online store but does so consistently, they cannot be considered lost. Conversely, if a user has not accessed a platform that offers daily updates for two weeks, that’s a cause for concern; they may have lost interest and moved on.

For a gym, it is reasonable to conclude that a customer has left if they haven’t visited in a month. While it’s possible they are on vacation and will return, this is not the usual scenario. Typically, if a customer joins, attends a few times, and then disappears, they are unlikely to return.

To combat churn, Model Fitness has digitized several customer profiles. Your task is to analyze this data and develop a customer retention strategy.

You should:
 - Learn to predict the probability of churn (for the upcoming month) for each customer
 - Draw up typical user portraits: select the most outstanding groups and describe their main features
 - Analyze the factors that impact churn most
 - Draw basic conclusions and develop recommendations on how to improve customer service:
   
      - Identify target groups
   
      - Suggest measures to cut churn
   
      - Describe any other patterns you see with respect to interaction with customers

# Data

   https://www.kaggle.com/datasets/ellanihill/model-fitness-customer-churn

# Data description

**Churn** - outflow in the current month;

Client data for the previous month before checking the outflow:

**gender** - man;

**Near_Location** - living or working in the area where the fitness center is located;

**Partner** - an employee of the club's partner company (cooperation with companies whose employees can receive discounts - in this case, the fitness center stores information about the client's employer);

**Promo_friends** - the fact of the initial registration as part of the “bring a friend” promotion (used a promo code from a friend when payed for the first subscription);

**Phone** - the presence of a contact phone;

**Age** - age;

**Lifetime** - time since the first visit to the fitness center (in months).

Information based on the log of visits, purchases and information about the current status of the client's subscription:

**Contract_period** - duration of the current active subscription (1 month, 3 months, 6 months, a year);

**Month_to_end_contract** — period until the end of the current active subscription (in months);

**Group_visits** - the fact of visiting group classes;

**Avg_class_frequency_total** - the average frequency of visits per week for the entire time since the start of the subscription;

**Avg_class_frequency_current_month** - average frequency of visits per week for the previous month;

**Avg_additional_charges_total** - total amount spent on the other services in the fitness center: cafe, sports goods, cosmetic and massage salon.

# Navigation
Gym_churning_colab - jupyter notebook file, created in Google Colab, that contains the queries.

# Notes
The model utilises data retrieved from Spark
check SPARK_VERSION (spark_version = 'spark-3.5.3')

# Group Presentation

# Conclusion

# Recommendations

   
