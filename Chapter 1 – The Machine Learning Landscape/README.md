# Chapter 01: The Machine Learning Landscape

This chapter is a hands-on introduction to the basic ideas behind machine learning. The notebook follows a small, practical workflow: load a simple dataset, explore the relationship between GDP per capita and life satisfaction, train two regression models, and compare their predictions.

## What This Chapter Covers

- What machine learning is and why it is useful
- Common application areas for machine learning
- The main types of machine learning systems
- Core challenges such as poor data quality, overfitting, and underfitting
- How to evaluate models and tune hyperparameters

## Notebook Walkthrough

The notebook in this folder practices the most common code blocks from the chapter:

- Importing the libraries needed for data analysis and modeling
- Loading the life satisfaction dataset from a CSV file
- Selecting the input feature and target variable
- Visualizing the relationship between GDP per capita and life satisfaction
- Training a linear regression model
- Training a K-nearest neighbors regressor
- Making predictions with both models
- Plotting the fitted regression line

## Files

- [Chapter_1_–_The_Machine_Learning_Landscape.ipynb](Chapter_1_–_The_Machine_Learning_Landscape.ipynb): main practice notebook for the chapter

## Notebook Details

This chapter is organized around the notebook in this folder, which walks through a compact regression example using the life satisfaction dataset. It shows the full workflow from importing packages and loading data to training two different regression models and comparing their predictions.

The notebook includes:

- Data loading from the remote CSV source
- Feature and target selection
- A scatter plot of GDP per capita versus life satisfaction
- A linear regression model as the model-based approach
- A K-nearest neighbors regressor as the instance-based approach
- Predictions for Puerto Rico using both models

## Model Results

The current notebook output shows these results:

- Linear regression slope: `6.778899694341222e-05`
- Linear regression intercept: `3.7490494273769093`
- Puerto Rico prediction with linear regression: `6.016103294356055`
- Puerto Rico prediction with KNN: `5.733333333333333`

The two models produce similar but not identical estimates, which is useful for comparing model-based and instance-based approaches on the same data.

## How To Use

1. Open the notebook in VS Code or Jupyter.
2. Run the cells from top to bottom.
3. Review the comments and outputs to understand each step of the workflow.
4. Modify the code blocks if you want to experiment with different inputs or models.

## Notes

- The chapter uses a small real-world dataset about GDP per capita and life satisfaction.
- Some cells produce plots or model outputs, so running the notebook in order is recommended.
- The README is limited to this chapter so the practice flow stays focused and easy to follow.
