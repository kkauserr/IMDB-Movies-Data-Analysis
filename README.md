This project explores movie data collected from IMDB
 using the movies dataset from the ggplot2movies R package. The analysis is conducted in R Markdown and compiled into a PDF report.

The goal of this lab is to practice:

Data exploration
Data wrangling
Visualization
R Markdown documentation
Reproducible research

📦 Dataset

The dataset used is:
movies

From the package:
ggplot2movies

To install (run in R console only — NOT in the Rmd file):
install.packages("ggplot2movies")

Then in the R Markdown file:
library(ggplot2movies)
data(movies)

The dataset contains:
58,788 movies
24 variables

Key Variables
Variable	Description
title	Movie title
year	Year of release
budget	Budget in USD (if known)
length	Length in minutes
rating	Average IMDB user rating
votes	Number of user ratings
mpaa	MPAA rating
action, animation, comedy, drama, documentary, romance, short	Binary genre indicators
r1–r10	Approximate percentage of users giving ratings 1–10

📊 Questions Addressed

The report answers the following:

1️⃣ Year Range
What is the oldest movie year?
What is the most recent movie year?

2️⃣ Budget Analysis
What proportion of movies include budget information?
What proportion do not?
Top 5 most expensive movies

3️⃣ Movie Length
Top 5 longest movies
Shortest short movie
Longest short movie

4️⃣ Genre Distribution
Number of movies in each genre (bar plot)

5️⃣ Average Ratings by Genre
Overall average rating per genre (bar plot)
Average rating per genre (2000–2005) (bar plot)

6️⃣ Genre Trends Over Time

For:
Action
Animation
Comedy
Drama
Documentary
Romance

Plot:
Number of movies per year
From 1990 to most recent year
All genres shown in one multi-colored line plot with legend

7️⃣ Additional Custom Questions
Three original analytical questions were formulated and answered.
At least one includes a visualization.

📁 Project Structure
├── Lab2.Rmd      # R Markdown source file
├── Lab2.pdf      # Knitted PDF output
├── README.md           # Project description

🛠 Requirements

Before knitting:
Ensure all required packages are installed in console:

ggplot2movies
dplyr
ggplot2
(optional: plotly)

🧠 Methodology

The analysis includes:
Data filtering
Handling missing values (NA)
Proportion calculations
Grouped summaries using dplyr
Bar plots and line plots using ggplot2
Clear markdown explanations (no explanations inside code chunks)
All steps are documented in markdown text to ensure clarity and reproducibility.

📄 Output

The final knitted PDF includes:
All code chunks
All outputs
All visualizations
Written explanations
Clean formatting

🚀 How to Run

Open Lab2.Rmd in RStudio
Make sure required libraries are installed
Click Knit → Knit to PDF
Verify that the generated PDF matches the submitted file

🎯 Learning Objectives

This lab demonstrates:
Reproducible reporting with R Markdown
Exploratory Data Analysis (EDA)
Data visualization best practices
Clean documentation practices
Academic reporting standards
