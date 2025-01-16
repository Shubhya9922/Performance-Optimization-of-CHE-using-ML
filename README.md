# Performance-Optimization-of-CHE-using-ML
Overview :
This project aims to analyze and model the performance of a Compact Heat Exchanger (CHE) using C++ for calculations and a web interface for user interaction. It explores various factors like fluid properties, fin types, surface configurations, and pressure drops to calculate the heat transfer coefficient, effectiveness, and feasibility of pressure drop. Additionally, an Artificial Neural Network (ANN) model is developed to predict effectiveness based on key parameters.

Methodology :
Studied heat exchanger principles, working, and performance.
Developed a C++ model to calculate heat transfer and pressure drop.
Created a web interface for easy user interaction.
Explored different fin types and surface configurations.
Collected and processed data to train an ANN model.
Selected and trained a suitable machine learning model to predict CHE effectiveness.

Results :
Developed a versatile CHE calculator/model with various fluid types, fin configurations, and materials.
Analyzed key parameters affecting CHE effectiveness and pressure drop.
Calculated heat transfer effectiveness and overall heat transfer coefficient.
Verifying the feasibility of pressure drop across different conditions.
ANN Model
The ANN model consists of a 5-layer linear regression model using "ReLU" as the activation function.
Achieved a mean absolute error (MAE) of 0.001132750.

Conclusions :
Effectiveness increases with mass flow rate of hot fluid, surface type, and depth, while it decreases with a lower mass flow rate of cold fluid.
Pressure drop for cold fluid increases with depth and surface type, while it increases for hot fluid with width and surface type.

Challenges :
Data unavailability.
Lack of detailed information on fouling factors.
Limited research on Kay and London models.

Installation: 

Clone the repository:

git clone https://github.com/Shubhya9922/Performance-Optimization-of-CHE-using-ML.git

Compile the C++ code:

g++ -o LBP.cpp

Run the jupyter notebook :

jupyter nbconvert --execute --to markdown LBP.ipynb
Open the web interface and interact with the model.
