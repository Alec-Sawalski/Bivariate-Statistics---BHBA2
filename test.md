# Bivariate-Statistics---BHBA2
Updated Bivariate statistics for BHBA and predictors
# AS4_DD2_MCS_Bivariate_Statistics_BHBA_3_18_20
Dopfer
3/18/2020
Set working directory

## [1] "C:/Users/sawalski/Desktop"
#Load libraries

BS.BHBA.1.2 ~ BS.Month + (1|CowID:Farm.No) - BS.Month_warm compared to high or low BHBA levels (cutoff: >=1.2 is hi and <1.2 is low)

## 
## Call:
## glm(formula = BS.BHBA.1.2 ~ BS.Month_warm, family = binomial(link = logit), 
##     data = hp9)
## 
## Deviance Residuals: 
##     Min       1Q   Median       3Q      Max  
## -0.6966  -0.6966  -0.6145  -0.6145   1.8761  
## 
## Coefficients:
##                Estimate Std. Error z value Pr(>|z|)    
## (Intercept)     -1.5710     0.1323 -11.874   <2e-16 ***
## BS.Month_warm1   0.2786     0.1911   1.457    0.145    
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## (Dispersion parameter for binomial family taken to be 1)
## 
##     Null deviance: 694.46  on 711  degrees of freedom
## Residual deviance: 692.35  on 710  degrees of freedom
## AIC: 696.35
## 
## Number of Fisher Scoring iterations: 4


<img src="https://user-images.githubusercontent.com/61294969/77189745-0dfcad00-6aa6-11ea-9274-df57a926a5cb.png">

