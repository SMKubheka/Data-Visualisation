# Medical Insurance 

## Context 

Insurance companies make money by collecting more in yearly premiums than they spend on medical care for its beneficiaries. As a result, insurers invest time and money to develop models that accurately forecast medical expenses. These are difficult to estimate because the most costly conditions are rare and seemingly random. Still, some conditions are more prevalent for certain segments of the population, eg. lung cancer is more likely among smokers than non-smokers, and heart disease may be more likely among the obese.

The goal of this analysis is to use patient data to estimate the average medical care expenses for such population segments. These estimates could be used to create actuarial tables which set the price of yearly premiums higher or lower depending on the expected treatment costs. Note: South Africa has standardised medical aid rates, which is different from the US and many other countries, where medical insurance is priced according to the person (like life insurance in SA).

## Dataset Overview

A data set, called insurance.csv, is provided containing medical insurance claims for anonymous clients in the US. The dataset contains some information on the clients which might have some correlation with the total amount of all claims (charges). You can assume that all clients in this dataset have the same exposure: i.e., all claims for all users are taken over the same period of time. 

Here, exploratory data analysis will be performed and visualisations of this dataset will be provided to answer questions based on the data. Ostensibly, the purpose of this dataset is to find correlations between total medical costs and the other factors.


The insurance data contains the following:

• age: age of primary beneficiary.

• sex: gender of the primary beneficiary: female, male.

• bmi: body mass index. Gives a relationship between weight and height, providing an objective index of body weight (kg/m2) using the ratio of height to weight, ideally 18.5 to 24.9. There is a BMI chart in the datasets.zip file.

• children: number of children covered by the insurance plan (or how many dependents there are).

• smoker: if the primary beneficiary is a smoker.

• region: the primary beneficiarys residential area in the US: northeast, southeast, southwest, northwest.

• charges: total medical costs (claims) billed to the insurance company for this period.

• premium: monthly premium paid by the client for this insurance plan.
