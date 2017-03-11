---
layout: page
title: Interests
---
## Data Science 

Apophenia is the human tendency to perceive meaningful patterns from randomn data. A visual representation of this is the apparent skull in the flower below: 

![flower]({{ site.url }}/public/flower.jpg)


The explanation put forth by evolutionary psychologists for apophenia is that it is not a defect of human cognition, but selected for. This is due to the asymmetrical cost of Type I and Type II (not recognizing a pattern that does exist) errors. For example, someone might hear a noise that sounds like a predator growling. If he believes that it is a predator, but it's just the wind, the cost is only losing a moment's travel time to stand on guard. If he believes that it is just the wind and it actually is a predator, the cost is his life[1].


![comic]({{ site.url }}/public/comic.png)
The XKCD comic "Feedback" by Randall Munroe.

[1] http://theness.com/neurologicablog/index.php/hyperactive-agency-detection/

## Python & Open Source Tools

Kaggle is a website where users submit data from unique sources, and have competitions to see who can extract the best insights from the data. One project that caught my eye, is the best time to head to the UC Berkeley Gym, based on a number of factors: time of day, day of week, weather, start of summer (true or false), etc. 

Here is a link to the project page:
<a href="https://www.kaggle.com/nsrose7224/crowdedness-at-the-campus-gym">Crowdedness at the campus gym</a>

The data comes in csv format, and the analysis is conducted in python using the Sci-kit learn module (machine learning), to train a model of features, and predict the best guess for crowdedness at the gym, based on other observable factors (time of day, day of week, weather, etc). The goal is maximize the model accuracy, by selecting the best features, and running regressions on those features. 

Below is a correlation matrix from the top user in the competition, showing the sensitivity of different features: Clearly time of day and weather are strong feautures, as one would expect. This model is able to predict with scores in the low 80s.
![corr]({{ site.url }}/public/corr.png)

To learn more about the model and implementation, checkout the author's GitHub Page :<a href="https://github.com/nirajvermafcb/Data-Science-with-python">Data Science with python</a>
