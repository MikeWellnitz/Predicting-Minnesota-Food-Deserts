# Predicting Minnesota Food Deserts

## Research Question
Despite considering multiple topics to build our model around, including personal beverage choices, sports analytics, diagnostic medical data, air quality data, and other weather, or natural disaster data, we elected to build out a model around census data that specifcally concerns food accessability. As a group we agreed that an easily accessible, single source dataset, would offer the simplest route to quickly building a model. You can find the chosen dataset at [USDA Economic Research Service](https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/) site, "Food Access Research Atlas Data Download 2019."

_Can I create a model using census tract data that could be used to predict food deserts in Minnesota and achieve at least 75% accuracy?_

## Data Cleaning
The Excel file was downloaded and resaved as a CSV, before being cleaned in Jupyter Notebooks. From here the data was cleaned using the Pandas library, before coding the model, using the same Jupyter Notebooks file.

### Languages and Libraries
+ Excel
+ Jupyter Notebooks
+ Pandas
+ Matplotlib
+ Mensorflow
+ Scikit-Learn
  + StandardScaler
  + train_test_split

## Creating the Model
Once the dataset and all its data points were understood and determined to be of value to building the model, the data was cleaned and filtered. A first attempt was made to build an intial model. I was more accurate thatn anticipated! Some considerations regarding the data needed to be addressed. In response, the data was adjusted and the model was re-run (hoping/anticipating some type of change). The model ran a little more accurately after this attempt and as a group we concluded this satisified the task requirements and that we had successfully built a model that answered our research question.

### Final Visualizations
The code concludes with a final visualization. The epochs range plot tracks the training loss over the amount of epochs that were run in the previous code. This visualization helps determine if were are using the correct approx. amount of epochs in our code, and if the model is either overfitting, or underfitting the data.

## Insights
The genesis of this project was whether a model could be created that could (in theory) be used by policy makers and community organizers to address the prevelance of statewide food deserts and food insecurity more broadly. This model seems to be in the right direcing towards achieving this objective. However, it is understood that the bounds and capability of the model have not been fully tested. It is possible  that the model could be tested using different variables from the same dataset, or perhaps even entirely different datasets altogether. How the model could be deployed in the future depends directly on the limits the model is capable of. 

### References
+ USDA Dataset (see above)
+ USDA [Documentation](https://www.ers.usda.gov/data-products/food-access-research-atlas/documentation/)
+ GitLab UofM Bootcamp Class Files
+ ChatGPT
