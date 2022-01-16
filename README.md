#  Mod20_Segment_1
By the end of this module segment, we will have created the foundation for the final project. By defining roles between team members and establishing a communication structure. Additionally, Decide on a topic for the project—think of a question that can be answered using data. Create a repository for the project and invite the other team members to join. Source a dataset that will suit your needs (you can even use multiple datasets if applicable). Begin to clean, organize, and perform exploratory data analysis on your datasets so that they're ready for analysis. Include mockups of a machine learning model and a database.

# Purpose 

First Segment: Sketch It Out: Decide on your overall project, select your question, and build a simple model. You'll connect the model to a fabricated database, using comma-separated values (CSV) or JavaScript Object Notation (JSON) files, to prototype your idea.


# Presentation 

![D11a](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D11a.PNG)

1. Google Earth
A Data frame was completed with data from the following sources; 
[Artic] - (https://earth.app.goo.gl/mYp7Ao)
[Antarctica] -(https://earth.app.goo.gl/1NveLo)

To product the following:

- seaice_extent_daily_v3.0.csv.

## Selected topic:

 Predicting when polar ice will be gone in the Artic and Antarctic using other scienctic features of global climate change by creating a database, ETL and Machine Learning Model.

![D11b](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D11b.PNG)

## Reason we selected the topic:

Polar Sea ice, found only in the Arctic and Antarctic, which is comprised of frozen ocean water. The amount of sea ice at each pole changes throughout the year, growing and shrinking. We will analyse data from sources from 1979 to 2018. And could expand this to 2022. Sea ice has an impact on the global climate from helping to regulate global temperature to affecting ocean currents and providing a habitat for wildlife. 

![D11c](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D11c.PNG)

## Description of the source of datasets:
![Daa](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/Daa.PNG)
1. [National Snow and Ice Data Center. NSIDC data on Google Earth. Accessed March 1, 2019](http://nsidc.org/data/google_earth)
2. [Climate Data Store](https://cds.climate.copernicus.eu/user/119111)
3. [Visualize Arctic and Antarctic Sea](https://livingatlas.arcgis.com/sea-ice/)
4. [Arcgis](https://developers.arcgis.com/javascript/latest/showcase/arctic-antarctic-sea-ice/)

## Questions we hope to answer with the features of the dataset(s):

###Dataset 1

![D3a](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D3a.PNG)

With this data we have extracted from the backend source that displays the Google Earth Map Video of the Polar Ice extent from the 1978 to Today. We extrated the data to .csv titled [seaice_extent_daily_v3.0.csv](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/seaice_extent_daily_v3.0.csv). And we imported the data using the following code [sea_ice_refactored](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/sea_ice_refactored.ipynb).
![D3a1](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D3a1.PNG)

With this data we can visually see the [Artic](https://earth.app.goo.gl/mYp7Ao) show more dramatic signs of climate change by reviewing the Sea Ice Extent sq2/ Km for years compared to 
[Antarctica](https://earth.app.goo.gl/1NveLo). 


###Dataset 2


1. Predicting when the polar ice will be gone in the Artic.

We want to explore the features of data within an 

2. Predicting when the polar ice will be gone in the Antarctic

## Description of the data exploration phase of the project 




## Description of the analysis phase of the project 

## Technologies, languages, tools, and algorithms used throughout the project 


# Github

* Description of the communication protocols:

We created a message group for direct messages with team members in Slack. Established a daily meetup time for everyone and a communication protocol in case of an emergency as follows: 
![D2a](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D1a.PNG)

* Individual Branches:
There is one branch for each team member as follows:
![D2b](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/D2b.PNG)

* Each team member has at least four commits for the duration of the first segment:

# Database 

Present a provisional database that stands in for the final database and accomplishes the following:
* Sample data that mimics the expected final database structure or schema based on the following: 


* Draft machine learning model is connected to the provisional database

# Technologies Used

•	Which tools are the best fit for your project?  
Jupyter Notebook, VScode IDE ,and Pandas to clean and drop fields.  
Javascript, HTML, CSS for building the webpage.  

•	What will be used for each section?  
Data gathering: Jupyter Notebook, Pandas  
Cleaning and dropping fields: Jupyter Notebook, Pandas  
ML section: Jupyter Notebook, Pandas, R, VScode IDE, Keras, Matplotlib, Scikit-Learn, TensorFlow  
Data Storage: SQLite, PostgreSQL, Mongo  
Interaction web page: VScode IDE, Javascript, HTML, CSS, Flask, D3.js library, Heruko 

•	How will the dashboard be built?  
The dashboard will be built on the right side of the web page, we can use the panel to play the visualized animation graph or show the data on a specific time.  

## Data Cleaning and Analysis
Pandas will be used to clean the data and perform an exploratory analysis. Further analysis will be completed using Python.

## Database Storage
Mongo and/or Postgres is the database we intend to use depending on the size of the data.

# Machine Learning Model

We will present a provisional machine learning model that stands in for the final machine learning model and accomplishes the following:

* Takes in data from the provisional database
* Outputs label for input data

#### Questions
* Which model did you choose and why? We will use a supervised machine learning model to split the historical data into training and testing data.
* How are you training your model? We will use A RandomForest Classifier model to train the data
* What is the model's accuracy? To be determined
* How does this model work? The random forest classifier is a versatile classification tool that makes an aggregated prediction using a group of decision trees trained using the bootstrap method with extra randomness while growing trees by searching for the best features among a randomly selected feature subset. Each individual tree in the random forest spits out a class prediction and the class with the most votes becomes our model’s prediction.

![image](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/RFC.jpeg)

We will use the historical sea ice data from NSIDC. along with several features to train and test the data and predict the accuracy. Depending on the accuracy, we will subsequently also use Keras and Tensor Flow to build a Deep Neural Network Model to improve accuracy.

The model has been designed to:
* pre-process the data
* create OneHotEncoder instance
* split, train and test the data
* create StandardScaler instances

We will be using the following libraries:
* Keras, including activation functions, layers, objectives and optimizers for the deep learning model
* Matplotlib – including pyplot and scatterplots to plot accuracies etc
* Scikit-Learn – to pre-process the data, regression and build the algorithm.
* TensorFlow – to develop the deep learning model

![image](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Mock%20ML%20Model/images/1.PNG)

![image](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Mock%20ML%20Model/images/2.PNG)

![image](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Mock%20ML%20Model/images/3.PNG)

# Dashboard

For our Dashboard and Website we would like to connect to the Dataset via Live Data API, Extraction and build the graphs interactivly with the live data connection to Dataset #1.
It will be hosted on Heroku.

## Result of analysis 

1. While Cleaning Data : We Created an ERD with species extintiction level and determinded after ERD that we will need alternate Data Sources 
 
![DNU_ERD](https://github.com/ALIYA2Group/Mod20_Segment_1/blob/main/Pictures/DNU_ERD.PNG)

## Recommendation for future analysis 

## Anything the team would have done differently 

