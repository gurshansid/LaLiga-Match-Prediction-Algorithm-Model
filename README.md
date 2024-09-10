<h1>LaLiga-Match-Prediction-Algorithm-Model</h1>

<h2>Description</h2>
This is a machine learning model that can predict matches from the Spanish Soccer League (LaLiga). I started by scraping LaLiga match result data from the last eight seasons. I then parsed the HTML of this match data, looking for the extraction of win/loss factors like shooting stats, where the match was played, etc. to create a Pandas dataframe that contains over 5300 instances of matches along with their extracted attributes. The dataframe is attached as a csv file. I applied a random forest machine learning algorithm to this dataframe that used multiple predictors (venue, opponent, time, day) to predict a given match’s outcome. Initially the precision of the algorithm was 46%, but I was able to improve it to 56% by retraining the algorithm using the rolling averages of the previous predictors as new predictors. I was able to improve the model a tad bit more to 59% accuracy in its predictions by combining home and away match predictions. I will improve the algorithm's accuracy and revisit this project as I learn more about machine learning!
<br />


<h2>Languages and Libraries Used</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>Requests</b>
- <b>BeautifulSoup</b>
- <b>scikit-learn</b>


<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
