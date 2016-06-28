##Machine Learning Course Project

A random forest algorithm is used to predict a factor variable that represents the manner in which a group of particpants completed an exercise, from a number of inputs associated with exercise accelerometers. 

Code can be viewed [here](http://rpubs.com/ajg519/156161)

The data for this assignment comes from [here](http://groupware.les.inf.puc-rio.br/har), and contains information from belt, forearm, arm, and dumbbell accelerometers. The data are split into a training group (19,622) observations and testing group (20 observations). Participants in this study were asked to do a "Dumbbell Biceps Curl" in five different ways, including using correct form and four common mistakes. Participants were equipped with censors on the arm, belt and dumbbell itself.

The outcome of the random forest model is evaluated against a training set and has an out of sample accuracy rate of 99.7%. The final model was then used to predict against the real-world testing dataset provided.



