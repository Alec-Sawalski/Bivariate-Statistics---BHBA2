# Bivariate-Statistics---BHBA2
Updated Bivariate statistics for BHBA and predictors
# AS4_DD2_MCS_Bivariate_Statistics_BHBA_3_18_20
Dopfer
3/18/2020
Set working directory

#### BS.BHBA.1.2 ~ BS.Month_warm
'''r
      Call:
     glm(formula = BS.BHBA.1.2 ~ BS.Month_warm, family = binomial(link = logit), 
      data = hp9)
 
     Deviance Residuals: 
         Min       1Q   Median       3Q      Max  
     -0.6966  -0.6966  -0.6145  -0.6145   1.8761  
 
     Coefficients:
                Estimate Std. Error z value Pr(>|z|)    
     (Intercept)     -1.5710     0.1323 -11.874   <2e-16 ***
     BS.Month_warm1   0.2786     0.1911   1.457    0.145    
     ---
     Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
 
     (Dispersion parameter for binomial family taken to be 1)

     Null deviance: 694.46  on 711  degrees of freedom
     Residual deviance: 692.35  on 710  degrees of freedom
     AIC: 696.35
 
    Number of Fisher Scoring iterations: 4


<img src="https://user-images.githubusercontent.com/61294969/77189745-0dfcad00-6aa6-11ea-9274-df57a926a5cb.png">

'''

Call:
glm(formula = BS.BHBA.1.2 ~ MS.DIM, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
        Min       1Q   Median       3Q      Max  
    -0.8146  -0.6862  -0.6188  -0.5633   2.0267  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)   
    (Intercept) -0.83435    0.29501  -2.828  0.00468 **
     MS.DIM      -0.03279    0.01535  -2.136  0.03267 * 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 689.85  on 710  degrees of freedom
    AIC: 693.85
    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.4341577 0.2417371 0.7697091
    MS.DIM      0.9677383 0.9388251 0.9971465


