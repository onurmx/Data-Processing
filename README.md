# Data-Processing
This repository contains me and my colleague's training exercises for data processing in R language course.

## Data
We used three anonymized dump of all user-contributed content on the Stack Exchange network for data. Each archive contains 8 tables in XML format:
1. Badges
2. Comments
3. PostHistory
4. PostLinks
5. Posts
6. Tags
7. Users
8. Votes

## Notebook 1(Individual Work)
Prepared scripts / modules allows for automatic data loading (from any forum) based on the given path. Moreover, written code / functions prepare data for analysis, i.e., the variables containing dates are being transform into correct format and all missing values is being denoted as NA. It also prepares a short report containing explanatory analysis of chosen sets:
1. Description of available variables
2. Basic statistics concerning them
3. Information about missing values
4. etc.

## Notebook 2(Group Work)
Purpose of this part is a data science challenge - which we create interesting questions and generate answers to them. We are interested in issues related to specific websites, but also comparisons between sites. The state of “today” and trends over time. Popular stuff and rarities. Differences and similarities.

In this part:
1. We used three data sets - one of which has size of > 100MB
2. We wrote the code that generates interactive charts, animations, data structures and etc.
3. We tried to implement techniques which enables the improvement of the speed of analyzes performed methods known from the literature(with our modification).
