# BigMart_SalesAnalysis-and-Prediction

# README #
### What is this repository for? ###

* Quick summary
This paper analyses the Big Mart Sales Prediction, in an effort to create an effective sales predictor that can be used for business decision-making purposes

* Problem Statement
The aim is to build a predictive model and find out the sales of each product at a particular store. 
* Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales



### How do I get set up? ###

# How to run
1. pip install requirements.txt: `pip install -r requirements.txt`
2. run `python sales_prediction.py` with arguments found in Command Line Arguments section below.

Example:
```
python sales_prediction.py \
    --input_Test=resources/Test.csv \
    --input_Train=resources/Train.csv \
    --output=output/Lasso Regressor.csv\
    --output=output/Linear Regression.csv\
    --output=output/Random Forest Regressor.csv
```

## Command line arguments
1. `--input_Test`: The input Oyster LinkIndex file . Must be a full path to a tsv file. For example, `--input_OysterLinkIndex=/Users/mohammedmutaharshaik/Desktop/UALR /Courses+Assignments/3 rd semester /ML/ML Main projects /resources/Test.csv`.
2. `--input_Train`: The input DWM LinkIndex file. Must be a full path to a csv file. For example, `--input_DWMLinkIndex=/Users/mohammedmutaharshaik/Desktop/UALR /Courses+Assignments/3 rd semester /ML/ML Main projects /resources/Train.csv`.
3. `--output`: The output file. Must be a full path to a csv file. For example, `--output=/Users/mohammedmutaharshaik/Desktop/UALR /Courses+Assignments/3 rd semester /ML/ML Main projects /Output`




### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
