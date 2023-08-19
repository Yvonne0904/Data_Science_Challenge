# Identifying Fraudulent Activities

## Goal:

The goal of this challenge is to build a machine learning model that predicts the probability that the first transaction of a new user is fraudulent.

## Challenge Description:

You have to build a model that predicts whether a user has a high probability of using the site to perform some illegal activity or not. 

You only have information about the user first transaction on the site and based on that you have to make your classification ("fraud/no fraud").



### Task(a)

For each user, determine her country based on the numeric IP address.

### Task(b)

Build a model to predict whether an activity is fraudulent or not. Explain how different assumptions about the cost of false positives vs false negatives would impact the model.

### Task(c)

Your boss is a bit worried about using a model she doesn't understand for something as important as fraud detection. How would you explain her how the model is making the predictions? Not from a mathematical perspective (she couldn't care less about that), but from a user perspective. **What kinds of users are more likely to be classified as at risk?** **What are their characteristics?**

### Task(d)

Let's say you now have this model which can be used live to predict in real time if an activity is fraudulent or not. From a product perspective, how would you use it? That is, **what kind of different user experiences** would you build based on the model output?



## Data

### Table A - Fraud Data

**Columns:**

- user_id
- signup_time
- Purchase_time
- Purchase_value
- device_id
- source
- browser
- sex
- age
- Ip_address
- Class

### Table B - IpAddress_to_Country

**Columns:**

- Lower_bound_ip_address
- Upper_bound_ip_address
- Country