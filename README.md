# Machine-Learning-in-Civil-Engineering

Concrete Compressive Strength Prediction using Machine Learning

## 1. Dataset Description
- Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Fly Ash (component 3) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Water (component 4) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Coarse Aggregate (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable 
- Fine Aggregate (component 7)	-- quantitative -- kg in a m3 mixture -- Input Variable 
- Age -- quantitative -- Day (1~365) -- Input Variable 
- Concrete compressive strength -- quantitative -- MPa -- Output Variable 

## 2. Exploratory Data Analysis
- Check the missing values
- Check the correlations between variables
- Data visualization: Pairplot, Scattorplot, 

## 3. Data preprocessing
- Split the data
- Standardization

## 4. Model building
- Linear Regression: Form a linear relationship between the input features and the target variable
- Lasso Regression: Adding the sum of the magnitudes of the coefficients will result in the coefficients being close to zero
- Ridge Regression: Adding the sum of squares of the coefficients to the cost function will make the coefficients be in the same range
- Decision Tree
- Random Forest: Ensembling more trees

## 5. References

- I-Cheng Yeh, “ Modeling of strength of high performance concrete using artificial neural networks,” Cement and Concrete Research, Vol. 28, №12, pp. 1797–1808 (1998).
- Ahsanul Kabir, Md Monjurul Hasan, Khasro Miah, “ Strength Prediction Model for Concrete”, ACEE Int. J. on Civil and Environmental Engineering, Vol. 2, №1, Aug 2013.
- https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength
- https://towardsdatascience.com/concrete-compressive-strength-prediction-using-machine-learning-4a531b3c43f3

