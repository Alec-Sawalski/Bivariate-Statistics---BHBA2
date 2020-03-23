# Bivariate-Statistics---BHBA2
Updated Bivariate statistics for BHBA and predictors
# AS4_DD2_MCS_Bivariate_Statistics_BHBA_3_18_20
Dopfer
3/18/2020
Set working directory

#### BS.BHBA.1.2 ~ BS.Month_warm

    
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

#### BS.BHBA.1.2 ~ MS.DIM

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

#### BS.BHBA.1.2 ~ CE.Fat.Level

    glm(formula = BS.BHBA.1.2 ~ CE.Fat.Level, family = binomial(link = logit), 
        data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.0432  -0.6712  -0.6014  -0.5479   2.0722  

    Coefficients:
             Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -2.14410    0.25502  -8.408  < 2e-16 ***
    CE.Fat.Level  0.04044    0.01329   3.042  0.00235 ** 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 675.70  on 694  degrees of freedom
    Residual deviance: 666.63  on 693  degrees of freedom
    (17 observations deleted due to missingness)
    AIC: 670.63

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %    97.5 %
    (Intercept)  0.1171732 0.07043956 0.1917457
    CE.Fat.Level 1.0412702 1.01435798 1.0687792

#### BS.BHBA.1.2 ~ BS.NEFA.Log

    glm(formula = BS.BHBA.1.2 ~ BS.NEFA.Log, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.1894  -0.7129  -0.5020  -0.3348   2.4998  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -0.5163     0.1459  -3.539 0.000402 ***
    BS.NEFA.Log   1.0149     0.1423   7.134 9.76e-13 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 634.16  on 710  degrees of freedom
    AIC: 638.16

    Number of Fisher Scoring iterations: 5

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.5967023 0.4472168 0.7930437
    BS.NEFA.Log 2.7590339 2.1021784 3.6747065

#### BS.BHBA.1.2 ~ BS.DIM

    glm(formula = BS.BHBA.1.2 ~ BS.DIM, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.8008  -0.6822  -0.6234  -0.5601   2.0223  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)   
    (Intercept) -0.80610    0.30185  -2.671  0.00757 **
    BS.DIM      -0.03334    0.01530  -2.179  0.02932 * 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 689.66  on 710  degrees of freedom
    AIC: 693.66

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.4465953 0.2453844 0.8025838
    BS.DIM      0.9672133 0.9384097 0.9964962

#### BS.BHBA.1.2 ~ BS.MS.Date.Difference

    glm(formula = BS.BHBA.1.2 ~ BS.MS.Date.Difference, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6921  -0.6653  -0.6394  -0.6394   1.8764  

    Coefficients:
                      Estimate Std. Error z value Pr(>|z|)    
    (Intercept)           -1.39538    0.12803 -10.899   <2e-16 ***
    BS.MS.Date.Difference -0.08819    0.15954  -0.553     0.58    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 694.16  on 710  degrees of freedom
    AIC: 698.16

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                             OR     2.5 %    97.5 %
    (Intercept)           0.2477401 0.1913297 0.3163388
    BS.MS.Date.Difference 0.9155829 0.6703928 1.2541397
    
#### BS.BHBA.1.2 ~ Calving.No

    glm(formula = BS.BHBA.1.2 ~ Calving.No, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6729  -0.6537  -0.6482  -0.6456   1.8280  

    Coefficients:
             Estimate Std. Error z value Pr(>|z|)    
    (Intercept) -1.471659   0.173923  -8.462   <2e-16 ***
    Calving.No   0.009233   0.047439   0.195    0.846    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 694.43  on 710  degrees of freedom
    AIC: 698.43

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.2295443 0.1624063 0.3213934
    Calving.No  1.0092758 0.9178009 1.1058522

#### BS.BHBA.1.2 ~ Milk.Yield

    glm(formula = BS.BHBA.1.2 ~ Milk.Yield, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7151  -0.6767  -0.6676  -0.6550   1.8212  

    Coefficients:
             Estimate Std. Error z value Pr(>|z|)   
    (Intercept) -1.527699   0.554172  -2.757  0.00584 **
    Milk.Yield   0.004681   0.016675   0.281  0.77892   
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 388.97  on 386  degrees of freedom
    Residual deviance: 388.89  on 385  degrees of freedom
     (325 observations deleted due to missingness)
    AIC: 392.89

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR      2.5 %    97.5 %
    (Intercept) 0.2170345 0.07122811 0.6288628
    Milk.Yield  1.0046920 0.97254097 1.0384050

#### BS.BHBA.1.2 ~ MS.Milk.Yield

    glm(formula = BS.BHBA.1.2 ~ MS.Milk.Yield, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6758  -0.6522  -0.6491  -0.6462   1.8347  

    Coefficients:
               Estimate Std. Error z value Pr(>|z|)    
    (Intercept)   -1.483075   0.253404  -5.853 4.84e-09 ***
    MS.Milk.Yield  0.002651   0.015677   0.169    0.866    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 694.44  on 710  degrees of freedom
    AIC: 698.44

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                     OR     2.5 %    97.5 %
    (Intercept)   0.2269388 0.1381628 0.3737587
    MS.Milk.Yield 1.0026544 0.9713925 1.0331587

#### BS.BHBA.1.2 ~ MS.NEFA

    glm(formula = BS.BHBA.1.2 ~ MS.NEFA, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.8670  -0.7210  -0.6011  -0.5271   2.0296  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept) -2.03701    0.24034  -8.476  < 2e-16 ***
    MS.NEFA      0.12650    0.03929   3.220  0.00128 ** 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 539.99  on 538  degrees of freedom
    Residual deviance: 529.31  on 537  degrees of freedom
      (173 observations deleted due to missingness)
    AIC: 533.31

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR      2.5 %   97.5 %
    (Intercept) 0.1304186 0.07999888 0.205644
    MS.NEFA     1.1348526 1.05156326 1.227011

#### BS.BHBA.1.2 ~ BS.DIM

    glm(formula = BS.BHBA.1.2 ~ BS.DIM, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.8008  -0.6822  -0.6234  -0.5601   2.0223  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)   
    (Intercept) -0.80610    0.30185  -2.671  0.00757 **
    BS.DIM      -0.03334    0.01530  -2.179  0.02932 * 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 689.66  on 710  degrees of freedom
    AIC: 693.66

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.4465953 0.2453844 0.8025838
    BS.DIM      0.9672133 0.9384097 0.9964962

#### BS.BHBA.1.2 ~ MS.Fat

    glm(formula = BS.BHBA.1.2 ~ MS.Fat, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.4479  -0.6640  -0.5771  -0.4940   2.4264  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept) -3.42908    0.41521  -8.259  < 2e-16 ***
    MS.Fat       0.42811    0.08473   5.052 4.36e-07 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 668.28  on 710  degrees of freedom
    AIC: 672.28

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %     97.5 %
    (Intercept) 0.03241687 0.01409631 0.07206189
    MS.Fat      1.53434969 1.30178885 1.81666177

#### BS.BHBA.1.2 ~ MS.Protein

    glm(formula = BS.BHBA.1.2 ~ MS.Protein, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.1044  -0.6991  -0.5587  -0.4111   2.3506  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)   4.8725     1.1339   4.297 1.73e-05 ***
    MS.Protein   -1.9561     0.3552  -5.507 3.64e-08 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 660.64  on 710  degrees of freedom
    AIC: 664.64

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                     OR       2.5 %       97.5 %
    (Intercept) 130.6530588 14.62393008 1253.3748502
    MS.Protein    0.1414084  0.06941738    0.2798488

#### BS.BHBA.1.2 ~ MS.Lactose

    glm(formula = BS.BHBA.1.2 ~ MS.Lactose, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.8279  -0.6652  -0.6183  -0.5435   2.1000  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)   
    (Intercept)   5.6458     2.3311   2.422   0.0154 * 
    MS.Lactose   -1.4731     0.4853  -3.036   0.0024 **
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 684.81  on 710  degrees of freedom
    AIC: 688.81

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                     OR      2.5 %       97.5 %
    (Intercept) 283.1076978 3.20955127 3.057114e+04
    MS.Lactose    0.2292081 0.08636079 5.815501e-01

#### BS.BHBA.1.2 ~ MS.Acetone.Log

    glm(formula = BS.BHBA.1.2 ~ MS.Acetone.Log, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.9549  -0.7174  -0.5560  -0.2142   2.7517  

    Coefficients:
               Estimate Std. Error z value Pr(>|z|)    
    (Intercept)     -6.3002     0.7101  -8.873  < 2e-16 ***
    MS.Acetone.Log   1.1019     0.1452   7.588 3.25e-14 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 576.43  on 520  degrees of freedom
    Residual deviance: 500.15  on 519  degrees of freedom
     (191 observations deleted due to missingness)
    AIC: 504.15

    Number of Fisher Scoring iterations: 5
    
    Waiting for profiling to be done...
                        OR        2.5 %      97.5 %
    (Intercept)    0.001835986 0.0004284467 0.006966016
    MS.Acetone.Log 3.009813418 2.2885541425 4.048326873

#### BS.BHBA.1.2 ~ MS.Urea

    glm(formula = BS.BHBA.1.2 ~ MS.Urea, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.4456  -0.6688  -0.6070  -0.5382   2.0063  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept) -2.42352    0.32035  -7.565 3.87e-14 ***
    MS.Urea      0.03822    0.01163   3.287  0.00101 ** 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 683.78  on 710  degrees of freedom
    AIC: 687.78

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                        OR        2.5 %      97.5 %
    (Intercept)    0.001835986 0.0004284467 0.006966016
    MS.Acetone.Log 3.009813418 2.2885541425 4.048326873

#### BS.BHBA.1.2 ~ MS.S.Cell.Count.Log

    glm(formula = BS.BHBA.1.2 ~ MS.S.Cell.Count.Log, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7337  -0.6587  -0.6393  -0.6230   1.8697  

    Coefficients:
                    Estimate Std. Error z value Pr(>|z|)    
    (Intercept)         -1.69312    0.32013  -5.289 1.23e-07 ***
    MS.S.Cell.Count.Log  0.05927    0.07202   0.823     0.41    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 693.79  on 710  degrees of freedom
    AIC: 697.79
    
    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                           OR      2.5 %    97.5 %
    (Intercept)         0.1839456 0.09777438 0.3435657
    MS.S.Cell.Count.Log 1.0610660 0.91961523 1.2202637

#### BS.BHBA.1.2 ~ MS.pH

    glm(formula = BS.BHBA.1.2 ~ MS.pH, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.1192  -0.6654  -0.6255  -0.5860   1.9692  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)  
    (Intercept)   13.708      6.953   1.971   0.0487 *
    MS.pH         -2.285      1.049  -2.178   0.0294 *
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 689.90  on 710  degrees of freedom
    AIC: 693.9

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                      OR      2.5 %       97.5 %
    (Intercept) 8.979684e+05 0.85520607 7.334620e+11
    MS.pH       1.017863e-01 0.01303654 8.235371e-01

#### BS.BHBA.1.2 ~ MS.SFA

    glm(formula = BS.BHBA.1.2 ~ MS.SFA, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.4230  -0.7329  -0.6555  -0.5398   2.1827  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -2.7549     0.5335  -5.164 2.42e-07 ***
    MS.SFA        0.5654     0.1902   2.973  0.00295 ** 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 441.08  on 420  degrees of freedom
     (290 observations deleted due to missingness)
    AIC: 445.08

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %   97.5 %
    (Intercept) 0.06361453 0.02170187 0.177149
    MS.SFA      1.76013167 1.21701475 2.574248

#### BS.BHBA.1.2 ~ MS.MFA

    glm(formula = BS.BHBA.1.2 ~ MS.MFA, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.9085  -0.6625  -0.5414  -0.3918   2.4192  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -3.5752     0.3869  -9.241  < 2e-16 ***
    MS.MFA        1.5929     0.2392   6.660 2.73e-11 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 398.50  on 420  degrees of freedom
      (290 observations deleted due to missingness)
    AIC: 402.5

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %     97.5 %
    (Intercept) 0.02801033 0.01272922 0.05821857
    MS.MFA      4.91800353 3.12075690 7.99188713

#### BS.BHBA.1.2 ~ MS.PFA

    glm(formula = BS.BHBA.1.2 ~ MS.PFA, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.6700  -0.7052  -0.5758  -0.3628   2.4054  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -3.8185     0.4877  -7.829 4.91e-15 ***
    MS.PFA       15.5945     2.7513   5.668 1.44e-08 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 414.18  on 420  degrees of freedom
     (290 observations deleted due to missingness)
    AIC: 418.18

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                      OR        2.5 %       97.5 %
    (Intercept) 2.196125e-02 8.148268e-03 5.538004e-02
    MS.PFA      5.924131e+06 3.078850e+04 1.536874e+09

#### BS.BHBA.1.2 ~ MS.NSFA

    glm(formula = BS.BHBA.1.2 ~ MS.NSFA, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.7242  -0.6284  -0.5186  -0.4032   2.5649  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -3.6552     0.3182 -11.487  < 2e-16 ***
    MS.NSFA       0.1262     0.0164   7.696 1.41e-14 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1
    
    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 629.67  on 710  degrees of freedom
    AIC: 633.67

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %     97.5 %
    (Intercept) 0.02585601 0.01360692 0.04746619
    MS.NSFA     1.13454645 1.09931007 1.17248609

#### BS.BHBA.1.2 ~ MS.Palmeic

    glm(formula = BS.BHBA.1.2 ~ MS.Palmeic, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7594  -0.7159  -0.7108  -0.7031   1.7542  
    
    Coefficients:
            Estimate Std. Error z value Pr(>|z|)  
    (Intercept)  -1.3474     0.5562  -2.423   0.0154 *
    MS.Palmeic    0.0996     0.4860   0.205   0.8376  
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 450.07  on 420  degrees of freedom
    (290 observations deleted due to missingness)
    AIC: 454.07

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR      2.5 %   97.5 %
    (Intercept) 0.2599191 0.08778159 0.783009
    MS.Palmeic  1.1047304 0.41559900 2.817616

#### BS.BHBA.1.2 ~ MS.Stearine

    glm(formula = BS.BHBA.1.2 ~ MS.Stearine, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.8154  -0.6720  -0.5346  -0.3307   2.4811  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -4.1936     0.4643  -9.033  < 2e-16 ***
    MS.Stearine   5.3343     0.7715   6.914  4.7e-12 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 393.53  on 420  degrees of freedom
    (290 observations deleted due to missingness)
    AIC: 397.53

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                      OR        2.5 %       97.5 %
    (Intercept)   0.01509111  0.005849489   0.03625587
    MS.Stearine 207.33232604 47.825292935 992.52377440

#### BS.BHBA.1.2 ~ MS.Oleic

    glm(formula = BS.BHBA.1.2 ~ MS.Oleic, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.9565  -0.6553  -0.5424  -0.3755   2.4232  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -3.4454     0.3662  -9.407  < 2e-16 ***
    MS.Oleic      1.6113     0.2397   6.722  1.8e-11 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 450.11  on 421  degrees of freedom
    Residual deviance: 397.14  on 420  degrees of freedom
    (290 observations deleted due to missingness)
    AIC: 401.14

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                    OR      2.5 %     97.5 %
    (Intercept) 0.03189325 0.01510683 0.06370411
    MS.Oleic    5.00940813 3.17636735 8.15182338

#### BS.BHBA.1.2 ~ CE.Temp

    glm(formula = BS.BHBA.1.2 ~ CE.Temp, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.9037  -0.6447  -0.6437  -0.6416   1.8356  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)
    (Intercept) -2.14415    1.80831  -1.186    0.236
    CE.Temp      0.01758    0.04675   0.376    0.707

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 674.04  on 697  degrees of freedom
    Residual deviance: 673.92  on 696  degrees of freedom
    (14 observations deleted due to missingness)
    AIC: 677.92
        
    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                  OR       2.5 %    97.5 %
    (Intercept) 0.117168 0.002630313 30.219421
    CE.Temp     1.017740 0.881258738  1.122815

#### BS.BHBA.1.2 ~ CE.Environ.Temp

    glm(formula = BS.BHBA.1.2 ~ CE.Environ.Temp, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6612  -0.6526  -0.6474  -0.6426   1.8414  

    Coefficients:
                 Estimate Std. Error z value Pr(>|z|)    
    (Intercept)     -1.402781   0.273691  -5.125 2.97e-07 ***
    CE.Environ.Temp -0.002771   0.015428  -0.180    0.857    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 654.83  on 672  degrees of freedom
    Residual deviance: 654.80  on 671  degrees of freedom
    (39 observations deleted due to missingness)
    AIC: 658.8

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                       OR     2.5 %    97.5 %
    (Intercept)     0.2459121 0.1421530 0.4163245
    CE.Environ.Temp 0.9972331 0.9675062 1.0279192

#### BS.BHBA.1.2 ~ BS.Cow.Breed

    glm(formula = BS.BHBA.1.2 ~ Cow.Breed, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7209  -0.7209  -0.5297  -0.5297   2.0166  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -1.2149     0.1139 -10.669  < 2e-16 ***
    Cow.Breed02  -0.6780     0.2120  -3.199  0.00138 ** 
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 683.55  on 710  degrees of freedom
    AIC: 687.55

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.2967359 0.2362483 0.3693603
    Cow.Breed02 0.5076151 0.3315272 0.7625881
    
       0   1
     01 337 100
     02 239  36
    
         0     1
    01 58.51 73.53
    02 41.49 26.47

#### BS.BHBA.1.2 ~ Hfr.or.Cow

#### BS.BHBA.1.2 ~ BS.Month

#### BS.BHBA.1.2 ~ CE.Skin.Dehydration

#### BS.BHBA.1.2 ~ CE.Stom.Tension

#### BS.BHBA.1.2 ~ CE.Stom.Layering

#### BS.BHBA.1.2 ~ CE.Stom.Fluid.Movement

#### BS.BHBA.1.2 ~ CE.Stom.Ping

#### BS.BHBA.1.2 ~ CE.Stom.Fullness.2

#### BS.BHBA.1.2 ~ CE.Stom.Noise.Freq

#### BS.BHBA.1.2 ~ CE.Waste.Consistency.2

#### BS.BHBA.1.2 ~ CE.Waste.Digestion

#### BS.BHBA.1.2 ~ CE.Locomotion.Score

#### BS.BHBA.1.2 ~ CE.Lame

#### BS.BHBA.1.2 ~ BS.NEFA.0.7

#### BS.BHBA.1.2 ~ FPR.1.4
