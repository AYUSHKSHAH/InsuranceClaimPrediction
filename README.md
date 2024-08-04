# InsuranceClaimPrediction
## Overview
A key challenge for the insurance industry is to charge each customer an appropriate
premium for the risk they represent. The ability to predict a correct claim amount has a
significant impact on insurer's management decisions and financial statements.
Predicting the cost of claims in an insurance company is a real-life problem that needs
to be solved in a more accurate and automated way.

Several factors determine the
cost of claims based on health factors like BMI, age, smoker, health conditions and
others. Insurance companies apply numerous techniques for analyzing and predicting
health insurance costs.

## Domain
Insurance

## Project Steps
1. Data Preparation and Exploratory Data Analysis.
2. Perform Descriptive Analysis.
3. Apply appropriate transformations to extablish a linear relationship of the features with the target and do correlation study.
4. Deal with categorical and continuous features. 
5. Fit a Linear regression model and apply appropriate regularization to make the predictions.

## How to Run The Code
1. Clone/Fork the repository.
2. Ensure that you have git installed. If not, please install it from [here](https://git-scm.com/downloads) based on your machine. Similarly install git LFS from [here](https://git-lfs.com/)
3. Ensure that python3 is installed in your system. You can download and install python 3 from [here](https://www.python.org/downloads/)
4. Next, create a virtual environment and activate as follows.<br>

    - For windows command prompt
        ```
        python -m venv myenv
        myenv\Scripts\activate
        ```

    - For macOS and Linux
        ```
        python -m venv myenv
        . myenv/bin/activate
        ```
5. Install the dependencies as follows
    ```
    pip install -r requirements.txt
    ```
6. Run the jupyter notebook, `Solution.ipynb`


