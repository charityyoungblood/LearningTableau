<!-- How to Use Tableau For Data Mining --> 

## Data Mining: the practice of examining large databases in order to generate new information### 

 How to Run A/B Tests in Tableau
 
 An A/B Test is a controlled experiment with TWO variants, A and B
  - A/B testing is a way to compare two versions of a single variable typically by testing a subject's response to variable A against variable B, and determining which of the two variables is more effective
 
  ## Step 1: Determine WHAT your DEPENDENT VARIABLE is 
    - Determine if you need to Move/Reorganize Your Dimensions and Measures 
    - In the "Churn Modeling" example - our DEPENDENT VARIABLE is "Exited" 
    - We want to see WHO exited the bank, so we move "Exited" to "Dimensions" in Tableau
    
  ## Step 2: Determine WHAT you are examining?
    - The most common A/B test is for Gender 
    - In the Churn Modeling example, we take Gender in order to answer the question: "If we hold all other variables EQUAL, we take a male customer and female customer, which one of them is MORE LIKELY to exit the bank?" 