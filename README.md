# A project to optimize advertisment in social medias 
##  The main goal of the project
The entire project we are currently working on is aimed at optimizing advertisement algorithms to improve advertising within the diffrent social medias. 
Our primary goal is to display our advertisements to as many people as possible who require our product while adhering to a fixed budget.
We refer to these individuals as our "target audience." The number of target individuals is contingent on various factors, such as a channel's subscriber count, 
the engagement rate of subscribers with channel posts, and the desire of those subscribers to purchase our product.
## What is the engagment rate?
When we mention the "engagement rate,"we are referring to the cumulative reactions, comments, and views a post receives within different timeframes and on various days of the week in a specific channel or page.
## Predicting advertisment prices
First we have made a model that predicts advertisment prices of a channel or page with some features of that like number of subscribers, the engagment rate, the community label of that channel or page and etc. The reason to do this is to estimate the advertisment prices of that channel based on its features
and compare it to the actual price that the owner of the channel or page offer. If the price is higher that what we have estimated, the prices of that channel is not good. But if it is less than that with a certain amount of threshold, we will add that channel to the list of channels that we may do advertisment on. The amount of threshold depends on the budget tht we have.
## Predicting engagment rate 
We've trained a neural network model that can predict the engagement rate of a post in a channel using specific datas of that post and channel like number of subscribers of channel, channel's community label, the time that the post has been posted and some other features. You can find detailed information about
this process in "result1.pdf" within the repository. The reason to do this is that calculation of the engagment rate of a post in a channel in each day takes time
and has some computational costs. So we can gather some data from the channel and predict the engagment rate of future posts in that channel. But we should update our data after some specific amount of time.
## Desire of subscribers
The subsequent tasks involve identifying the best community label that align with our product and identifying the related communities to that community label.
The first one can be easily done. The most realted topic to clothing products is clothing. But the second one is a little chalenging because a clothing product can be advertised in a channel which its community label is shoes but it is not okay to be advertised in a channel that its posts are about politics. 
In telegram this can only be done by doing some nlp procceses for community labels but in other platforms like instagram, it can be done by monitoring the overlap of different pages followers with different community labels.
## The final task
The final task is to choose the best set from the list that we have based on their prices, subscribers, engagment rate, 
 Our system has undergone extensive testing and can cater to a variety of usage scenarios. We have already attracted numerous customers 
and generated 50 million Tomans in revenue from this project.
