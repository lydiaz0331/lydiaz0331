Hall of Fame Predictive Modeling Project
-------------
-	The business insight of this project comes from the fact that now excellent NBA players are getting drafted by small market teams then leaving or demanding a trade 
-	We want to build a model which can evaluate potential value of the player, both on and off the court

  -	Model: **Logistic Regression, LDA, QDA.**
  - Data Source:
    - Career data of 1000 top NBA scorers. Calculated new stats and initialized binary variables in Excel.
    - 2015 Player info. This was used exclusively to determine if a player retired in time to be in the Hall of Fame as of 2018.
    - Hall of Fame data. List of all players in Hall of Fame.
    - All Star data. Used to calculate career All-Star appearances within main data set.
  - Final Result:
    - ROC Curve shows that QDA gives the best result
    - The model performs very well when using the NBA players’ metrics to predict their possibility of presence at HOF.
