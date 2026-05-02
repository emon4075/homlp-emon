# Chapter 02: End-to-End Machine Learning Project

This chapter is a hands-on walkthrough of a complete machine learning workflow using the California housing dataset. The notebook follows a practical end-to-end pipeline: load the data, explore the features, engineer new variables, build preprocessing pipelines, train regression models, compare their performance, tune the best model, and save it for later use.

## What This Chapter Covers

- Loading the housing dataset from a remote CSV source
- Exploring the dataset with summaries, distributions, and correlation plots
- Creating engineered features such as rooms per house and people per house
- Preparing numeric and categorical preprocessing pipelines
- Splitting the data into training and test sets
- Training and comparing regression models
- Evaluating model performance with cross-validation and test-set metrics
- Tuning the best model with `GridSearchCV`
- Saving the final model as `housing_model.pkl`

## Notebook Walkthrough

The notebook in this folder practices the most common code blocks from the chapter:

- Importing the libraries needed for data analysis, preprocessing, and modeling
- Loading the California housing dataset into a pandas DataFrame
- Inspecting the dataset with `head()`, `info()`, `value_counts()`, and `describe()`
- Visualizing feature distributions, geographic patterns, and feature correlations
- Adding engineered features to enrich the model input
- Building separate preprocessing pipelines for numeric and categorical attributes
- Defining the training and test splits
- Training Linear Regression, Decision Tree, and Random Forest models
- Running cross-validation to compare model performance
- Measuring MSE, RMSE, and R-squared on the test set
- Searching for the best random forest hyperparameters
- Saving the final tuned model with `joblib`

## Files

- [Chapter_2_–_End_to_End_Machine_Learning_Project.ipynb](Chapter_2_–_End_to_End_Machine_Learning_Project.ipynb): main practice notebook for the chapter

## Notebook Details

This chapter is organized around the notebook in this folder, which walks through a full regression workflow on the California housing dataset. It shows the complete process from loading and inspecting the data to training multiple models, comparing their predictions, and selecting the best model with hyperparameter tuning.

The notebook includes:

- Data loading from the remote housing CSV source
- Exploratory data analysis with plots and correlation checks
- Feature engineering with ratio-based attributes
- Preprocessing for numeric and categorical columns
- A linear regression baseline
- A decision tree regressor
- A random forest regressor with cross-validation
- Grid search for model tuning
- Model export with `joblib.dump()`

## Model Results

The notebook is structured to compare model performance using these metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R2)

The random forest model is further tuned with `GridSearchCV` so the final saved estimator can be reused later as `housing_model.pkl`.

## How To Use

1. Open the notebook in VS Code or Jupyter.
2. Run the cells from top to bottom.
3. Review the comments and outputs to understand each step of the workflow.
4. Modify the code blocks if you want to experiment with different preprocessing choices or model settings.

## Notes

- The chapter uses the California housing dataset from the Geron data repository.
- Some cells produce plots or model metrics, so running the notebook in order is recommended.
- The README is limited to this chapter so the practice flow stays focused and easy to follow.
