# Human-action-detection
Overview
This project focuses on detecting human actions using sensor data. The dataset contains 1,215,745 samples with 14 features, including accelerometer and gyroscope readings from wearable devices, along with activity labels and subject identifiers.

Key Features:

Initial Data Shape: (1,215,745, 14)

Features:

3-axis accelerometer data (alx, aly, alz)

3-axis gyroscope data (glx, gly, glz)

Additional sensor readings (arx, ary, arz, grx, gry, grz)

Activity labels

Subject identifiers

Data Preprocessing:

Missing Values Check: No missing values found in any feature

Duplicate Removal: No duplicates found (shape remained unchanged)

Data Visualization: Includes plots of sensor readings across different activities

Class Balancing: Final balanced dataset shape (26,000, 14)

Usage:

The Jupyter notebook (Human action detection.ipynb) contains:

Data loading and exploration

Missing value analysis

Data visualization

Class balancing implementation

Model training and evaluation (to be implemented)

Next Steps:

Feature engineering

Model selection and training

Performance evaluation

Deployment

Requirements:

Python 3.x

Pandas

NumPy

Matplotlib/Seaborn

Scikit-learn

Jupyter Notebook

Note: The notebook shows initial data exploration and preprocessing steps. The actual modeling components would need to be implemented based on project requirements.

