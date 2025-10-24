# RBC Data Scientist Preparation Project

## Objective
End-to-end data science workflow to simulate RBC Insurance data scientist tasks:
- Exploratory Data Analysis (EDA)
- Machine Learning Model Development
- Model Monitoring
- Dashboard Creation

## Tech Stack
Python (pandas, numpy, scikit-learn, matplotlib, seaborn), SQLAlchemy, MLflow, Power BI/Tableau, Docker.

## Folder Structure

Project layout (created empty folders include a `.gitkeep` so they are tracked):

- data/                  - data storage
	- raw/                 - unprocessed datasets (e.g. `insurance.zip`, `insurance.csv`)
	- processed/           - cleaned/features ready for modeling
- notebooks/             - Jupyter notebooks (EDA, experiments, modeling)
- models/                - trained model artifacts (.pkl, .joblib)
- monitoring/            - scripts for drift detection, metrics collection
- dashboard/             - Power BI / Tableau exports and assets
- app/                   - simple API for serving the model (Flask/FastAPI)
- docs/                  - slides, diagrams, notes, runbooks



## Next Steps
1. Perform EDA on the dataset.
2. Build baseline model (logistic regression, random forest).
3. Add model monitoring pipeline.
4. Create dashboard to visualize performance.
