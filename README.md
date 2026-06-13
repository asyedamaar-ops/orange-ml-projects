# Orange ML Projects

A collection of machine learning workflows built using [Orange 3](https://orangedatamining.com/), an open-source visual programming tool for data mining and analysis. Each project demonstrates an end-to-end ML pipeline — data loading, preprocessing, visualization, modeling, and evaluation — built using Orange's drag-and-drop widget canvas.

## Projects

| Project | Type | Description |
|---|---|---|
| [ALS Classification](./ALS_Classification) | Supervised Classification | Detecting Amyotrophic Lateral Sclerosis (ALS) from acoustic voice features using five ML models, with results compiled into an IEEE-format research paper |
| [Titanic Survival Prediction](./Titanic_Survival_Prediction) | Supervised Classification | Predicting passenger survival on the Titanic using Logistic Regression with ROC analysis |
| [Iris Clustering Analysis](./Iris_Clustering_Analysis) | Unsupervised Learning | Hierarchical clustering and distance-based grouping on a numeric dataset, with visual exploration via scatter, box, and distribution plots |

## What's in Each Project

Each folder contains:
- An `.ows` file — the Orange workflow, openable directly in Orange 3
- A `README.md` — explaining the dataset, workflow steps, widgets used, and results
- Supporting files (papers, screenshots) where applicable

## Tools Used

- **Orange 3** — visual ML workflow tool ([orangedatamining.com](https://orangedatamining.com/))
- Widgets: File, Data Table, Preprocess, Select Columns, Rank, Scatter Plot, Box Plot, Violin Plot, Bar Plot, Distributions, Logistic Regression, SVM, Random Forest, Gradient Boosting, Neural Network, Test and Score, Predictions, Confusion Matrix, ROC Analysis, Distances, Hierarchical Clustering

## How to Run These Workflows

1. Install Orange 3:
   ```
   pip install orange3
   ```
   or download the desktop app from [orangedatamining.com/download](https://orangedatamining.com/download/)

2. Open Orange, then go to **File → Open** and select the `.ows` file from the relevant project folder.

3. The full workflow canvas will load — double-click any widget to view its output (tables, charts, model results).

## About Me

B.Tech CSE (AI & ML) student at SRM Institute of Science and Technology, Chennai. Interested in machine learning, predictive modeling, and data engineering. Check out my other work on my [GitHub profile](https://github.com/asyedamaar-ops).
