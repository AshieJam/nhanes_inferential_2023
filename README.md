# nhanes_inferential_2023
## Google Collab

**Questions for Analysis**

   Use the questions below to guide your analysis. Remember to transform or recode variables where needed as specified, and determine the appropriate statistical tests that should be performed based on the question and variables.

   - **Question 1**: "Is there **an association** between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?"  
     - Variables: `DMDMARTZ` (marital status) and `DMDEDUC2` (education level). Recode as specified.

     **Ans** - Based on the Chi-Square test there was a statistically significant association between marital status and education level.

   - **Question 2**: "Is there **a difference in the mean** sedentary behavior time between those who are married and those who are not married?"  
     - Variables: `DMDMARTZ` (marital status, recoded) and `PAD680` (sedentary behavior time, cleaned).

     **Ans** - According to the t-test, sedentary behavior and marital status are related. Compared to single individuals, married individuals reported far less sedentary time.

   - **Question 3**: "How do age and marital status affect systolic blood pressure?"  
     - Variables: `RIDAGEYR` (age), `DMDMARTZ` (marital status, recoded), and `BPXOSY3` (systolic blood pressure).

     **Ans** - Age was a significant positive predictor of systolic blood pressure, according to the regression analysis, suggesting that blood pressure tends to increase with age. People who were married had a lower average systolic pressure than individuals who were single, which was a minor but significant effect of marital status.

   - **Question 4**: "Is there a **correlation** between self-reported weight and minutes of sedentary behavior?"  
     - Variables: `WHD020` (self-reported weight, cleaned) and `PAD680` (sedentary behavior time, cleaned).

     **Ans** - Weight and sedentary time move in the same direction, according to the correlation analysis: sedentary behavior tends to slightly rise as weight increases. Despite being statistically significant, the weak correlation (r = 0.16) suggests that there may be more relevant variables. 
     
     Weak: A correlation is weak if it falls between 0.1 and 0.5.


   - **Question 5 (Creative Analysis)**: Difference in Diastolic Blood Pressure by Kidney Failure.

Reason for analysis- It is known that high blood pressure is an indicator to kidney failure. Although systolic is mostly used I wanted to seek if there is a causation from the NCHS dataset. 

**Ans** - The results suggest that kidney health is associated with blood pressure levels. Individuals with weak or failing kidneys tended to show lower diastolic pressure
