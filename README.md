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
My very first Kaggle competition, worked along with experienced seniors. This repository consists of my works which resembles one of my earliest interactions with data science and machine learning.

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
>
> <p align="center">
> <img src="https://latex.codecogs.com/svg.latex?RMSE&space;=&space;\sqrt{\frac{1}{n}\sum_{i=1}^{n}&space;\left&space;(&space;y_{i}&space;-&space;\hat{y}_{i}&space;\right&space;)^{2}}" title="root mean squared error" />
> </p>
>
> where y hat is the natural log of the predicted revenue for a customer and y is the natural log of the actual summed revenue value plus one.
>
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

## Usage
Few ways to run these notebooks interactively:

### Jupyter Notebook
<details>
<summary>Details</summary>
  
1. Download this repository in a zip file by clicking [here](https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction/archive/master.zip) or execute this from the terminal: 
```
git clone https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction.git 
```
2. Download the datasets at [competition website - data](https://www.kaggle.com/c/pubg-finish-placement-prediction/data).
3. Put both downloads in the same directory and unzip them.
4. For cleanliness, create a new folder **input** and put the datasets (with `.csv` extensions) into it.
4. Open Anaconda Prompt.
5. Navigate to the **repository folder** with
```
cd [path address]
```
6. Create a virtual environment with
```
conda create -n [environment name] python=3.7
```
7. Activate the environment with 
```
activate [environment name]
```
8. Install the required dependencies with
```
pip install -r requirements.txt
```
9. Execute Jupyter Notebook from the command line or terminal with
```
jupyter notebook
```
10. Click on files with `.ipynb` extension on the Jupyter Notebook dasboard and enjoy!
11. When you're done, deactivate the virtual environment with 
```
deactivate
```

</details>

### Google Colab
<details>
<summary>Details</summary>

1. Download the datasets at [competition website - data](https://www.kaggle.com/c/pubg-finish-placement-prediction/data).
2. Put all downloads in the same directory and unzip them.
3. For cleanliness, create a new folder **input** and put the datasets (with `.csv` extensions) into it.
4. Click on any model you want work with at the [**Model Deployment**](#Model-Deployment) section.
5. Copy the link of the page and paste it into the search bar of a new page.
6. Replace `https://github.com` with `colab.research.google.com/github` and hit enter.
7. Go to the sidebar, click on **Files** > **Upload**.
8. Upload all contents in the **input** folder.
9. You may now run the notebook.
10. Once you are done, remember to save the notebook somewhere.
  
</details>

### Kaggle Kernels
<details>
<summary>Details</summary>
  
1. Download this repository in a zip file by clicking [here](https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction/archive/master.zip) or execute this from the terminal: 
```
git clone https://github.com/y33-j3T/Kaggle-PUBG-Finish-Placement-Prediction.git 
```
2. Unzip your download.
3. Go to [competition website - kernels](https://www.kaggle.com/c/pubg-finish-placement-prediction/kernels).
4. Click on **New Kernel**.
5. Select **Notebook**.
6. Click on **File** > **Upload Notebook**.
7. Upload any file with `.ipynb` extension that you want to work with from your downloaded repository and enjoy!
8. Once you are done, remember to click on **Commit**.

</details>

Note: Depending on how datasets are arranged in your directory, paths contained inside `read_csv()` might need to be changed accordingly.


## Exploratory Data Analysis
- *work in progress*

## Model Deployment
- *work in progress*

## Contributing
Please refer to [CONTRIBUTE.md](./CONTRIBUTE.md) for details. :heart_eyes:

## License
Kaggle Google Analytics Customer Revenue Prediction is released under the [MIT License](./LICENSE).
