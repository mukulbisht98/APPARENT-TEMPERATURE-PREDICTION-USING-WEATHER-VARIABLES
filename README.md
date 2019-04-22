# <h1 style="color: teal">APPARENT TEMPERATURE PREDICTION USING WEATHER VARIABLES</h1>
# <h1><span style="color: teal">INDEX :</span></h1>
I. [INTRODUCTION](#1)

II. [DATA CLEANING](#2)

III. [ELABORATORY DATA ANALYSIS](#3)
- [Corelattion in Data](#31)
- [Data Visualization](#32)

IV. [PREDICTING APPARENT TEMPERATURE](#4)

v. [SUMMARY](#5)
# <h1><a id='1' style="color: teal">I. INTRODUCTION</a></h1>
## <Li style="list-style-type: square"><span style="color: teal">Question Statement</span></Li>
Is there a relationship between humidity and temperature? What about between humidity and apparent temperature? Can you predict the apparent temperature given the humidity?

Statistics and Machine Learning can help us answer these questions and predict various relations and variables given the data.
Apparent temperature is the temperature that it feels like to our body because of other weather variables other than temperature.This is generally higher incase of high humidity.

In this project i am trying to predict the apparent temperature given other weather variables in an hourly manner.

<Li style="list-style-type: square"><span style="color: teal">Objective</span></li>
<li>Clean the data and drop useless columns.</li>
<li>Make a EDA report.</li>
<li>Visualize the distributions of various features and correlations between them.</li>
<li>Feature engineering to extract the correct features for the model.</li>
<li>Train a regression model to predict the apparent temperature.</li>
<h1><a id="2" style="color: teal">II. DATA CLEANING</a></h1>
<Li style="list-style-type: square"><span style="color: teal">Statement:</span></Li>
<li>Perform data cleaning using pandas library. Which includes replacing the miscoded information and handling missing data.</li>
<h1><a id="3" style="color:teal">III. EXPLORATORY DATA ANALYSIS</a></h1>
<Li style="list-style-type: square"><span style="color: teal">Statement:</span></Li>
<li>Make a Exploratory Data Analysis on the data using pandas.</li>
<li>Visualize distributions and correlation of features using seaborn and pandas</li>
<h1><a id="4" style="color:teal">IV. PREDICTING APPERANT TEMPERATURE</a></h1>
<Li style="list-style-type: square"><span style="color: teal">Statement:</span></Li>
<li>Build a linear regression model taking the selected features through feature engineering</li>
<li>Predict the apparent temp for the split test data(Use 30% of the data for test)</li>
<h1><a id="5" style="color:teal">V. SUMMARY</a></h1>
<h2>In this project i have done the following:</h2>
<h3>1. Performed data cleaning using pandas library. Which includes replacing the miscoded information and handling missing data.</h3>
<h3>2. Made a Exploratory Data Analysis on the data using pandas.</h3>
<h3>3. Visualized distributions and correlation of features using seaborn and pandas.</h3>
<h3>4. Built a linear regression model taking the selected features through feature engineering.</h3>
<h3>5. Predicted the apparent temp for the split test data(Use 30% of the data for test).</h3>
