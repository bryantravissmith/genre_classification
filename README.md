# genre_classification
Udacity exerises for ML-Ops nano degree

Example run:
```
mlflow run -v 1.0.0 https://github.com/bryantravissmith/genre_classification.git -P hydra_options="main.execute_steps='download,preprocess,check_data,segregate,random_forest,evaluate'"
```