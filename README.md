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

# Forecasting Models

Three forecasting approaches were implemented in this project.

The first approach was a baseline statistical model using a moving average method. The moving average model calculates the average demand over the previous seven days and uses this value as the forecast for the next observation. This simple model provides a benchmark for evaluating the performance of more advanced forecasting approaches.

The second approach was a machine learning model based on the Random Forest algorithm. Random Forest is an ensemble learning method that combines multiple decision trees to generate predictions. The model is capable of capturing nonlinear relationships and interactions between features, making it well suited for demand forecasting tasks involving complex feature sets.

The third approach was a deep learning model using Long Short-Term Memory networks. LSTM models are designed to capture sequential dependencies in time-series data by maintaining memory of past observations. This architecture enables the model to learn temporal patterns across longer sequences of data.

# Results and Analysis

This project demonstrates the application of machine learning and deep learning models for retail demand forecasting using the M5 dataset. The results show that machine learning models combined with effective feature engineering strategies can achieve strong predictive performance in retail forecasting tasks.

Among the evaluated models, the Random Forest approach achieved the best overall performance, highlighting the effectiveness of ensemble tree-based methods for structured forecasting problems. Although deep learning models such as LSTM networks are capable of modeling sequential dependencies, their performance may depend on larger datasets and more complex model configurations.

The findings emphasize the importance of integrating predictive analytics with supply chain decision-making processes. Improved forecasting accuracy has the potential to support more efficient inventory management strategies, reduce operational costs, and improve product availability in retail environments.

