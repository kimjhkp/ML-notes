** RandomForest **  

. It is a decision tree algorithm with bagging (bootstrap and construct multiple trees)  

. Test a binary split for each observations and features, calculate **MSE** (weighted) for each splited groups  

. Resulting MSEs are RSS (Residual sum of squares) and the resulting splits are the ones that minimize RSS 

. In the end, it is an **ANOVA** (TSS (Total variance) = RSS (Error) + SST (treatment)) 
  and we are creating dummy coded variables for every splits we make  
  
. If the response variable is categorical, then we use **Gini** index instead
