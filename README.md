# V1
Making food recommendations easy!

## Context
Due to fast-paced and long work environments, people are struggling to pay due to attention to their meals.
Most of these meals are **ready-to-eat either delivered** by restaurants or **packaged meals** from convinience stores. 
Due to the purpose of these meals they **cannot be a substitute for a balance diet**; Especially if they are consumed without dietary planning.
This can be contributed to high amounts of calories, fat, sugar, and sodium and lack of low in nutrients, such as fiber, vitamins, and minerals.
## Our Solution
Developing a **service that integrates with E-Carts** of food order, convenience store platforms and provide nutritional insights, statistics and **recommendations**, to help consumers make healthier choices, and enhance the **user experience in this trillion dollar market**.

## Scope of this hackathon.
For the scope of this hackathon, the focus will be on working towards the recommender system.
The current planned approach is to use a **temporal hybrid recommender system**, that combines collaborative filtering and Content based filtering, for time series data.

## Challenges
**Datasets**: Limited item options from particular convenience stores or restaurants limit the datasets.
**Bypassing Variance**: Reliance on user participation can be bypassed using content based filtering.
**Parameter Tuning**: Weighing the priority of a general healthy diet with user specialized data in forming recommendations.
Considerations for palette and budget
**Time Series Component:** Consideration of all meals consumed by the user on a daily, weekly, or monthly scale to form recommendations.

## Road map
1. Dataset generation: For pan vendor and vendor specific applications the datasets will seperate.
2. User utility generation: Based on various explicit / implicit considerations developing a user utility extraction function.
3. Utility function: making an accurate primary model that gives the most apt recommendations based on the extracted utility requirements of the user. Currently basing it on MAUT (Multiple Attribute Utility theory.)
5. Evalution, Testing ,Tuning till satisfaction.


## Outcomes/ USP
The USP of the product is it aims for a more structured and healthier consumption of ready to eat, order to eat meals for regular consumers to promote a healthier lifestyle.
Therefore the outcome of the project is hopeful towards developing a model that can recommend items based on user utility in this domain.
