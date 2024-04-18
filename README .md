# <a name="co2-emission-by-cars"></a>**CO2 Emission by Cars**
A reliable End to End Machine Learning Model to predict CO2 Emissions in different type of Cars.
### <a name="description"></a>**Description**
The task is to build a machine learning model to predict CO2 emissions by different types of cars based on features such as:

- Model of car
- Engine Size (in Litre)
- Number of cylinders
- Class of vehicle
- Fuel consumption (on highways, in city roads)

Project also aims at testing the influence of different independent features on the emission of CO2 using statistical methods.

**Predictive co2**

- Engine size
- Cylinders
- Fuel consumption city(L/100km)
- Fuel consumption Hwy(L/100km)
- Fuel consumption comb(L/100km)
- Fuel consumption comb(mpg)
- Fuel type
- Make
- Vehicle class

<a name="dataset"></a>DataSet:

- The dataset has been taken from the Canada Government official open data website and is available in [kaggle](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)
- Cleaned and processed version of the data can be accessed from [here](https://raw.githubusercontent.com/d0r1h/CO2-Emission-by-Cars/main/final_co2.csv)
- Dataset contains 7385 rows and 12 columns.

|<a name="notebook"></a>CO2 Emission|[](https://colab.research.google.com/github/d0r1h/CO2-Emission-by-Cars/blob/main/notebook/co2-emission-by-cars.ipynb)|[](https://www.kaggle.com/code/undersc0re/co2-emission-by-cars)|
| :- | :- | :- |
### <a name="models"></a>**Model**
We experimented with different methods for model building

`  `Navie bayes 
## <a name="project-pipeline"></a>**Project Architecture**
![ml-process.png](Aspose.Words.5ef29099-804f-4097-a073-cf270d502acf.001.png)

<a name="techstack"></a>**Packages**:Python-library pandas, numpy, seaborn, matplotlib,sklearn
## <a name="results"></a>**Results**
- Navie bayes (with alpha = 0.5) has been the most effective in reducing RMSE.
- The exact combination of features responsible for high CO2 emissions cannot be predicted Since all the features are highly correlated.

