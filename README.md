# NFL-Draft-Predictions
Predicting round of draftee from combine performance

## Project Goal:
   #### Predicting whether (and in which round) a given combine performer will be drafted based upon their results at the event
## Process:
   #### Scrape data from past 20 year of combine performances
   #### Clean player names, school names, and impute universally valid values (round 8 for undrafted players, 22 for mean age)
   #### Handle more crucial missing values by imputing a postional mean with a penatly of .5 standard deviations (add/sub depending on event)
   #### Explore relationships in the cleaned data - scatter matrix, barplot, histogram, etc
   #### Apply a range of modeling techniques such as Random Forest, K-Nearest-Neighbors, and XGBoost to make predictions (both binary and multi)
##  Repo Contents

   #### NFL-Draft-Predictions Notebook - includes both binary-class (drafted/undrafted) and multi-class (round drafted)
   #### Further-Investigations - does incorporating college production and twitter sentiment help improve accuracy of models?
   
- ### Impute penalized postional means for missing values
   
   <br>
    <p align = "center">
      <img src = "/Graphs/impute_nan.png" width = 700>
    </p>
   <br>

- ### Investigate correlations via scatter matrix
   
   <br>
    <p align = "center">
      <img src = "/Graphs/scatter_mat.png" width = 700>
    </p>
   <br>
   
- ###  Distribution of draft pick by round
   
   <br>
    <p align = "center">
      <img src = "/Graphs/round_dist.png" width = 700>
    </p>
   <br>
   
- ### Average draft round by position
   
   <br>
    <p align = "center">
      <img src = "/Graphs/round_by_pos.png" width = 700>
    </p>
   <br>
   