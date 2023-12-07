# datasci_5_statistics

## Chi2 test

### Rationale

For this chi2 test I decided to use a COVID-19 seroprevalence dataset in order to see if there is a relationship between Age and seroprevalence of COVID-19. Previous to my analysis I would have expected the younger population to develop more serovprevalence. In this dataset, I liked how the indicator of seroprevalence took into account both COVID-19 vaccination and past COVID-19 infections. These points are very important when trying to understand the development of COVID-19 seroprevalence. 

### Patterns

While running the chi2 test I realized that there seems to be an equal distribution between all the groups in variable 1 (age) and variable 2 (COVID-19 seroprevalence (indicator)). Due to this equal distribution, I belive I recieved the p-value and chi2 value which I did which not only suggested that there is not relationship between there variables but that the null hypothesis is supported almost perfectly. In the future, if I were to run a chi2 test, I will make sure that there is not an equal distribution between the groups and would like to take a look at another COVID-19 seroprevalence dataset to check if my hypothesis is true. 

## T-test 

### Rationale

Out of all the tests conducted, I struggled the most with the T-Test. For this portion I ran two tests as the first one produced a T-value and p-value I did not like. For the second T-Test I found a dataset on the death rate in NYC. For this test I decided to take a look at if there is a difference between the death rate of females and males, the two categories in gender. It was challenging to run the T-test due to there being strings present in the dataset. In order to get the test to run I had to get rid of the strings, which were parenthesis following the death rate values. Once I was able to get rid of the strings, which I made the decision to do so as my analysis did not include these values, I was able to run the test. 

### Patterns 

Based off of the p-value and T-value populated, it can be concluded that there is no significant difference between the death rates of females and males in NYC. 

## ANOVA 

### Rationale 

For the ANOVA portion I decided to run a two-way ANOVA similar to what we did in class. For the ANOVA I found a dataset which took a look at different variables which cause stroke. With in this dataset I found the variables of bmi, smoke status, and residence type to be interesting. From prior knowledge I was aware that smoking tends to cause a higher bmi and wanted to see if this was in fact true. I also wanted to take a look if the location of residence had an impact on bmi. If residence does have an impact, I think it would be cool to check if there is difference between the food consumed in rural and urban residences and if that is what impacted the difference in bmi. 

### Patterns 

Based off of the F and p-values calculated it can be concluded that there the two independent variables residence type and smoking status have an impact on the dependent variable of bmi. Along with that due a very high F-value, we know that there is a big difference of bmi between the groups in the smoking status category. I would like to conduct further analysis in order to figure out which group differs the most within this category. 

## Regression Analysis

### Rationale

For the regression analysis I chose to use a dataset which took a look at variables which impact heart risk. The variables I used for the analysis are hdl and risk of heart attack. I wanted to see if there is a relationship between hdl values and the risk of heart attack. 

### Patterns 

Looking at the plot created to see the relationship between hdl vaue and risk of heart attack, there seems to be no specific pattern like expected. The data points are not moving in a specific direction, rather scattered everywhere, which is supported by the r2 value that there is a weak relationship between these two variables. 
