## YouTube Comment Sentiment Analysis: AI Video Generator Models
This project's goal is for summarizing pros/cons of AI video generation tool in different aspects and overall precentage of positive/negative comments. Visualize as bar chart and radar graph.

##Method
*Codes are being run on the google Colab*
Use YouTube API to get the comments(reference:https://www.youtube.com/watch?v=SIm2W9TtzR0)
Insert Data in MongoDB as a database, read the database using spark library
Read the data preprocessed data, return results about the Strong and weaks of the certain ai

##How to run

It's not necessary to use MongoDB, but you can still connect to your own, you can jsut read the comment file u scratched,
remove the read MongoDB code replace as comments_clean <- read.csv("YOUR FILE NAME.txt")

## Requirements

### Option 1: Local Use (No MongoDB Required) 
- R (4.0 or above)
- R packages: "stringr", "ggplot2", "fmsb", "scales"
### Option 2: Local Use (No MongoDB Required) 
 library:"mongolite"


## Credit
This is my individual contribution to a group project, I worked on the code by myself. 
The work focused on data collection, preprocessing, sentiment modeling, and summary generation.
Sample comment from:https://www.youtube.com/watch?v=_o2MuUX9UYg
