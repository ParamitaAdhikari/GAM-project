# GAM
dataset:https://www.kaggle.com/kumarajarshi/life-expectancy-who
my colab notenook: https://colab.research.google.com/drive/1niCcCY393yOI_4SOQHOPIPsrwZk1JUtu?usp=sharing

I have worked on Life expectancy data from Kaggle. After taking care of missing entries, I have plotted many graphs to understand the trends in the data and how various features affect Life expectancy of a Country. Then after encoding the categorical variables, I fit a Linear Generalised Additive Model(GAM) on the data followed by a Gamma GAM. The train-test ratio is 7:3 and the results show both models work well. 
Here are some observations:
1. Life expectancy is higher in developed countries compared to developing countries
2. It increases with time, i.e., year.
3. It is negetively correlated to adult mortality.
4. Diseases like 'Measles ', 'Polio', ' thinness 5-9 years'do not affect Life expectancy.
5. The population of a Country is not a significant factor for its Life expectancy, nor is the GDP.
