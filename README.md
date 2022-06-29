An End-To-End Machine Learning for Air Quality Prediction deployment through flask

 Air quality is predicted based on it's factors associated with likewise the following factors has to given in order to get the quality percentage,
   average time in celcius,
   maximum temperature in celcius,
   minimum temperature in celcius,
   average relative humidity in percentage,
   total rainfall/snowmelt in millimetre,
   average visibility in kilometre,
   average windspeed in kilometre/hour,
   maximum sustain windspeed in kilometre/hour.
   
 The whole end-to-end model is developed by using ensemble methods which groups the weak learner and form a strong learner.
    The following are ensemble algorithms that are used in this model to predict the air quality,
    i)Decision tree:
          A decision tree is a flowchart-like structure in which each internal node represents a "test" on an attribute (e.g. whether a coin flip comes up heads or tails), each branch represents the outcome of the test, and each leaf node represents a class label (decision taken after computing all attributes).
    ii)Decision tree regressor:
          Decision tree regression observes features of an object and trains a model in the structure of a tree to predict data in the future to produce meaningful continuous output. Continuous output means that the output/result is not discrete, i.e., it is not represented just by a discrete, known set of numbers or values.
    iii)Lasso regression:
          Lasso regression is a regularization technique. It is used over regression methods for a more accurate prediction. This model uses shrinkage. Shrinkage is where data values are shrunk towards a central point as the mean. The lasso procedure encourages simple, sparse models (i.e. models with fewer parameters).
    iv)Linear Regression:
           Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.
    v)RandomForest:
           Random forests or random decision forests is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees.
    vi)XGBoost:
           Random forests or random decision forests is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees.
           
           
           
  The frontend is completely developed by using,
  HTML and CSS
  deployed through the python library called flask.
