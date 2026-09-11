# Diamond-Dynamics-Price-Prediction-and-Market-Segmentation
Problem Statement:
The diamond market heavily depends on multiple quality attributes like carat, cut, clarity, and color to decide pricing. Accurately predicting diamond prices helps in pricing strategy and customer targeting. Additionally, segmenting diamonds into meaningful market groups can assist sellers in inventory management and buyers in finding suitable products.


Objectives:
Predict diamond prices using different regression models and Artificial Neural Networks (ANN).
Cluster diamonds into market segments based on physical and qualitative features.
Develop an interactive Streamlit UI for price prediction and cluster identification based on user inputs.


Model Building:
📌 1️⃣ Regression (Price Prediction)
Split data into Train-Test sets (80-20 or 70-30).


Build 4–5 ML regression models (e.g., Linear Regression, Random Forest, XGBoost, Decision Tree, KNN).


Build an ANN regression model.


Evaluate all models using MAE, MSE, RMSE, R².


Compare model performances and save the best performing model as .pkl file

📌 2️⃣ Clustering (Market Segmentation)
Try K-Means clustering and optionally try different clustering techniques (e.g., K-Means, DBSCAN, Hierarchical Clustering).


Use the Elbow Method or Silhouette Score to find the optimal number of clusters.


Encode categorical variables (cut, color, clarity) before fitting the model.


Optionally, perform Dimensionality Reduction with PCA:


Reduce features to 2 or 3 principal components.


Use PCA for visualizing clusters in a 2D or 3D scatter plot.


Pickle the best-performing clustering model(pkl) for use in Streamlit.



📌 Cluster Naming Approach:
After clustering, analyze average price, carat, and cut distribution per cluster.
Name clusters based on characteristics like:


"Premium Heavy Diamonds"


"Affordable Small Diamonds"


"Mid-range Balanced Diamonds"
📌 Cluster Naming Ideas Based on Characteristics
Cluster Characteristic
Example Cluster Name
Description
High carat, high price
Premium Heavy Diamonds
Large, expensive, premium-grade stones
Low carat, low price
Affordable Small Diamonds
Small, budget-friendly stones
Medium carat, medium price
Mid-range Balanced Diamonds
Balanced in size and cost


Exploratory Data Analysis (EDA):
Analyses & Visualizations ideas:


Distribution plots for price, carat, x, y, z

<img width="1483" height="384" alt="download" src="https://github.com/user-attachments/assets/0e9cc411-cac4-4926-8f8f-c1cd66ea0d85" />
<img width="1183" height="384" alt="download" src="https://github.com/user-attachments/assets/f5968013-d476-4899-af91-c151872e0ff1" />


Count plots for categorical features (cut, color, clarity)

<img width="1784" height="484" alt="download" src="https://github.com/user-attachments/assets/06390b03-8c7c-4a5e-afa5-4b843ee07146" />


Price variation with carat, cut, color, clarity using boxplots

<img width="1784" height="484" alt="download" src="https://github.com/user-attachments/assets/290486e5-4f0b-4165-b2c8-11cf64a1f6a3" />

Correlation heatmap for numerical features

<img width="873" height="785" alt="download" src="https://github.com/user-attachments/assets/313f2c87-921d-4e77-985e-83af21150e71" />

Scatterplot matrix for carat, x, y, z, and price/Pairwise relationships using sns.pairplot()

<img width="1370" height="1274" alt="download" src="https://github.com/user-attachments/assets/c190ed7b-69e7-4071-8e26-0ab103a72b86" />

Carat vs. price regression lineplot

<img width="617" height="473" alt="download" src="https://github.com/user-attachments/assets/c2dff685-a200-42d7-aa87-3771ca7e41dd" />


Average price per cut, color, clarity categories using bar plots
<img width="1784" height="484" alt="download" src="https://github.com/user-attachments/assets/7bca8a6f-c031-4801-b472-04162acece42" />

📱 Streamlit App Features

<img width="902" height="384" alt="Capture1" src="https://github.com/user-attachments/assets/7bc676ad-d6e4-4544-ad32-d98620e00e88" />

<img width="916" height="397" alt="Capture2" src="https://github.com/user-attachments/assets/89f06e29-44b6-47f4-9c20-1703b7c3eae4" />

<img width="922" height="431" alt="Capture3" src="https://github.com/user-attachments/assets/c30b769b-a7f8-4be0-928f-97d3dec3c174" />

<img width="887" height="439" alt="Capture4" src="https://github.com/user-attachments/assets/fb4293fa-4376-47ed-91e2-75cdab9a919d" />
