# 🚇 Metro Line Optimization Using Machine Learning

### Identifying Potential Metro Stations and Building an Optimized Metro Network

## 1. Project Overview

This project uses machine learning to identify potential metro station locations and create an optimized metro network with maximum geographical coverage.

The main objective is to classify whether a given location is suitable for a metro station based on factors such as population density, nearby facilities, traffic, rental prices, and existing railway connectivity.

After identifying potential metro stations, the project connects suitable locations to build a metro network with maximum coverage while maintaining non-intersecting connections between neighbouring stations.

The project demonstrates how machine learning and data analysis can help solve real-world urban transportation planning problems.

## 2. Problem Statement

Choosing the right locations for metro stations is important for improving public transportation and connecting different parts of a city.

However, selecting suitable locations requires considering several factors, such as population density, nearby facilities, traffic conditions, and existing transportation networks.

This project aims to:

- Identify locations that are suitable for metro stations.
- Classify locations as potential metro stations or non-metro stations.
- Connect potential metro stations to create an optimized metro network.
- Improve geographical coverage while avoiding intersecting connections between neighbouring stations.

## 3. Dataset & Features

We created our own dataset using information collected from various government websites and other online sources.

The dataset contains 11 parameters that help determine whether a location is suitable for a metro station.

| Feature | Description |
|---|---|
| Population Density | Number of people living in a particular area. |
| Hospitals | Number of hospitals and nearby healthcare facilities. |
| Entertainment | Availability of entertainment and recreational places. |
| Monuments | Nearby historical and tourist locations. |
| Schools | Number of educational institutions in the area. |
| Rent | Rental prices in the area. |
| Latitude | Geographical latitude of the location. |
| Longitude | Geographical longitude of the location. |
| Railway | Availability of existing railway connectivity. |
| Traffic | Traffic conditions in the area. |
| City | Name of the city. |

These parameters help evaluate locations based on population, accessibility, infrastructure, and transportation needs.

## 4. Methodology

The project follows two main stages:

### Stage 1: Metro Station Classification

We used machine learning algorithms to classify locations into two categories:

- **Metro Station:** Locations identified as suitable for metro stations.
- **Non-Metro Station:** Locations identified as unsuitable for metro stations.

Two machine learning models were trained and evaluated:

1. Random Forest
2. XGBoost

Both models were compared to identify the better-performing model.

### Stage 2: Metro Network Optimization

After identifying potential metro station locations, we connected the prospective stations to create an optimized metro network.

The objective was to:

- Connect potential metro stations.
- Achieve maximum geographical coverage.
- Maintain non-intersecting connections between neighbouring stations.
- Create a more organized metro connectivity network.

This stage helps convert the classification results into a practical metro network layout.

## 5. Model Performance & Comparison

We evaluated both models using Accuracy and F1-score.

| Evaluation Metric | Random Forest | XGBoost |
|---|---:|---:|
| Accuracy | 81% | 86% |
| F1-Score | 87% | 91% |

### Key Findings

- Random Forest achieved 81% accuracy and an 87% F1-score.
- XGBoost achieved 86% accuracy and a 91% F1-score.
- XGBoost performed better than Random Forest on both evaluation metrics.

Based on these results, XGBoost was the better-performing model for identifying potential metro station locations.

## 6. Visual Results

The following visualization shows the classification results and the generated metro network.

![Metro Station Classification and Optimized Network](https://github.com/Tamogh123/Metro-Line-optimization/assets/91934369/da9021c3-e05e-4605-8fbc-37bc2334c16e)

**Legend:**
- Red crosses represent metro station locations.
- Black crosses represent non-metro station locations.
- Red lines represent the connected metro network.

The visualization shows how the predicted metro locations are connected to form a metro network.

## 7. Business Insights & Recommendations

The project provides a data-driven approach to identifying suitable locations for metro station development.

### Key Insights

1. **Population Density:** Areas with higher population density may have greater demand for public transportation.
2. **Accessibility:** Locations near hospitals, schools, entertainment centres, and monuments may improve access to important destinations.
3. **Transportation Connectivity:** Existing railway connectivity can help in planning better-connected transportation networks.
4. **Traffic Conditions:** Areas with heavy traffic may benefit from improved public transportation facilities.
5. **Network Coverage:** Connecting suitable station locations helps create a more organized transportation network with wider geographical coverage.

### Recommendations

Based on the project's objectives, the following factors should also be considered before finalizing metro station locations:

- Passenger demand and population growth.
- Construction and maintenance costs.
- Land availability and infrastructure requirements.
- Connectivity with existing public transportation.
- Environmental and urban development considerations.

**Business Value:** This project demonstrates how data analysis and machine learning can support infrastructure planning, identify potential metro station locations, and improve transportation network planning.

## 8. Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Random Forest, XGBoost |
| Data Analysis | Pandas, NumPy |
| Model Evaluation | Accuracy, F1-Score |

*Add any other libraries or tools used in the actual implementation.*

## 9. Key Skills Demonstrated

- Data Collection and Dataset Creation
- Data Preprocessing and Analysis
- Machine Learning and Classification
- Random Forest and XGBoost
- Model Evaluation and Comparison
- Geographical Analysis
- Network Optimization
- Problem-Solving and Data-Driven Decision-Making

## 10. Project Outcome

The project successfully combines machine learning-based classification with metro network optimization.

By analysing 11 different parameters, we developed models to identify potential metro station locations. XGBoost achieved 86% accuracy and a 91% F1-score, outperforming Random Forest.

The identified locations were then connected to create a metro network focused on maximizing geographical coverage while maintaining non-intersecting connections between neighbouring stations.

The project demonstrates how machine learning can be applied to real-world transportation planning challenges.

**Note:** The identified locations are model-based predictions and should be further evaluated through detailed feasibility studies before actual implementation.





















# Metro-Line-optimization
This project has been made for classifying whether a station can be claassified as a metro station or not and connect all possible prospective stations to make the best coverage metro network with non-intercepting neighbours.
# Dataset used
We have created our own dataset using several goverment websites and other sites.The different parameters considered are:<br>
1.popden<br>	2.hospitals<br>	3.entertainment<br>	4.monuments<br>	5.schools<br>	6.rent<br>	7.lat<br>	8.long<br>	9.railway<br>	10.traffic<br> 	11.city<br>
# Models used
we have utilized Random forest and XGboost to train the dataset.
# Results
Accuracy in Random forest-81%<br>
Accuracy in XGboost-86%<br>
F1 score in Random forest-87%<br>
F1 score in XGboost-91%<br>
![Screenshot 2024-01-01 153003](https://github.com/Tamogh123/Metro-Line-optimization/assets/91934369/da9021c3-e05e-4605-8fbc-37bc2334c16e)
<br>
*Here the red crosses show metro points while those in black show non-metro points and the red path shows the metro path.


