# ForecastingUsingMultiVariateData
Performing forecasting on multivariate data

### Dataset
The dataset is a record of 7 common different fish species in fish market sales. With this dataset, a predictive model can be performed using machine friendly data and the species of fish can be predicted.

Below is a sample of the first 5 rows of data.

|   | Species | Weight | Length1 | Length2 | Length3 |  Height |  Width |
|:-:|:-------:|:------:|:-------:|:-------:|:-------:|:-------:|:------:|
| 0 |  Bream  |  242.0 |   23.2  |   25.4  |   30.0  | 11.5200 | 4.0200 |
| 1 |  Bream  |  290.0 |   24.0  |   26.3  |   31.2  | 12.4800 | 4.3056 |
| 2 |  Bream  |  340.0 |   23.9  |   26.5  |   31.1  | 12.3778 | 4.6961 |
| 3 |  Bream  |  363.0 |   26.3  |   29.0  |   33.5  | 12.7300 | 4.4555 |
| 4 |  Bream  |  430.0 |   26.5  |   29.0  |   34.0  | 12.4440 | 5.1340 |

The dataset contains mere 159 records so the predictions might not be accurate but it is sufficient to demonstrate the process of prediction.

### Task
Based on the available multivariate data, train a model to predict the species of a fish, provided other input paramaters. 

> Note - You can also train a model to predict the weight of the fish on the basis of rest of the details.

### Approach
Multiple possible models are tested for accuracy and the one with the optimal accuracy is used to make prediction.
