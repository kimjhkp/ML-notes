** RandomForest **  

. It is a decision tree algorithm with bagging (bootstrap and construct multiple trees)  

. It tests a binary split for each observation and feature, then calculates **MSE** (weighted) for the splited groups splitted  
. Resulting MSEs are RSS (Residual sum of squares) and the resulting splits are the ones that minimize RSS 

. In the end, it is an **ANOVA** (TSS (Total variance) = RSS (Error) + SST (treatment)) 
  and we are creating dummy coded variables for every splits we make (For regression problems)
  
. If the response variable is categorical, then we can use **Gini** index instead or **Information gain**

2020/05/02

. How does the averaging work? For regression problems, we get individual outputs from each tree given the training input,       then we average the outputs (then calculate the prediction accuracy + R^2). For classification problems, we get the major       votes from the individual trees. 
