# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Regression and classification with housing data
## This project was part of my Data Science immersive course at General Assembley Sydney.  The dataset required a significant amount of cleaning and feature engineering in order to be ready for modelling.  I had the opportunity to implement many exploratory analysis and python data munging techniques.  The nature of the data having a high number of features allowed for some interesting insight into the process of feature selection via a variety of approaches.  I was also able to compare quite a few different modelling approaches in both regression and classification.  To exhibit some of my visualization skills I did a plotly viz of the effects of l2 regularization (ridge) on my feature coefficients.  This viz is useful to understand the effect of the changing alpha penalty on the feature weights.
## Business Case

You work for a real estate company interested in using data science to determine the best properties to buy and re-sell. Specifically, your company would like to identify the characteristics of residential houses that estimate the sale price and the cost-effectiveness of doing renovations.

There are three components to the project:

1. Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. Your goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
3. Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).

This project uses the [Ames housing data recently made available on kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## Directions

Though the housing data for this project is very rich, it is not trivial to clean and prepare for modeling. Good EDA, cleaning, and feature engineering will be critical to the success of your models. Always remember to think critically about the data before modeling. The computer can't be the researcher for you!

The first two parts of the project are regression problems. There are potentially hundreds of features and plenty of multicollinearity, so regularization is definitely recommended.

The second question involves fitting a regression on the residuals of the first model. This is a practice that "covaries out" any effects of the predictors in the first model before investigating the effects of predictors in the second model.

The third section of the project is more challenging and involves dealing with significant class imbalance. This is a common and tricky problem in real-world classification tasks. We leave it up to you to decide how you want to tackle this problem and devise a solution, and highly recommend doing your own research into the topic.

We will be looking for the following things:

- Detailed EDA with justification for the steps. Visualize your data with pandas, matplotlib, or other plotting libraries. Explain the variables you choose for your models.
- Detail your choice of regression and classification models for the task. Include Markdown explaining your justification, results, and interpretation of your models. Make sure your code is clean and clear.
- Remember to frame your results according to your goals outlined in the project prompts.

---

## Requirements

- Materials must be in a clearly commented Jupyter notebook
- You should demonstrate the ability to:

    - Analyze a complex dataset & explicitly state your assumptions.
    - Clean, impute, and explore the dataset.
    - Justify your modeling choices and feature engineering.
    - Plot, visualize, and interpret your data logically.
    - Clearly outline your modeling strategy in response to the questions
    - Explain your results to a technical audience.

---

### Project Feedback + Evaluation

For all projects, students will be evaluated on a simple 4 point scale (0, 1, 2 or 3). Instructors will use this rubric when scoring student performance on each of the core project **requirements:** 

 Score | Expectations
 ----- | ------------
 **0** | _Did not complete. Try again._
 **1** | _Does not meet expectations. Try again_
 **2** | _Meets expectations._
 **3** | _Surpasses expectations. Brilliant!_
 
| Requirement | Rubric   |
|------|------|
|   Materials must be in a clearly commented Jupyter notebook  | |
|   Analyse a complex dataset & explicitly state your assumptions  | |
|   Clean, impute, and explore the dataset  | |
|   Justify your modeling choices and feature engineering  | |
| Plot, visualize, and interpret your data logically ||
| Clearly outline your modeling strategy in response to the questions ||
| Explain your results to a technical audience ||

__Qualitative feedback:__
