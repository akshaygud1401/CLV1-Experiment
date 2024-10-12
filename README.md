# API Security: Anomaly Detection App

> [!WARNING]
> All the metrics, plots, and insights are made up and taken from the internet

![network header](assets/header.png)

## **BGNBD_analysis**
### Refer to the following few sections for background.

## Dataset

The dataset for this project can be found on [Kaggle](https://www.kaggle.com/c/acquire-valued-shoppers-challenge/data). I specifically used the **transactions.csv** file for my analysis.

The dataset was initially over 20GB of data and includes transaction information for several companies, but to make the experiment more narrowly focused, I chose one company at random. This lowered the size of the dataset to about 45MB. To see how I collected and narrowed my data, check out the **create_data.ipynb** notebook.

Customer Lifetime Value is frequently modeled on transaction data. The authors of this dataset have generated transactions for a large number of customers, including several product metrics (ie. product specifications, company selling the item, brand the product belongs to).

## Objectives

The main objective of this project is:

> **To analyze the performance a statistical model to predict Customer Lifetime Value**

To achieve this objective, it was further broken down into the following 4 technical sub-objectives:

1. Analyze the dataset to determine course of action for completing the analysis
2. Fit and evaluate a BG/NBD model on the data to predict frequency of transactions.
3. Fit and evaluate a Gamma-Gamma model on the data to predict monetary value of the transactions.
4. Combine the two models to make a CLV model, and compare performance to the baseline naive approacch.

## Main Insights

From the initial data exploration, I found that:

* 50% of customers made at leat 10 purchases
* Roughly 10-25k transactions are made in a given day

## Model Selection

### Beta Gamma/Negative Binomial Distributiion model

The BG/NBD model is a statistical method used to analyze customer behavior, especially in marketing and business contexts. It helps companies understand and forecast how customers are likely to make purchases over time. The model assumes that customers have a specific probability of buying at various intervals, categorizing them based on how frequently and recently they have purchased. By examining historical purchase data, businesses can identify distinct customer segments, predict future buying patterns, and tailor their marketing efforts to boost customer retention and sales.

### Gamma-Gamma Model

## Business Metrics

