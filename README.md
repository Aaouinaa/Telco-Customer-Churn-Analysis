# Telco-Customer-Churn-Analysis
##  Customer Churn Prediction

## Projektübersicht
Diese Anwendung dient der Vorhersage von Kunden-Churn. Ziel ist es, potenziell abwandernde Kunden frühzeitig zu identifizieren und so gezielte Maßnahmen zur Kundenbindung zu ermöglichen. Mithilfe von explorativen Datenanalysen, Feature Engineering und Machine Learning Modellen werden Muster und Risikofaktoren, die zur Abwanderung führen, ermittelt.

## Funktionen
- **Datenexploration und Visualisierung:** Diagramme zur Analyse von Kundenmerkmalen und -verhalten.
- **Datenaufbereitung und Feature Engineering:** Bereinigung der Rohdaten und Transformation relevanter Merkmale für die Modellierung.
- **Modelltraining und -bewertung:** Einsatz verschiedener Machine Learning Algorithmen zur Vorhersage des Churns, inklusive Evaluierung anhand von Kennzahlen wie Genauigkeit, Präzision, Recall und F1-Score.

## Datensatz
Der Datensatz stammt aus dem Kaggle-Wettbewerb [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) :contentReference[oaicite:0]{index=0} und enthält Informationen zu Kunden eines fiktiven Telekommunikationsunternehmens. Die wichtigsten Spalten sind:

- **customerID:** Eindeutige Kennung für jeden Kunden.
- **gender:** Geschlecht des Kunden (male, female).
- **SeniorCitizen:** Gibt an, ob der Kunde ein Senior Citizen ist (1 = ja, 0 = nein).
- **Partner:** Gibt an, ob der Kunde einen Partner hat (Yes, No).
- **Dependents:** Gibt an, ob der Kunde unterhaltsberechtigte Angehörige hat (Yes, No).
- **tenure:** Anzahl der Monate, die der Kunde beim Unternehmen ist.
- **PhoneService:** Ob der Kunde einen Telefonservice nutzt (Yes, No).
- **MultipleLines:** Ob der Kunde mehrere Telefonleitungen hat (Yes, No, No phone service).
- **InternetService:** Der Internet-Service-Anbieter des Kunden (DSL, Fiber optic, No).
- **OnlineSecurity:** Gibt an, ob der Kunde einen Online-Sicherheitsservice nutzt (Yes, No, No internet service).

## Projektstruktur
- **Churn_Analysis.ipynb:** Das Haupt-Notebook, das alle Schritte von der Datenaufbereitung über die Analyse bis hin zur Modellierung umfasst.
- Data : **WA_Fn-UseC_-Telco-Customer-Churn.csv:** Primärer Datensatz mit den Kundeninformationen.
- **requirements.txt:** Liste der erforderlichen Python-Pakete.
- **README.md:** Diese Datei mit einer Projektübersicht und Anleitung.
- **Churn_Dashboard.pbix:** Power BI Dashboard.

## Verwendete Technologien
Python 3.11.3

- **Jupyter Notebook:**  Für die interaktive Entwicklung und Analyse.
- **Pandas & NumPy:**  Für Datenmanipulation und -verarbeitung.
- **Scikit-Learn:**  Für den Aufbau und die Evaluierung der Machine Learning Modelle.
- **Matplotlib & Seaborn:**  Für die Erstellung aussagekräftiger Visualisierungen.
- **TensorFlow/Keras:**  Für neuronale Netzwerke und Deep Learning Ansätze.
- **Imbalanced-Learn:**  Für das Oversampling bei unausgewogenen Datensätzen.

## Installation und Ausführung
1. Klonen Sie dieses Repository
2. Installieren Sie die erforderlichen Abhängigkeiten: `pip install -r requirements.txt`

