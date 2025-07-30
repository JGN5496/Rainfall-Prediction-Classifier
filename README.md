# Rainfall-Prediction-Classifier

DE:

**Entwicklung eines Klassifikators zur Regenfallvorhersage**

In diesem Projekt wurde ein Machine-Learning-Modell entwickelt, um die Regenwahrscheinlichkeit für den nächsten Tag anhand historischer Wetterdaten vorherzusagen.
**Ergebnis:** Ein voll funktionsfähiger und optimierter Klassifikator, der die Komplexität realer Wetterdaten handhaben und präzise Vorhersagen treffen kann.

Angewandte Fähigkeiten:
 * Datenaufbereitung und Feature Engineering:
    - Analyse und Aufbereitung eines realen, umfangreichen Wetterdatensatzes des australischen Wetteramtes (Zeitraum 2008-2017)
    - Umgang mit fehlenden Werten durch Entfernen unvollständiger Zeilen, um eine saubere Datenbasis von über 56.000 Einträgen zu schaffen
    - Fokussierung des Modells auf eine spezifische geografische Region (Melbourne und Umgebung), um die Vorhersagegenauigkeit zu verbessern
* Modellentwicklung und Optimierung:
  - Aufbau einer robusten Scikit-learn Pipeline, die Datenvorverarbeitung (Standard-Skalierung für numerische und One-Hot-Encoding für kategoriale Daten) und Modelltraining automatisiert
  - Training eines Random Forest Classifiers und systematische Optimierung der Hyperparameter mittels Grid Search Cross-Validation, um die bestmögliche Leistung zu finden
* Evaluation und Interpretation:
  - Umfassende Bewertung des finalen Modells mit einem Klassifikationsbericht und einer Konfusionsmatrix, wobei eine Vorhersagegenauigkeit von 84 % auf ungesehenen Testdaten erreicht wurde
  - Analyse der Merkmalswichtigkeit (Feature Importance), um die treibenden Faktoren der Vorhersage zu identifizieren, wobei sich die Luftfeuchtigkeit um 15 Uhr (Humidity3pm) als wichtigstes Merkmal herausstellte.
  - Vergleich des Random-Forest-Modells mit einem Logistischen Regressionsmodell, um die Überlegenheit des gewählten Ansatzes zu bestätigen

EN:

**Development of a classifier for predicting rainfall**

In this project, a machine learning model was developed to predict the rainfall probability for the next day based on historical weather data.
**Result:** A fully functional and optimized classifier that can handle the complexity of real weather data and make accurate predictions.

Applied skills:
 * Data preparation and feature engineering:
    - Analyzing and preparing a real-world, large-scale weather dataset from the Australian Bureau of Meteorology (period 2008-2017).
    - Dealing with missing values by removing incomplete rows to create a clean database of over 56,000 entries
    - Focusing the model on a specific geographic region (Melbourne and surrounding areas) to improve forecast accuracy
* Model development and optimization:
  - Build a robust scikit-learn pipeline that automates data pre-processing (standard scaling for numeric and one-hot encoding for categorical data) and model training
  - Training of a random forest classifier and systematic optimization of hyperparameters using grid search cross-validation to find the best possible performance
* Evaluation and interpretation:
  - Comprehensive evaluation of the final model with a classification report and confusion matrix, achieving a prediction accuracy of 84% on unseen test data
  - Feature Importance analysis to identify the driving factors of the prediction, with Humidity at 3pm (Humidity3pm) emerging as the most important feature
  - Comparison of the random forest model with a logistic regression model to confirm the superiority of the chosen approach
