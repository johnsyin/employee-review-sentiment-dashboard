# employee-review-sentiment-dashboard
This project aims to analyze the reviews for 6 company included Microsoft, Apple, Amazon, Facebook, Netflix and Google that are published on Glassdoor. The scraped data is downloaded from Kaggle: https://www.kaggle.com/petersunga/google-amazon-facebook-employee-reviews/version/2

#### Overview
![Alt text](/ReadMeMedia/overview.JPG "Optional Title")

#### Visualization #1
Shows ratio between positive/neutral/negative sentiments of **all 6 companies** to give a general idea.

Static:

![Alt text](/ReadMeMedia/first_graph_1.JPG "Optional Title")

On Hover:

![Alt text](/ReadMeMedia/first_graph_2.JPG "Optional Title")

On Click:

![Alt text](/ReadMeMedia/first_graph_3.JPG "Optional Title")

#### Visualization #2
Shows the ratings of **one company**.

Static:

![Alt text](/ReadMeMedia/second_graph_1.JPG "Optional Title")

On Hover:

![Alt text](/ReadMeMedia/second_graph_2.JPG "Optional Title")

Hover on graph #1 (To quickly compare between companies):

![Alt text](/ReadMeMedia/filter_1.gif "Optional Title")

#### Visualization #3

Shows the pros and cons with different color hued for **one company**.

![Alt text](/ReadMeMedia/third_graph_1.JPG "Optional Title")

#### Visualization #4

Shows the **adjectives mentioned** for **self-defined** aspects(time,benefit,salary,etc..).

![Alt text](/ReadMeMedia/forth_graph_1.gif "Optional Title")

#### Visualization #5

Shows the sentiment across the map of U.S. for **one company**.

![Alt text](/ReadMeMedia/fifth_graph_1.gif "Optional Title")

#### Filters 

Including changing the company for the **one company** visualizations, the date of reviews, and type of employee(former/current).

![Alt text](/ReadMeMedia/filters.gif "Optional Title")

###### Note that the .ipynb file is the Python file that preprocess the data from kaggle "employee_reviews.csv" to "employee_reviews_processed.csv" as the sentiment in this project is classified using Python and not Javascript.
