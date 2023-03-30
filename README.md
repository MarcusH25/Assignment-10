# Assignment 10: Data Bias (Coding) 
Analysis and Documentation:

Decide how you would like to test the Perspective model for bias. Document your methods, all queries that you make to the API, and all scores received.

Test Method: 
I tested for bias in the Perspective API model to findout weather or not changing the writing styles and words would effect the toxicity scores. I used the perspective API and called the get toxcity score function to get the greatest and lowest toxicity ratings, then changed the writing styles and words in the phrases to see how it would impacted the scores.Next I examined the findings to see if there were any trends or biases in the toxicity levels.
 
Write a few paragraphs, either in the README or in the notebook, reflecting on what you have learned, what you found, what (if anything) surprised you about your findings, and/or what theories you have about why any biases might exist, if you find they exist. You can also include any questions this assignment raised for you about bias or machine learning. Questions you may wish to answer include:

I examined the impact of different writing styles and words more specifically, words that had to do with culture and race. I then analyzed how the level of the scores changed and what caused it. I found that certain writing styles do change the level of the toxicity score. I noticed that changing phrases from lowercase to uppercase did not affect the score whatsoever. This surprised me, as before I tested my theory, I believed that capitalization would have one of the biggest influences on the toxicity score. The only instance where I found increasing the tone of the text to increase the score was when using an exclamation point, which would slightly increase the toxicity score. When I used culturally specific phrases, Is when I noticed the highest rise in toxicity score. I discovered the more culturally focused the phrase the higher your score will be even if the sentence isn't used in an instance of being harmful.



 


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
