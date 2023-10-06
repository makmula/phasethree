# Phase 3 README

## Overview

This project aims to address a critical business challenge faced by our client, a leading sports agency with strategic collaborations within the NBA. The focus is on leveraging data-driven insights to optimize talent management in professional basketball, specifically predicting the likelihood of NBA players remaining in the league for five or more years. The primary objectives include developing a robust predictive model, enhancing talent scouting and recruitment strategies, implementing proactive measures for risk mitigation, and fostering strategic collaborations with NBA teams.

## Business and Data Understanding

### Stakeholder Audience

The primary stakeholders for this project are:

1. **Sports Agency Leadership:** The leadership team seeks actionable insights to make informed decisions regarding player recruitment, resource allocation, and talent development.

2. **Player Agents:** Agents representing NBA players benefit from a predictive model that aids in negotiating contracts and guiding players toward a successful and enduring career.

3. **NBA Teams:** Collaborations with NBA teams are crucial. The insights derived from the model can enhance negotiations, player representation, and strategic planning for both the agency and the teams.

### Dataset Choice

The dataset choice involves a comprehensive collection of data, including player statistics, and other relevant features. The dataset will be curated from reliable sources, ensuring its accuracy and relevance to the predictive modeling objectives.

## Modeling

The core of the project lies in developing a predictive model for NBA player longevity. Key steps include:

1. **Data Preprocessing:** Cleaning and preparing the dataset for analysis, handling missing values, and ensuring data quality.

2. **Feature Selection:** Identifying and selecting relevant features that significantly impact player longevity in the NBA. The Feature of choice was Recall. 

3. **Model Development:** Employing advanced machine learning techniques to build a robust predictive model. Models include logistic regression, and decision trees. We tuned the hyperparameters to help us get to the best posible model we could.  

4. **Evaluation Metrics:** Using appropriate evaluation metrics such as accuracy, precision, recall, and F1 score to assess the model's performance. In finalizing the model we used Recall due to how we want to focus on, True negitives and postives. 

5. We used a used a decision tree which is a non-parametric supervised learning algorithm, which is utilized for both classification and regression. We also used logistic regression which estimates the probability of an event occurring, such as voted or didn't vote, based on a given dataset of independent variables.

## Evaluation

The evaluation phase involves a thorough assessment of the developed predictive model. Key aspects include:

1. **Model Performance:** From the base model to the final model we imporves our recall by 4%, going from 0.81 to 0.85. Below we show the diffrence in our test data between our baseline model (logistic regression) and our best model (Decision tree) 
<img width="377" alt="Screenshot 2023-10-06 at 1 11 54 PM" src="https://github.com/makmula/phasethree/assets/141356197/79d0541f-cc17-4872-b8fe-5d30111007df">
<img width="378" alt="Screenshot 2023-10-05 at 12 06 37 PM" src="https://github.com/makmula/phasethree/assets/141356197/69607d53-d513-40c4-8061-1053aadff47d">


   
2. **Business Impact:** Linking model predictions to real-world business impact, such as optimized recruitment strategies, enhanced player support, and improved return on investments. Our model will improve the way clinets find who is worth working with. 

## Recommendations

**Decision tree:** We recommend using our Decision tree model because of how well it our recall responded. With this we can predict with a high degree of confidence which players have staying pro for 5 plus years. 

## Conclusion

In conclusion, this project represents a pivotal initiative for our sports agency client, offering the potential to revolutionize talent management strategies within the NBA. By combining advanced analytics with domain expertise, we aim to provide actionable insights that empower the agency to make strategic decisions, maximize player potential, and strengthen its position as a leader in the sports industry. The predictive model developed in this project is not just a technical achievement but a catalyst for positive business transformation, benefitting players, agents, and NBA teams alike.

## Next steps
Our model was pretty good at classifying which players would not have a long career in the NBA, but we'd like it to do better at classifying the players who WOULD. For our next steps we could've:

Added weight to each collumn based on how impactful that is to the game of basketaball.
Gone more into depth on the F-1 scores and how they may impact our which model to pick from.
Looked at newer data and more stats in the NBA.
We could adjust the scaler through RobustScaler() that could help with the outlires in our data.



|--Phase3_Project
|   |--data
|   |--Phase 3 pres.pdf
|   |--README.md
|   |--Untitled.ipynb

