README.txt
This README provides instructions to run the trained models. The script used to evaluate the models on the test dataset is:
NECO.ipynb

1. Required Software:
    Python: 3.13
    Operating System: Windows
    Jupyter Notebook or PyCharm with Jupyter plugin

2. Required Libraries:
    torch==2.10.0+cpu
    scikit-learn==1.8.0
    pandas==3.0.1
    numpy==2.4.2
    matplotlib==3.10.8
    joblib==1.5.3
    openpyxl==3.1.5

3. Directory and Path Setup:
    Before running the script, ensure all of the following files
    are in the same folder:
        NECO.ipynb
        mlp_best_model.pth
        svm_best_model.pkl
        default of credit card clients.xls

4. Running the Testing of Both Models:
    1. Open NECO.ipynb in PyCharm or Jupyter Notebook
    2. Ensure all files listed above are in the same directory
    3. Run all cells from top to bottom
    4. View results in the output below each cell

    The script will:
    Load and preprocess the dataset
    Load both trained models (MLP and SVM)
    Apply each model to the test set
    Output predictions, metrics and figures

5. Output Files Generated:
    mlp_loss_curve.png- MLP Training vs Validation Loss
    roc_comparison.png- ROC Curve Comparison MLP vs SVM
