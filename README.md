# Breast Cancer Data Exploration
## by Klaus BONOU SELEGBE


## Dataset
The data consists of information about 4024 breast cancer patients. It presents each patient's age, marital status, different stages of cancer advancement, tumor size, number of months he survived before recovering or dying, vital status and many more. The dataset can be found [here](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer)

## Summary of Findings

Exploration showed that in this data set, 85% of patients are alive while approximately 15% are dead.
The distribution of some interesting variables such as tumor size, stage variables, grade were studied.
We learn from this exploration that
    - Alive patients are about 32 to 69 years old, their tumor size is among the smallest and they survive for a long time at least about more than 50 or 60 months
    - Dead patients are of all ages, their tumor size is also among the smallest, but not as alive patients...looking at the distribution, we could easily add that a large portion of dead patients have relatively large tumor with a size around 50 and 70 mm. They don't necessarily survive long before they die.
    - Proportionally, patients with an advanced stage for the 6th_stage (IIIC, IIIB, IIIA) and for n_stage(N3) are less likely to survive than if their cancer was at a lower stage (N1 or N2) or (IIA or IIB).
    - Proportionally patients with poorly differentiated or undifferentiated cells or whose carcinogenic cells are at an advanced grade (grade 3 and 4) are more likely to die than if their cells were well differentiated or if the carcinogenic cells were at a low grade (1 or 2)
    - Regarding marital status, separated, widowed, single and divorced patients respectively have less chance of surviving than married ones.
    - Finally The tumor_size increases as the stage or grade is high.

## Key Insights for Presentation

For the presentation, I focus only on the influence of variables such as tumor size, stage variables(`n_stage`, `6th_stage`), `survival_months`,the grade of cancer cells (`grade`) on the status of the patient. I start by presenting the status variable, followed by the distribution model of the variables involved.

Next, I introduce each of the most important relationships between variables using  violinplots and clustered bar plots for categorical variables. Then come the graphs describing more clearly the influence of the variables raised on the status of the patient. Scatter plots will be preferred in this case