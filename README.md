# Customer-Funnel



# Goal of the Project

To provide recommendations or hypotheses to improve company conversion by helping to scope where to implement product interventions to increase pull through to sign and exam.


# The Data 

The two datasets are made up of these variables listed below:

started_navigator - first step in the product funnel and everyone in this dataset sees this step.

collect_contact_info - this is where we ask for an email and phone number for identification and marketing purposes.

viewed_quotes - After presenting contact info, we are able to show customers quotes for life insurance. This is the first place they see pricing.

application_submit - After seeing quotes, customers can submit applications to move forward with their quotes.

phone_connect - Once a customer submits an application, the app is routed to a live insurance agent to call them and collect more detailed information to move them forward with the life insurance process.

sign_and_exam - For this purpose, this is the last step to analyze. This represents a customer moving forward the life insurance process and scheduling a medical exam.

In the user dataset the fields in it include:

user_id - the key that identifies the user.

age - how old the customer applying for life insurance is.

device - indicates the type of device a customer came in on. This allows you to differentiate between mobile and desktop and also what kind of mobile device (ios vs android)

income - annual income as provided by the customer.

num_conditions - how many health conditions the customer has.

premium - the annual price for the lowest policy from the quotes provided to customers. This is what the customer will pay a year.

marketing_channels - the marketing channel the customer came from.

The funnel dataset has 7 columns and the user dataset has 2 columns.



# What hypotheses do you take away from the funnel and segmentation analysis above?

Some of the questions that came to mind after doing analysis were:
How can we measure the effectiveness of the marketing channels? Are podcast more effective? Those that went through the podcast channel were more likely to convert at the end of the funnel.
Null hypothesis- Using the podcast marketing channel does not affect if a customer makes it to the end of the funnel and converts.

alternative hypothesis- Using the podcast marketing channel does affect if a customer makes it to the end of the funnel and converts.

Does the type of device impact whether or not a customer converts?
Null hypothesis: Using a mobile ios device does not affect if a customer converts.

alternative hypothesis: using a mobile ios device does affect if a customer converts.

Does having more exposure to the product make it more likely that a customer converts?
null hypothesis: Advertising more does not increase a customers chances of converting.

alternative hypothesis: Advertising more thrugh a particular marketing chanel increases a customers chances of converting.

Does having more income make it more likely that a customer will convert?
null: Having more income does not have an effect on whether a customer will make it through the end of the funnel and convert.

alternative: Having more income does have an effect on whether a customer will make it through the end of the funnel and convert.

# What recommendations would you make to the product team?

Some of the recommendations that I would make to the product team is to look closley at the navigator and try to think of ways to engage and increase click rate for the other parts of the process.

Seeing if we can have different incentives for people with different incomes. Maybe seeing if discounts can be added at certain parts of the year to incentivize people with lower income to move through the funnel.

# How would you test your recommendations?

I would test my recommendations with a few A/B tests to see what drives the largest impact to get the most people to convert.

For instance, if I want to look at how the webpage plays a role in customers that make it through the funnel, I would potentially test how

What is the probability that someone with more than two conditions will convert given that they opened the navigator?

or I can test, what is the probabilty that someone with x income will convert given that they opened the navigator?

Then also looking into how certain characterisitics of the webpage plays in having different groups convert like what would the difference between having a blue or red click here button be on individuals who have more than two conditions on converting given that they opened the navigator?

# What recommendations are likely to drive the largest impact?

Foucsing on what aspects of the navigator influences customers to convert and income would drive the largest impact since the webpage's design and how it impacts the customer as well as what their income looks like when viewing the quotes can influence whether or not they decide to purchase.
What are the caveats of your analysis?

# A few of the caveats of my analysis include:

Not knowing the gender of the customers. Maybe women tend to purchase insurance more and there are ways to market to that group specifically and vice versa.

Knowing other demographic information too like family size or location whether the customers are in rural or urban NC or elsewhere.

Knowing how time affects habits, so like whether or not there is specific season when more people tend to purchase insurance and how we can go about marketing to customers during the off season.

# If you had more time and resources to develop this analysis further. What additional attributes would you want to gain more insight about optimizing conversion?

I would want to look more into other demographics such as education, location, occupation, possibly gender and family size which could all have an impact on wehther the person goes through to the end of the funnel or not and it could also give insight into the types of consumers that are purchasing which can give more of an idea on how to market the product.
What other ways could you expand this work?

To expand this work, I would design a hypothesis test and then predict the conversation rates using the most important features using either a logistic regression or Naives Bayes to estimate the probability of conversion.
