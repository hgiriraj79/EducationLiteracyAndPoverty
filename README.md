# Effects of Education and Literacy on Poverty Probability

This project focuses on making a statistical inference about the effects of Education and Literacy on Poverty Probability. The aim is to perform an interpretation on the dataset with factors, Education and Literacy, and state whether how big or small of an effect they have on probability and whether the results are statistically significant or not. 



# Interpretation of analysis

<img src="img/Interpretation Image.png" alt="OLS model summary" title="Summary">



__Following interpretation can be drawn from the above obtained summary:__

1. The intercept of 0.71 means that when all variables take the value of 0 (all categorical variables are at the reference level), the average probability of poverty is 0.71. That is, when Education Level is at 0 and Literacy is TRUE, the probability that the individual is suffering from poverty is 71%. The p-value obtained for the intercept is < 0 which denotes that the result is statistically significant.

2. The coefficient for data$education_level.f1 is -0.03 and is significantly different from 0, suggesting that one unit increase in Education Level is associated with 0.03 units decrease in the probability that the individual is suffering from poverty, holding other variables constant. The p-value obtained for the coefficient data\$education_level.f1 is < 0 which denotes that the result is statistically significant.

3. The coefficient for data$education_level.f2 is -0.19 and is significantly different from 0, suggesting that one unit increase in Education Level is associated with 0.19 units decrease in the probability that the individual is suffering from poverty, holding other variables constant. The p-value obtained for the coefficient data\$education_level.f2 is < 0 which denotes that the result is statistically significant.

4. The coefficient for data$education_level.f3 is -0.32 and is significantly different from 0, suggesting that one unit increase in Education Level is associated with 0.32 units decrease in the probability that the individual is suffering from poverty, holding other variables constant. The p-value obtained for the coefficient data\$education_level.f3 is < 0 which denotes that the result is statistically significant.

5. The coefficient for data$literacy.fFalse does not differ significantly as the p-value obtained is > 0.05. 

From the above drawn interpretation we can conclude that, as the levels of Education increase, the chances of individual suffering from poverty decreases holding that value for Literacy is TRUE.