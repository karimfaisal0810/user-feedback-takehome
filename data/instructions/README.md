You are given a dataset containing user feedback collected from a product.
The feedback includes a numerical rating and a short free-text response.

Your task is to analyze this data and extract meaningful insights that could help a product team understand user issues.

This assignment is designed to assess:

Logical thinking

Basic data analysis skills

Ability to work with text data

Clarity of explanation

File location:data/feedback.csv
----------------------------------------------------------------------------------------------------------

The dataset contains the following columns:

feedback_id – unique identifier for each feedback

created_at – date the feedback was submitted

rating – integer value from 1 (lowest) to 5 (highest)

feedback_text – free-text user feedback

----------------------------------------------------------------------------------------------------------
Tasks
1️. Identify Problematic Feedback

  Define a clear rule to identify problematic or negative feedback.
  The rule can be based on:

  * rating

  * feedback text

  * or a combination of both

  * Explain why you chose this rule.

  There is no single correct answer — we are interested in your reasoning.
---------------------------------------------------------------------------------
2. Create Issue Categories

  Based on the feedback text, create 3–4 issue categories.

  Categories should be:

  * Simple

  * Mutually exclusive (one feedback → one category)

  * Explain how you identified these categories.
---------------------------------------------------------------------------------
 3. Apply Your Logic Using Python

  Assign one issue category to each feedback.

  Use Python to show:

  * Number of feedback entries per category

  * Average rating per category

  * You may use any Python libraries you are comfortable with.
  No machine learning is required.
---------------------------------------------------------------------------------
4️ Validate Your Approach

  Provide 2 examples where your categorization might be incorrect.

  Briefly explain why these cases are difficult to classify.
---------------------------------------------------------------------------------
5️ Recommendation

Based on your analysis, answer:

  * Which issue category should the product team prioritize fixing first, and why?

  * Support your answer using data from your analysis.
---------------------------------------------------------------------------------
Tools & Guidelines
Python is preferred
Google Colab is acceptable
Keep the solution simple and readable
Focus on clarity of logic over complex techniques

---------------------------------------------------------------------------------
Submission Instructions
  Fork this repository

  Add your analysis file (notebook or script)

  Update the root README.md with:

  Your approach

  Assumptions made

  Limitations of your solution

  Share the link to your GitHub repository
---------------------------------------------------------------------------------
  
  **We value clear thinking and reasoning more than perfect code or advanced techniques.**
