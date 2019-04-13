# Kaggle Google Analytics Customer Revenue Prediction
Competition website: https://www.kaggle.com/c/ga-customer-revenue-prediction

## Contents
- [Introduction](#Introduction)
- [Installation](#Installation)
- [Usage](#Usage)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Model Deployment](#Model-Deployment)
- [Contributing](#Contributing)
- [License](#License)

## Introduction

### Competition Description
<details>
<summary>Details</summary>
  
>The 80/20 rule has proven true for many businesses–only a small percentage of customers produce most of the revenue. As such, marketing teams are challenged to make appropriate investments in promotional strategies.
>
> RStudio, the developer of free and open tools for R and enterprise-ready products for teams to scale and share work, has partnered with Google Cloud and Kaggle to demonstrate the business impact that thorough data analysis can have.
>
> In this competition, you’re challenged to analyze a Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset to predict revenue per customer. Hopefully, the outcome will be more actionable operational changes and a better use of marketing budgets for those companies who choose to use data analysis on top of GA data.

*from [competition website...](https://www.kaggle.com/c/ga-customer-revenue-prediction)*

</details>

### Competition Evaluation
<details>
<summary>Details</summary>
  
> #### Root Mean Squared Error (RMSE)
> Submissions are scored on the root mean squared error. RMSE is defined as:
> \mathcal{W}(A,f) = (T,\bar{f})
> where y hat is the natural log of the predicted revenue for a customer and y is the natural log of the actual summed revenue value plus one.

> #### Submission File
> For each `fullVisitorId` in the test set, you must predict the **natural log** of their total revenue in `PredictedLogRevenue`. The submission file should contain a header and have the following format:
> ``` markdown
> fullVisitorId,PredictedLogRevenue
> 0000000259678714014,0
> 0000049363351866189,0
> 0000053049821714864,0
> etc.
> ```

*from [competition website...](https://www.kaggle.com/c/ga-customer-revenue-prediction)*

</details>

## Installation
* [NumPy](http://www.numpy.org/)
* [IPython](http://ipython.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](http://matplotlib.org/)

## Usage
To run this notebook interactively:

1. Download this repository in a zip file by clicking [here](https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction/archive/master.zip) or execute this from the terminal: 
```
git clone https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction.git
```
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with 
```
virtualenv env
```
4. Activate the environment with 
```
source env/bin/activate
```
5. Install the required dependencies with
```
pip install -r requirements.txt
```
6. Execute IPython notebook from the command line or terminal with
```
ipython notebook
```
7. Click on files with `.ipynb` extension on the IPython Notebook dasboard and enjoy!
8. When you're done deactivate the virtual environment with 
```
deactivate
```

## Exploratory Data Analysis
- [Data Exploration]()
- [Data Preprocessing]()
- [Feature Extraction]()
- [Feature Engineering]()

## Model Deployment

## Contributing
Please refer to [CONTRIBUTE.md](./CONTRIBUTE.md) for details. :heart_eyes:

## License
Kaggle Google Analytics Customer Revenue Prediction is released under the [MIT License](./LICENSE).
