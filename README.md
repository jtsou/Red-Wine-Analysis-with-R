# Red Wine Analysis with R
<h3> Chemical Properties </h3>
<ul>
<li>fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily) (tartaric acid - g / dm^3)</li>
<li>volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste (acetic acid - g / dm^3)</li>
<li>citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines (g / dm^3)</li>
<li>residual sugar: the amount of sugar remaining after fermentation stops (g / dm^3)</li>
<li>chlorides: the amount of salt in the wine (sodium chloride - g / dm^3</li>
<li>free sulfur dioxide: he free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion (mg / dm^3)</li>
<li>total sulfur dioxide: amount of free and bound forms of S02 (mg / dm^3)</li>
<li>density: the density of water is close to that of water depending on the percent alcohol and sugar content (g / cm^3)</li>
<li>pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic)</li>
<li>sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels (potassium sulphate - g / dm3)</li>
<li>alcohol: the percent alcohol content of the wine (% by volume)</li>
</ul>
<h5>Output variable (based on sensory data):</h5>
<ul>
<li>quality (score between 0 and 10)</li>
</ul>
<h3> Data Exploration </h3>
The report explores a dataset containing wine quality and attributes for approximately 1599 red wines. 

All the chemical properties of the wine are explored for the first round. 
After that, I chose some interesting results for further investigation.
I created ggpairs for correlation in both numerical form and graphs. 



I then created three unique plots that illustrate how alcohol percentage is essential to the quality of red wine.
They are shown as below.
<h3>Final Plots and Summary</h3>

<h3>Plot One</h3>

<br>![Preview](https://github.com/jtsou/Data-Analysis-with-R/blob/master/Wine%20Density%20and%20Alcohol%20Percentage.png)<br>

<h5>Description One</h5>
<p>I created a new variable 'label' to show how alcohol percentage and wine quality vary. We can see that medium alcohol is the majority.</p>

<h3>Plot Two</h3>

<br>![Preview](https://github.com/jtsou/Data-Analysis-with-R/blob/master/Density%20and%20pH.png)<br>

<h5>Description Two</h5>
<p>From the scatter plot distribution, there is a negative relationship between density and pH. The lines are grown to see the ratings. The correlation we identified earlier suggested a relatively moderate relationship which is -0.342. The graph here also suggests that the lower the pH with density be between approximately 0.99 and 1, the rating of the alcohol would remain excellent.</p>

<h3>Plot Three</h3>

<br>![Preview](https://github.com/jtsou/Data-Analysis-with-R/blob/master/Wine%20and%20percent%20dist.png)<br>

<h5>Description Three</h5>
<p>The distribution of Alcohol Percentage and Wine Density is strong. The higher the alcohol percenrage, the lower is the density. We can also see in this plot that stronger wine tend to have higher rating.</p>

<h2> REFLECTION </h2>
<p>Based on the analysis I did for the dataset, I am convinced that alcohol concentrate is the most important factor to deciding the quality of Red Wine would be density. The lower the density, the higher the alcohol concentration, and the higher the alcohol concentration the better the quality of wine. One of the challenges I encountered however, is that although I like wine, I do not know the chemistry behind it. It was a little tough for me to wrap my mind around what might be the most important component in making a quality wine. After playing around with the variables and creating the plots, the results eventually made sense to me. I wish I could enhence my analysis by knowing which brands that are highly rated by consumers fit my prediction. This analysis serves as a rough idea of what makes a good wine and the audience can just go from there.</p>
