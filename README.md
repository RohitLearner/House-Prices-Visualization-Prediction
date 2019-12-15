# House Prices: Visualization & Prediction
Predict sales prices and practice different machine learning regressors.
( ⭐️ Star us on GitHub — it helps! )

<img src="https://www.vancouverrealestatepodcast.com/wp-content/uploads/2018/10/Detached-home-prices.jpg"
     title="House Prices">

Getting started with competitive data science can be quite intimidating. So I build this notebook for a quick overview of the `House Prices: Advanced Regression Techniques` competition. For your convenience, please view it in [kaggle](https://www.kaggle.com/iamrohitsingh/house-prices-visualization-prediction/output).

I encourage you to fork this kernel/GitHub repo, play with the code and enter the competition. Good luck!

## Requirements

This project requires  **Python 2.7**  and the following Python libraries installed:

-   [NumPy](http://www.numpy.org/)
-   [matplotlib](http://matplotlib.org/)
-   [seaborn](https://stanford.edu/~mwaskom/software/seaborn/#)
-   [scikit-learn](http://scikit-learn.org/stable/)
-   [XGBoost](https://xgboost.readthedocs.io/en/latest/)

You will also need to have the software installed to run and execute an  [iPython Notebook](http://ipython.org/notebook.html)

## Code

```bash 
python3 grid_search.py
python3 train.py
python3 predict.py
```

An ipython notebook is used for data preprocessing, feature transforming and outlier detecting. All core scripts are in `file .ipynb"` folder. All input data are in `input` folder and the detailed description of the data can be found in [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Content in Notebook
1.  Exploratory Visualization
2.  Data Cleaning & Preprocessing
3.  Feature Engineering  
    3.1 Value Mapping  
    3.2 Simplification 
    3.3 Feature Selection  
    3.4 Handling Categorical Data
4.  Modeling & Evaluation
	4.1 Cross-validation method 
	4.2 Model scoring function
	4.3 Setting Up Models
5. Train & Fit Model
6.  Ensemble Methods  
    6.1 Weight Average  of Model
    6.2 Blend with Top Kernals submissions
7. Output
	7.1 Prediction file ( .csv)
	7.2 Model Comparison
8. Acknowledgments

## FlowChart

<img src="https://raw.githubusercontent.com/RohitLearner/House-Prices-Visualization-Prediction/master/fig/flowchart.png"
     title="FlowChart">


## Prediction & Submission

<img src="https://raw.githubusercontent.com/RohitLearner/House-Prices-Visualization-Prediction/master/output/model%20comparison.png"
     title="Model Comparison">	 

The final price prediction for each house is present in the `output` folder as a .csv file. The final model used for scoring is blended one as a weighted average of all different types of models. 

## Contributors
Rohit Kumar Singh (IIT Bombay)

## Feedback
Feel free to send us feedback on [file an issue](https://github.com/RohitLearner/House-Prices-Visualization-Prediction/issues). Feature requests are always welcome. If you wish to contribute, please take a quick look at the [kaggle](https://www.kaggle.com/iamrohitsingh/house-prices-visualization-prediction/output).

## Acknowledgments

Inspirations are drawn from various Kaggle notebooks but majorly motivation is from the following :

1.  [https://www.kaggle.com/poonaml/house-prices-data-exploration-and-visualisation](https://www.kaggle.com/poonaml/house-prices-data-exploration-and-visualisation)
    
2.  [https://www.kaggle.com/lavanyashukla01/how-i-made-top-0-3-on-a-kaggle-competition](https://www.kaggle.com/lavanyashukla01/how-i-made-top-0-3-on-a-kaggle-competition)
    
3.  [https://www.kaggle.com/itslek/blend-stack-lr-gb-0-10649-house-prices-v57/data?scriptVersionId=11189608](https://www.kaggle.com/itslek/blend-stack-lr-gb-0-10649-house-prices-v57/data?scriptVersionId=11189608)
    
4.  [https://www.kaggle.com/hemingwei/top-2-from-laurenstc-on-house-price-prediction/notebook](https://www.kaggle.com/hemingwei/top-2-from-laurenstc-on-house-price-prediction/notebook)
    
5.  [https://www.kaggle.com/jesucristo/1-house-prices-solution-top-1](https://www.kaggle.com/jesucristo/1-house-prices-solution-top-1)
    

###### Credit for image to  [https://www.vancouverrealestatepodcast.com/tag/housing-price-prediction-2019/](https://www.vancouverrealestatepodcast.com/tag/housing-price-prediction-2019/)
> Written with [StackEdit](https://stackedit.io/).
