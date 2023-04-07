<figure>
  <img src="newborn.png">
  <figcaption><div align="right"><sub>Lindsay Walden Photography</sub></div></figcaption>
</figure>

<br>

# Inferential Statistics Project: what will your baby's weight be? :baby_bottle:

Hello everyone, thank you for being here! :blush:

This project aims at predicting a newborn's weight, based on the knowledge of some variables related to the mother and the newborn itself. Therefore, we study how these variables influence the weight and see which of them play a relevant role in its determination. To achieve this objective, we first graphically represent the data, mainly using the `ggplot2` package, performing hypothesis tests to verify possible correlations between them. Then, we carry out a feature selection procedure to find the best multiple linear regression model describing the observations, possibly considering non-linear effects and/or interaction terms.

We use the dataset present in the `newborns.csv` file. It contains data on 2500 newborns collected from 3 different hospitals. There are 10 variables for each observable:

- `Mother.age`: the mother's age;
- `Pregnancies.number`: the number of pregnancies the mother has already gone through; 
- `Smoker`: it is 0 if the mother does not smoke, otherwise it is 1; 
- `Gestation.weeks`: number of gestation's weeks;
- `Weight`: baby's weight, in g;
- `Length`: baby's length, in mm; 
- `Cranium`: diameter of the baby's cranium, in mm;
- `Birth.type`: birth type, Natural or Cesarean;
- `Hospital`: hospital, 1, 2 or 3;
- `Sex`: baby's sex, Male or Female.

You can see the HTML output of the R Markdown document by clicking on the link in the "About" section! 



