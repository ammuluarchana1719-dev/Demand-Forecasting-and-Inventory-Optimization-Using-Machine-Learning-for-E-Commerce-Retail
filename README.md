# Demand-Forecasting-and-Inventory-Optimization-Using-Machine-Learning-for-E-Commerce-Retail

# Overview

Accurate demand forecasting plays a critical role in modern supply chain management and inventory optimization. Forecast errors can lead to operational inefficiencies such as excess inventory, increased holding costs, or product stockouts. This project investigates how machine learning and deep learning forecasting methods can improve decision-making within retail inventory systems.

The study uses the M5 Forecasting Accuracy dataset, which contains large-scale retail sales data from Walmart stores in the United States. The project implements and compares multiple forecasting models, including a traditional statistical baseline, a machine learning approach using Random Forest, and a deep learning model using Long Short-Term Memory (LSTM) networks.

The objective is not only to evaluate predictive accuracy but also to examine how forecasting improvements translate into better inventory decisions, including reduced stockouts and optimized inventory levels.

# Dataset

The dataset used in this project is sourced from the M5 Forecasting Accuracy Competition, hosted on the Kaggle platform. It contains large-scale retail sales data provided by Walmart, designed to support research in time-series forecasting and hierarchical demand prediction.

The dataset includes historical daily sales records for thousands of products across multiple stores and states in the United States. It is structured to reflect real-world retail operations, with detailed information on product hierarchy, store locations, calendar events, and pricing.

The main components of the dataset are:

1.Sales Data (sales_train_validation.csv)
Contains daily unit sales for each product-store combination over an extended time horizon. Each row represents a unique product, while columns represent daily demand observations.

2.Calendar Data (calendar.csv)
Provides temporal information such as dates, weekdays, months, and special events. This dataset enables the incorporation of seasonal and event-driven demand patterns.

3.Price Data (sell_prices.csv)
Includes weekly product pricing information across different stores, allowing analysis of price-related demand behavior.

This dataset is widely used in both academic research and industry applications due to its large scale, hierarchical structure, and realistic demand patterns, including seasonality, intermittency, and volatility. These characteristics make it highly suitable for evaluating forecasting models and their impact on supply chain decision-making.

Dataset link:
[https://www.kaggle.com/competitions/m5-forecasting-accuracy/data](url)
