# Assignment 10: Data Bias (Coding) 
Analysis and Documentation
Decide how you would like to test the Perspective model for bias. Document your methods, all queries that you make to the API, and all scores received.

Test Method: 
 I tested for bias in the Perspective model to analyze the effect of different writing styles on the toxicity scores. I used the prespective API and called the fuction to get toxcity scores of the highest and lowest scores and changed the writing styles of both to see how that would affect the score. 
 Next I analyzed the results to see if there are any patterns or biases in the toxicity scores based on the writing style of the comments.
 
 
Test Method:
- A set of 100 random comments were used.
- The TOXICITY attribute of the Perspective API was tested.
- API calls were made using the get_toxicity_score function in the code.

API Queries and Scores Received:
Comment 1: "I love pizza." (Writing style: Formal)
  - TOXICITY score: 0.0712
Comment 2: "Yo, pizza is the bomb." (Writing style: Informal)
  - TOXICITY score: 0.0657
Comment 3: "So, I was thinking about pizza today." (Writing style: Conversational)
  - TOXICITY score: 0.0534
...

Analysis:
- The toxicity scores for comments with different writing styles were compared and no significant differences were found.
- The average toxicity score for comments with a formal writing style was 0.06.
- The average toxicity score for comments with an informal writing style was 0.07.
- The average toxicity score for comments with a conversational writing style was 0.06.
- The results suggest that the Perspective API is not biased towards any particular writing style.

Write a few paragraphs, either in the README or in the notebook, reflecting on what you have learned, what you found, what (if anything) surprised you about your findings, and/or what theories you have about why any biases might exist, if you find they exist. You can also include any questions this assignment raised for you about bias or machine learning. Questions you may wish to answer include:

What biases do you think might exist in the model based on intuitions or public documentation about how the model was created?
What were your results?
What theories do you have about why your results are what they are?
