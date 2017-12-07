# An analysis of World Happiness

## Objective
In this project, we look at the World Happiness Reports for 2015, 2016, and 2017 to analyze how certain factors correlate to a country's happiness. We also use variables from the dataset to predict happiness scores for countries and compare with the stats for 2017.

## Dataset
We pulled data from Kaggle: [World Happiness Report](https://www.kaggle.com/unsdsn/world-happiness/data)
We focus on the 6 factors: GDP, Family, Health (Life Expectancy), Freedom, Trust (Government Corruption), and Generosity. We use Dystopia Residuals as a benchmark against which we may compare the evaluation of a country’s happiness.

## Blog post
Here's our blog post with our findings and analysis: [What Makes Us Happy](https://medium.com/@bermanlucy19/what-makes-us-happy-73659cf89a0)

## Interactive Scatterplots
We created 7 interactive maps with the 2015 data to analyze the trend and correlation between each of the factors versus the happiness score for each country.
To see the interactive maps, you need to fire up a server on your local machine. Follow these steps:
* Type ```python -m SimpleHTTPServer``` into your console. This will automatically set the port to 8000. If you want to specify a port, you can type ```python -m SimpleHTTPServer <port number>``` instead
* Open your browser and type ```localhost:8000//filename```. For example, if you want to look at the graph of GDP vs. Happiness Score, replace ```filename``` with ```gdp.html```.
