### Media Case Study: Understanding the Decline in Viewership

In this project, we analyzed the decline in viewership for a digital media company's show using linear regression models. Initially, the show saw high engagement, but viewership began to drop. Our goal was to identify the key predictors influencing viewership and understand the root cause of the decline.

#### Key Steps and Insights:
1. **Initial Hypothesis**:
   - We began by exploring whether a decrease in platform visitors was the primary cause of the viewership decline. 
   - Introduced variables like weekday/weekend patterns and the presence of a key character (Character A) to understand their impact on viewership.

2. **Model Development**:
   - **Iterative Approach**: We built 10 different models, refining them by adding and removing variables based on their significance.
   - **Lag Variables**: Included lag variables to capture the relationship between today's and yesterday's views, which showed that past viewership influences current viewership.
   - **Visitor Impact**: Reintroduced the 'Visitors' variable to test its impact against 'Views' and found it to become insignificant with more variables in the model.

3. **Key Findings**:
   - **Ad Impressions and Character A**: Identified these as significant drivers of viewership. Ad impressions were directly linked to marketing efforts, while Character A's presence strongly influenced viewership numbers.
   - **Visitor Patterns**: The model revealed that while the number of visitors initially seemed crucial, it became less significant as we included more specific variables.

4. **Model Validation**:
   - Achieved a high adjusted R-squared of ~80%, indicating our model explained the viewership pattern well.
   - The error analysis confirmed that our model accounted for all significant patterns, leaving only random errors.

5. **Actionable Insights**:
   - To increase viewership, focus on boosting ad impressions through increased marketing investment.
   - Leverage Character A's popularity, as their presence significantly boosts viewership.

By methodically building and refining our models, we provided a data-driven solution to understand and address the decline in the show's viewership, offering actionable strategies for improvement.
