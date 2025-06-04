 🔭 Exoplanet Classification and Anomaly Detection using PySpark

This project leverages Big Data techniques with PySpark, Machine Learning to classify exoplanets discovered by the Kepler Space Telescope.

Introduction

The Kepler Space Telescope has provided an enormous amount of stellar observation data. This project utilizes machine learning to classify whether an observed candidate is 
a confirmed exoplanet or a false positive, and uses anomaly detection to explore potential unknown planetary behaviors.

 Tech Stack

- Language: Python
- Big Data Framework: Apache Spark (PySpark)
- ML Libraries: PySpark MLlib, scikit-learn
- Visualization: Matplotlib, Seaborn

 System Design

1. Data Ingestion: Kepler CSV parsed and cleaned using Pandas and Spark.
2. Feature Engineering: Selected key planetary and stellar features.
3. Classification Model: Random Forest Classifier via PySpark.
4. Anomaly Detection: Isolation Forest.
5. Evaluation: Accuracy, F1 score, visualizations.



