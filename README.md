Target Variables: Variables like Ave (Batting Average) and SR (Strike Rate) are continuous and real-valued, making them appropriate for regression tasks.

Feature Selection: Features such as Mat (Matches), NO (Not Outs), HS (Highest Score), and Runs are numerical and provide predictive power for modeling target variables. Irrelevant features, including '100', '50', and '0', were dropped as they are not directly related to predicting the target variable.

Handling Correlated Features: HS (Highest Score) was dropped because it is highly correlated with Runs and Ave, which could introduce multicollinearity and reduce model interpretability.

Categorical Data: Categorical features, such as player names and teams, were removed as they are non-numeric and irrelevant for predicting batting performance.
