# life_expectancy_drivers
The goal of this project was to determine what factors are significant drivers for life expectancy in various countries.

Health data was obtained from the WHO Global Health Observatory, economic data from the UN Human Development Reports, and social and emotional data from the UN's World Happiness Report.

Data was cleaned and merged, then variables were transformed to meet linear model assumptions (lienarity, independent and normally distributed residuals with constant variance, no multicollinearity).

Backward and forward stepwise regression was performed to determine what variables may be significant. 

In the end, some of the key predictors for life expectancy were: adult mortality, prevalence of thinness in youths, number of years of schooling, HIV/AIDS, and infant deaths, which generally make sense.

We further discovered that we could not simply drop all emotional and social markers, with the delivery quality of government services, reporting feeling positive emotions, and reporting feeling negative emotions being statistically significant when predicting life expectancy.
