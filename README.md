# Battery-Health-Modelling-A-Data-Driven-Approach

This repository includes the research and code for my SURGE'23 Intern project under the guidance of Prof. Swathi Battula, Assistant Professor, Department of Electrical Engineering, IIT-Kanpur. The model's purpose is to accurately forecast the SoH of batteries, and the project was carried out during my internship as part of the SURGE program.

## Objective
The main objective of this project is to predict the State of Health (SoH) of batteries using Recurrent Neural Networks (RNNs). SoH prediction is crucial for battery management and maintenance to ensure optimal performance and longevity.

## Approach
- Data Extraction: Battery performance data was extracted from MATLAB files sourced from the NASA Ames Prognostics Center of Excellence (PCoE) Battery Data Repository, providing a diverse dataset for model training and evaluation.

- Feature Selection and Data Visualization: Exploratory data analysis was performed to identify the most crucial features that significantly impact the SoH prediction. Visualizations aided in understanding the data distribution and relationships.

- RNN Architecture: A parallel RNN architecture was developed, incorporating three different RNN variants: Vanilla RNN (SimpleRNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU). Input features were processed in two distinct ways to enhance model performance.

- Data Smoothing: A moving average filter was applied to the data to reduce noise and improve the model's ability to learn underlying patterns.

- Model Training: TensorFlow and Keras were utilized to train the RNN model with L1 regularization and an exponential learning rate, enhancing model stability and convergence.

## Result
The outcome of the project was a successfully developed model capable of predicting the SoH with a remarkable mean squared error (MSE) of only 0.05%. This high level of accuracy demonstrates the effectiveness of the data-driven approach in battery health prediction.

## Acknowledgments
I would like to express my gratitude to Prof. Swathi Battula for her invaluable guidance and support throughout this project.

Feel free to explore the code and research findings in this repository. If you have any questions or feedback, please don't hesitate to reach out.
