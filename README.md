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
4. Evalution, Testing ,Tuning till satisfaction.


## Outcomes/ USP
The USP of the product is it aims for a more structured and healthier consumption of ready to eat, order to eat meals for regular consumers to promote a healthier lifestyle.
Therefore the outcome of the project is hopeful towards developing a model that can recommend items based on user utility in this domain.

## Current status 
 1.Dataset generation: An intermediate method of using language models to judge the nutrition content and calorific count for each dish based on its description.
 
 2.User utility generation: being generated as per need. Instead of time series, meals are being averaged out by total calories per day/ number of meals. Implicit criteria are frequency of attribute,browse time.
 
 3.Utility function: An IU-SLSQP (Implicit utility with Sequential Least square optimizer for non linear programming) for tastes with explicit utility for Nutrition price and rating combined over a Multi Atribute Utility Theory function (MAUTF). IU-GA (Genetic algorithm also explored)
 
 4.Evaluation: base results run, with acceptible outcomes.

## Future Scope
 1.building an app/web interface.
 
 2.using the said interface for crawlers to collect implicit utility data, ie. frequency of attribute,browse time.
 
 3.domain expertise oriented tokenisation of estimation of nutrition content for language model being used.Lot of scope in the fine tuning of LLM based data generation.
 
 4.Suggestion on the model itself. Domain experts based utility functions finetuning
 
 5.Further testing and implementation of results with real users.
