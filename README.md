# Analyzing Factors Affecting Graduation Rate at Higher Education Institutions in the U.S.

## View full project [here](https://github.com/conniehuang14/data-science/blob/main/INFO%202950-%20Data%20Science%20Final%20Project.ipynb).

### Overview
Project by Connie Huang and Sophie Ruan.

This project analyzes factors that affect the graduation rate of first-time, full-time students attending 4-year universities in the United States. We examined several factors such as students’ academics, the institution’s admissions, aid, cost of attendance, funding source, as well as the student body’s racial diversity and socio-economic status. We analyzed the relationships using linear regression to determine the extent to which there is a linear relationship between each factor and the graduation rate. In order to evaluate the significance of the results of each linear regression, we decided to create permutations of the variables used for the linear regression to assess the significance of the results.

### Data
Dataset: https://collegescorecard.ed.gov/data/

The dataset used was collected for the College Scorecard, an online tool created by the United States Department of Education to aid prospective higher education students receiving federal financial aid to compare high education institutions. The dataset was filtered for any null values in the columns used for linear regression analysis.

### Process
1. We analyzed the relationships using linear regression to determine the extent to which there is a linear relationship between each factor and the graduation rate. We calculated the Pearson correlation coefficient to determine the strength of the linear correlation. 
2. We then calculated the coefficient of determination, or the r^2 score, to determine the proportion of the variance in the dependent variable, graduation rate, that is explained by the independent variables in the linear model. 
3. In order to evaluate the significance of the slope, we decided to create permutations of the variables used for the linear regression to assess the significance of the slopes. The permutation shuffles the order of one of the variables, and then is analyzed through a linear regression with the unchanged second variable. We then plot this on a histogram to see all instances of all slopes generated from the linear regression analyses using random permutations. We then compared this histogram with the actual linear regression slope from the actual dataset. 
4. We can evaluate whether or not the slope is likely to be a result of random chance, rather than an indication of a strong relationship between the two variables. 
5. We can evaluate whether or not the slope is significant. We can visually assess that all the slopes fall on a Gaussian distribution, with most histograms containing slope value ranges with minimum and maximum values with similar absolute values.

### Conclusion
- There are positive relationships that are not likely of random chance between student completion rate with average equivalent SAT score and student completion rate with admission rate at higher education institutions 
- There is a strong negative relationship between Pell Grant recipients and completion rate
- There are strong positive relationships not likely of random chance for White, Black, and Hispanic student completion rate with average attendance cost across all higher education institutions
- There is a strong positive relationship not likely of random chance for students across all income brackets at public institutions with completion rate, and for students across lower to upper-middle income brackets for private institutions with completion rate
