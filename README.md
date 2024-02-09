Walmart Sales Prediction Documentation

By **OUBAZIZ Wassim** and **CHELGHAM Mounsif**

**1 Introduction**

This project aims to predict weekly sales for Walmart stores using machine learning algorithms. The dataset contains various features such as store type, size, department, temperature, fuel price, CPI, unemployment rate, and markdowns.

**1.1 Objectives**

- Predict weekly sales for Walmart stores.
- Identify factors influencing sales.
- Optimize model performance.

**2 Project Setup**

The project begins with importing necessary libraries and loading the datasets.

- Python code snippet for Importing libraries and Loading datasets

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.001.png)

Figure 1: Loading datasets

3  **Data Exploration**

We perform exploratory data analysis (EDA) to gain insights into the dataset.

1. **Overview of Data**
- Python code snippet of displaying headers of datasets

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.002.png)

Figure 2: Overview of Data

2. **Missing Values**
- Python code snippet for checking missing values

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.003.png)

Figure 3: Checking Missing Values

3. **Correlation Matrix**
- Python code snippet for Correlation Matrix

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.004.png)

Figure 4: Correlation Matrix Code

Execution...

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.005.png)

Figure 5: Correlation Matrix

4. **Store Type Distribution**
- Python code snippet for displaying a pie chart of store types

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.006.png)

Figure 6: Code of Store Type Distribution

Execution...

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.007.png)

Figure 7: Store Type Distribution

4  **Data Preprocessing**

We preprocess the data to prepare it for model training.

**4.1 Feature Engineering**

- Python code snippet for feature engineering

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.008.png)

Figure 8: Feature Engineering Code

5  **Exploratory Data Analysis (continued)**

We continue exploring the data to understand the relationship between features and sales.

**5.1 Weekly Sales vs. Store Size**

- Python code snippet for plotting weekly sales vs. store size

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.009.png)

Figure 9: Weekly Sales vs. Store Size Code

Execution...

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.010.png)

Figure 10: Weekly Sales vs. Store Size

6  **Model Training**

We train machine learning models to predict weekly sales.

**6.1 Random Forest Regression**

- Python code snippet for training Random Forest model

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.011.png)

Figure 11: Training Random Forest Model Code

7  **Model Evaluation**

We evaluate the performance of the trained models.

**7.1 Random Forest Regression Results**

- Python code snippet for evaluating Random Forest model

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.012.png)

Figure 12: Actual vs. Predicted Sales (Random Forest) Code

Execution...

![](Aspose.Words.8dc1b6f9-188b-4295-8fb4-4bf2c91fde1c.013.png)

Figure 13: Actual vs. Predicted Sales (Random Forest)

8  **Conclusion**

The Walmart Sales Prediction project demonstrates the application of machine learning techniques to forecast weekly sales accurately. By analyzing various features and employing advanced regression models like Random Forest, we can optimize sales predictions and assist in strategic decision-making for Walmart stores. Further model refinement and feature engineering could potentially enhance prediction accuracy and provide more valu- able insights for the retail industry.
7
