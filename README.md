<h2> Project Comparing Products by Ingredients</h2> 
The dataset has been cleaned to focus on the 'INGREDIENT', 'ADVANTAGE', and 'DISADVANTAGE' columns, and a function has been created to search for a specific ingredient. When searching for "Wheat Gluten," the function successfully retrieves its advantages and disadvantages. The advantage column for this ingredient is empty, while the disadvantage is listed as "not for people with autoimmune disorder celiac disease." This setup allows us to query the dataset for insights on various ingredients by name.

Buying new pre packed products is difficult. It can even be scary for those who have sensitive skin and are prone to skin trouble. The information needed to alleviate this problem is on the back of each product, but it's tought to interpret those ingredient lists unless you have a background in chemistry.

Instead of buying and hoping for the best, we can use data science to help us predict which products may be good fits for us. In this Project, you are going to create a content-based recommendation system where the 'content' will be the chemical components of cosmetics. Specifically, you will process ingredient lists for 1472 cosmetics on Sephora via word embedding, then visualize ingredient similarity using a machine learning method called t-SNE and an interactive visualization library called Bokeh.

This Project lets you apply the skills from Manipulating DataFrames with pandas, Chapter 1 of Dimensionality Reduction in Python, and Interactive Data Visualization with Bokeh. This Project also includes the concepts of natural language processing and word embedding, which you can learn about in Natural Language Processing Fundamentals in Python.


<h3>Project Overview</h3> 

The project aims to create a content-based recommendation system to predict which cosmetic products may be suitable for users based on their ingredient lists. The project will use word embedding to process ingredient lists for 1472 cosmetics from Sephora and visualize ingredient similarity using t-SNE and Bokeh.

<h3> Challenges</h3>
Interpreting the ingredient lists on cosmetic products without a background in chemistry
Finding suitable cosmetic products for users with sensitive skin and those prone to skin trouble

<h3> Proposed Solution </h3>
Create a content-based recommendation system where the 'content' will be the chemical components of cosmetics
Process ingredient lists for 1472 cosmetics on Sephora using word embedding along with personalized dataset focusing indian market.
Visualize ingredient similarity using t-SNE and Bokeh

<h3> Skills Needed </h3>

Manipulating DataFrames with pandas
Dimensionality Reduction in Python
Natural Language Processing Fundamentals in Python
Interactive Data Visualization with Bokeh

<h3>Project Outline</h3>

Data Preprocessing
Word Embedding
Ingredient Similarity Visualization
Building the Recommendation System

<h3>Expected Outcome</h3>

A system that can predict suitable cosmetic products for users based on their ingredient lists, making it easier for users to find products that are safe and beneficial for their skin.

# Project Tasks

1. Cosmetics, edible items chemicals... it's complicated
2. Focus on one product category and one skin type
3. Tokenizing the ingredients
4. Initializing a document-term matrix (DTM)
5. Creating a counter function
6. The Cosmetic-Ingredient matrix!
7. Dimension reduction with t-SNE
8. Let's map the items with Bokeh
9. Adding a hover tool
10. Mapping the cosmetic items
11. Comparing two products
