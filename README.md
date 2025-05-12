
# Interpretability Techniques for Machine Learning Models
This seminar provides practical techniques to enhance the explainability of machine learning models. We will stress the importance of understanding why models make specific predictions, both during their creation and after they are put into use. The session will cover methods for determining overall feature importance (global explanations) and assessing the impact of each feature on individual predictions (local explanations). We'll explore techniques applicable to linear models, as well as perturbation-based methods, and finally Shapley Additive Explanations (SHAP) for understanding local feature contributions. You will learn how to apply these techniques using Python and popular libraries like pandas, sklearn, XGBoost, and SHAP to build more interpretable, fair, and trustworthy models.

## Prerequisites

Please run test_environment.ipynb. It checks the versions of your python and some packages (like pandas, sklearn, xgboost). If the notebook returns all OK, you should be able to run the presentation without issues. If some FAILs are returned, you need to install/update those packages first.

You can recreate the python environment using the interpretability.yml conda environment file by running these two commands in the terminal:

`conda env create -n interpretability -f interpretability.yml`

`conda activate interpretability`

You should be able to run the notebook now.

## Author

Andras Zsom (andras_zsom@brown.edu)

## License

This project is licensed under the MIT License.
