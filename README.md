# Kickstarter-Success-Prediction
Predicting the success of kickstarter campaigns with machine learning

## Summary:

### Data exploration

1. Successful projects have smaller financial goals. 

2. Projects under spotlight have a 100% chance of success.

3. If the project is a staff pick, chance of success is doubled.

4. Many more successful projects set deadline to ~30 days after launch than failed projects, 30 day projects may produce a sense of urgency while giving enough time to find backers.

5. Categories with least success (<15%): Apps, Mobile Games, Web, Food Trucks

6. Categories with most success (100%): Shorts, Tabletop Games, Product Design, Documentary

### Machine learning:

1. Boosting model predicts success of a kickstarter project from the financial goal, category, time from creating the project to launching it, and the deadline set after launch, with 75% accuracy;
2. Top three features: (i) Financial goal; (ii) time from creation to launch; and (iii) sentiment of project name and blurb.

