dataset:https://www.kaggle.com/datasets/deepu1109/star-dataset

#Problem
I wanted to help people who wanted to figure out what type of star somethign is. This is the problem I tried to solve since I had a bunch of data about stars. I basically wanted to create a Machine Learning model but I did not know what type of Machine Learning model I should create or what I would be predicting with the model. Well, I had a lot of data so I decided that I would plot and create a bunch of graphs based off hte data and then determine what I wanted to do with it based on the patterns I see in the graphs. 

#Histograms
In the first part of the ipynb file I have a bunch of histograms that show me the frequency of temperature, star color, luminosity, radius, and Absolute Magnitute to help me find the relatoinship between wach of these proferties and start type and how many types each one of these happens based off of that star type. 

#Scatter Plots
In the next part the of the ipynb file, I wanted to see how spread out and the frequency all the stars were in a graph as single points. I wanted to see the density of each of the features and this helped me figure out what I wanted to figure out in my Machine learnign model

#Box Plots
#In the third part of the ipynb file I created a bunch of box plots to help me find relationships between the same 4 properties but to find the range of these properties. The box plots helped me compare the different properties better

#Analyze
I then analyzed all the graphs and determined that there was a direct relationshuo between the temerature and the luminosity so I determined that I wanted to create a model that can predict star type solely based on a given temperature. 

#model
I created a random forest classifier machine learning model to determint eh accuracy of the model where i used the first 80% of the data as actual data adn the rest 20% of the data as test to figure out how accurate my model was. I got a score of 1.0/1.0. I then decided I wanted a histogram of all the data and thats what I created. Lastly I addad a predictor where the user can ask the model what type of star something is based off the temperature they enter.
