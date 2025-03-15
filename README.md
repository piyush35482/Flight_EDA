# EDA and Feature Engineering: Flight Price Prediction  

## Dataset  
This project analyzes flight price data for predictive modeling. The dataset can be found here:  
[Flight Price Prediction Dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)  

## Features  
The dataset contains the following key features:  

1. **Airline** – Name of the airline (categorical, 6 unique values).  
2. **Flight** – Flight code (categorical).  
3. **Source City** – City from where the flight departs (categorical, 6 unique values).  
4. **Departure Time** – Categorized departure time bins (categorical, 6 unique labels).  
5. **Stops** – Number of stops (categorical, 3 unique values).  
6. **Arrival Time** – Categorized arrival time bins (categorical, 6 unique labels).  
7. **Destination City** – Destination of the flight (categorical, 6 unique values).  
8. **Class** – Seat class (categorical: Business or Economy).  
9. **Duration** – Total travel time in hours (continuous).  
10. **Days Left** – Derived feature representing the number of days until departure.  
11. **Price** – Target variable representing ticket price.  

## Setup and Usage  

### Requirements  
To run this project, install the following dependencies:  

```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Notebook  
To explore the data and perform feature engineering, open the Jupyter Notebook:  

```bash
jupyter notebook 2.0-EDA+And+FE+Flight+Price.ipynb
```

### Example Code  
Here's a snippet of the initial data analysis:  

```python
# Importing basic libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

%matplotlib inline

df = pd.read_csv('flight_price.csv')
df.head()
```

---

Let me know if you need any more edits! 🚀
