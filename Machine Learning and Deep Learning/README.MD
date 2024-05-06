**Course Name: Machine Learning and Deep Learning**
* **Project Title**: Predicting Used Car Prices and Analysing Value Drivers for Auto1 - A Comparative Study of Advanced Machine Learning Techniques
* **Deliverable**: Python code for machine learning pipeline used for price prediction on used cars
* **Tools**: Python (Pandas, SciKit-Learn, XGBoost, Pycaret)

**Exam deliverable**: To write a report comparing different machine learning or deep learning models on an interesting dataset.

**Outcome**:
* We acquired a **dataset** from Auto1 (a German platform for selling used cars)
* We wanted to **predict the value of a car** that is put on the platform, based on all the information which the staff gathers about the cars
* Based on our models, we wanted to **get key insigts** in what **factors** were the most relevant when **valuing a used car**
* We built and **compared 9 different regression models**
* We found that our **XGBoost model achieved the highest model scores**, followed by a MLP (neural network) model
* We found that the models perceived logical measures such as **built year**, car model, automatic gear shifts, degree of damages and total milage to be the **biggest deciding factors** for valuing the cars

**Methodology overview**:
![Process graph](imgs/ml_process_graph.png)

**Model results** (*car prices were modelled in Euros*):
![Prediction results tabel](imgs/ml_results_table.png)

**Model feature importance**:
![Factors deciding the price of a used car](imgs/ml_feature_importance.png)
