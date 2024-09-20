# Maritime-Shipping-Estimated-Time-of-Arrival-ETA-Prediction-and-Route-Optimization

## Languages:
* **Python**

## Important Libraries:
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Tensorflow/Keras**
* **Gurobi**
* **NetworkX**
* **Matplotlib**
* **Seaborn**
* **Plotly**

## Technologies:
* **Algorithm (Dijkstra)**
* **Optimization (Binary Linear Programming in Gurobi)**
* **Reinforcement Learning (Q-Learning)**
* **Data Analysis**
* **Machine Learning**

### Abstract:
This project focuses on predicting the Estimated Time of Arrival (ETA) for shipping routes and optimizing those routes using various techniques. By leveraging AIS data from Spire, we aim to enhance operational efficiency and reliability in maritime logistics.

### Dataset:
Spire, Proxy

### Methodology:
Data preprocessing involved cleaning and preparing the datasets for analysis, ensuring accuracy and completeness. Exploratory data analysis was conducted to analyze data patterns and relationships, informing model development. For ETA prediction, we implemented predictive models using Scikit-learn. The Decision Tree Regressor emerged as the best-performing model, achieving an R² score of 0.97, a mean absolute error (MAE) of 6086.35, and a mean squared error (MSE) of 11988887233.40.

For route optimization, we employed Dijkstra's Algorithm to identify the shortest path, effectively managing the maritime routes. Additionally, we integrated Binary Linear Programming in Gurobi to address resource allocation constraints, enhancing the efficiency of the routing process. To adaptively improve routing decisions based on dynamic maritime conditions, we utilized reinforcement learning through Q-Learning. This approach continuously refines route choices by learning from feedback gathered during previous voyages, ultimately leading to improved operational strategies.

### Results and Conclusion:
The implemented models demonstrated significant improvements in ETA accuracy and route efficiency. The findings indicate that combining traditional optimization methods with reinforcement learning can lead to better operational strategies in maritime logistics.

### Disclaimer:
The dataset used for this project consists of AIS data from Spire, while proxy data was employed for route optimization purposes. The assumptions made in this analysis are based on available data. The findings from this project may not accurately reflect real-world scenarios. Further validation and refinement are necessary to ensure reliability and effectiveness in practical applications.
