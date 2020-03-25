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

<img src="https://user-images.githubusercontent.com/61294969/77337940-9faf2900-6cf7-11ea-86ea-cdffca2eae72.png">

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
    
   <img src=https://user-images.githubusercontent.com/61294969/77543528-d3b05880-6e75-11ea-87b3-c8aaa99bb54e.png>
   <img src=https://user-images.githubusercontent.com/61294969/77543542-db6ffd00-6e75-11ea-8287-6b78dd88a769.png>

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
    
<img src=https://user-images.githubusercontent.com/61294969/77545239-25f27900-6e78-11ea-90aa-5fba806c54af.png>
<img src=https://user-images.githubusercontent.com/61294969/77545254-2d198700-6e78-11ea-8070-a246c54feaca.png>


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

<img src=https://user-images.githubusercontent.com/61294969/77545478-7964c700-6e78-11ea-8b55-7d6e5abcc3ef.png>
<img src=https://user-images.githubusercontent.com/61294969/77545499-7f5aa800-6e78-11ea-84b9-44466e1faa1c.png>

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
    
  <img src=https://user-images.githubusercontent.com/61294969/77549922-7371e480-6e7e-11ea-8e7d-03a0a0ca2072.png>
  <img src=https://user-images.githubusercontent.com/61294969/77549942-78cf2f00-6e7e-11ea-90b9-dc747840fac4.png>

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
    
  <img src=https://user-images.githubusercontent.com/61294969/77550179-c3e94200-6e7e-11ea-863a-c79feecdcb22.png>
  <img src=https://user-images.githubusercontent.com/61294969/77550201-cb105000-6e7e-11ea-871f-44465b5b8b40.png>
    
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
    
  <img src=https://user-images.githubusercontent.com/61294969/77550531-36f2b880-6e7f-11ea-9693-cac3386ea14b.png>
  <img src=https://user-images.githubusercontent.com/61294969/77550552-3ce89980-6e7f-11ea-8166-39e8800c5f37.png>

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

    glm(formula = BS.BHBA.1.2 ~ Hfr.or.Cow, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6644  -0.6456  -0.6456  -0.6456   1.8279  

    Coefficients:
              Estimate Std. Error z value Pr(>|z|)    
    (Intercept)   -1.39842    0.17440  -8.019 1.07e-15 ***
    Hfr.or.Cowcow -0.06386    0.20828  -0.307    0.759    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 694.37  on 710  degrees of freedom
    AIC: 698.37
    
    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                     OR     2.5 %   97.5 %
    (Intercept)   0.2469880 0.1732598 0.343877
    Hfr.or.Cowcow 0.9381321 0.6273656 1.421892
     
        0   1
    cow 410  95
    hfr 166  41
     
          0     1
    cow 71.18 69.85
    hfr 28.82 30.15

#### BS.BHBA.1.2 ~ BS.Month

    glm(formula = BS.BHBA.1.2 ~ BS.Month, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7718  -0.7074  -0.6354  -0.5148   2.0429  

    Coefficients:
                Estimate Std. Error z value Pr(>|z|)    
    (Intercept)     -1.92789    0.37839  -5.095 3.49e-07 ***
    BS.Month07-2018  0.43037    0.46386   0.928   0.3535    
    BS.Month08-2018  0.67021    0.43298   1.548   0.1216    
    BS.Month09-2018  0.78276    0.45382   1.725   0.0846 .  
    BS.Month10-2018 -0.02639    0.45863  -0.058   0.9541    
    BS.Month11-2018  0.54160    0.43529   1.244   0.2134    
    BS.Month12-2018  0.86928    0.47161   1.843   0.0653 .  
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 684.25  on 705  degrees of freedom
    AIC: 698.25

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                       OR     2.5 %    97.5 %
    (Intercept)     0.1454545 0.0639921 0.2877973
    BS.Month07-2018 1.5378289 0.6357059 4.0032223
    BS.Month08-2018 1.9546569 0.8703565 4.8475182
    BS.Month09-2018 2.1875000 0.9280455 5.6106246
    BS.Month10-2018 0.9739583 0.4068312 2.5116631
    BS.Month11-2018 1.7187500 0.7608650 4.2773306
    BS.Month12-2018 2.3852041 0.9711338 6.2978535
         
            0   1
    06-2018  55   8
    07-2018  76  17
    08-2018 102  29
    09-2018  66  21
    10-2018 120  17
    11-2018 108  27
    12-2018  49  17
         
              0     1
    06-2018  9.55  5.88
    07-2018 13.19 12.50
    08-2018 17.71 21.32
    09-2018 11.46 15.44
    10-2018 20.83 12.50
    11-2018 18.75 19.85
    12-2018  8.51 12.50

#### BS.BHBA.1.2 ~ CE.Skin.Dehydration

    glm(formula = BS.BHBA.1.2 ~ CE.Skin.Dehydration, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6518  -0.6518  -0.6518  -0.6518   2.0782  

    Coefficients:
                       Estimate Std. Error z value Pr(>|z|)    
    (Intercept)            -1.44097    0.09791 -14.717   <2e-16 ***
    CE.Skin.Dehydrationred -0.59591    0.62160  -0.959    0.338    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 677.80  on 699  degrees of freedom
    Residual deviance: 676.74  on 698  degrees of freedom
    (12 observations deleted due to missingness)
    AIC: 680.74

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                              OR     2.5 %    97.5 %
    (Intercept)            0.2366972 0.1945937 0.2857323
    CE.Skin.Dehydrationred 0.5510617 0.1293253 1.6140580
     
        0   1
    phy 545 129
    red  23   3
     
          0     1
    phy 95.95 97.73
    red  4.05  2.27

#### BS.BHBA.1.2 ~ CE.Stom.Tension

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Tension, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6541  -0.6541  -0.6541  -0.5799   2.0593  

    Coefficients:
                   Estimate Std. Error z value Pr(>|z|)    
    (Intercept)        -1.43318    0.09954 -14.398   <2e-16 ***
    CE.Stom.Tensionerh -0.55925    0.44643  -1.253     0.21    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 674.46  on 698  degrees of freedom
    Residual deviance: 672.68  on 697  degrees of freedom
    (13 observations deleted due to missingness)
    AIC: 676.68

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                          OR     2.5 %    97.5 %
    (Intercept)        0.2385496 0.1954680 0.2888592
    CE.Stom.Tensionerh 0.5716364 0.2146561 1.2737202
     
        0   1
     phy 524 125
     erh  44   6
     
          0     1
     phy 92.25 95.42
    erh  7.75  4.58

#### BS.BHBA.1.2 ~ CE.Stom.Layering

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Layering, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6681  -0.6441  -0.6441  -0.6441   1.8303  

    Coefficients:
                  Estimate Std. Error z value Pr(>|z|)    
    (Intercept)       -1.46755    0.09843 -14.909   <2e-16 ***
    CE.Stom.Layering0  0.08125    0.56762   0.143    0.886    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 674.04  on 697  degrees of freedom
    Residual deviance: 674.02  on 696  degrees of freedom
    (14 observations deleted due to missingness)
    AIC: 678.02

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                        OR     2.5 %    97.5 %
    (Intercept)       0.230490 0.1892798 0.2784984
    CE.Stom.Layering0 1.084646 0.3067791 3.0165598
   
      0   1
    1 551 127
    0  16   4
   
        0     1
    1 97.18 96.95
    0  2.82  3.05

#### BS.BHBA.1.2 ~ CE.Stom.Fluid.Movement

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Fluid.Movement, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.6529  -0.6529  -0.6529  -0.6529   2.0782  

    Coefficients:
                         Estimate Std. Error z value Pr(>|z|)    
    (Intercept)              -1.43730    0.09795 -14.674   <2e-16 ***
    CE.Stom.Fluid.Movementre -0.59959    0.62161  -0.965    0.335    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 676.97  on 697  degrees of freedom
    Residual deviance: 675.89  on 696  degrees of freedom
    (14 observations deleted due to missingness)
    AIC: 679.89

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                                OR     2.5 %    97.5 %
    (Intercept)              0.2375691 0.1952981 0.2868054
    CE.Stom.Fluid.Movementre 0.5490394 0.1288497 1.6081563
     
        0   1
    obb 543 129
    re   23   3
     
          0     1
    obb 95.94 97.73
    re   4.06  2.27

#### BS.BHBA.1.2 ~ CE.Stom.Ping

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Ping, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7585  -0.6458  -0.6458  -0.6458   1.8276  

    Coefficients:
               Estimate Std. Error z value Pr(>|z|)    
    (Intercept)    -1.46163    0.09697 -15.073   <2e-16 ***
    CE.Stom.Pingre  0.36302    1.15876   0.313    0.754    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 677.80  on 699  degrees of freedom
    Residual deviance: 677.71  on 698  degrees of freedom
    (12 observations deleted due to missingness)
    AIC: 681.71

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                      OR     2.5 %     97.5 %
    (Intercept)    0.2318584 0.1909747  0.2793839
    CE.Stom.Pingre 1.4376590 0.0708069 11.3293260
     
        0   1
    re    3   1
    obb 565 131
     
          0     1
    re   0.53  0.76
    obb 99.47 99.24

#### BS.BHBA.1.2 ~ CE.Stom.Fullness.2

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Fullness.2, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7585  -0.6465  -0.6465  -0.6465   1.8265  

    Coefficients:
                       Estimate Std. Error z value Pr(>|z|)    
    (Intercept)            -1.45916    0.09774 -14.928   <2e-16 ***
    CE.Stom.Fullness.2high  0.36054    1.15883   0.311    0.756    
    CE.Stom.Fullness.2low   0.36054    0.48143   0.749    0.454    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 693.85  on 709  degrees of freedom
    AIC: 699.85

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                              OR      2.5 %    97.5 %
    (Intercept)            0.2324324 0.19114690  0.280485
    CE.Stom.Fullness.2high 1.4341085 0.07062716 11.302955
    CE.Stom.Fullness.2low  1.4341085 0.51164043  3.496510
        
           0   1
     normal 555 129
    high     3   1
    low     18   6
        
             0     1
    normal 96.35 94.85
    high    0.52  0.74
    low     3.12  4.41

#### BS.BHBA.1.2 ~ CE.Stom.Noise.Freq

    glm(formula = BS.BHBA.1.2 ~ CE.Stom.Noise.Freq, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.9218  -0.5855  -0.5855  -0.4952   2.0782 

    Coefficients:
                         Estimate Std. Error z value Pr(>|z|)    
    (Intercept)               -1.6767     0.2272  -7.381 1.58e-13 ***
    CE.Stom.Noise.Freqbis_2    1.0407     0.3696   2.816  0.00486 ** 
    CE.Stom.Noise.Freqgroe_3  -0.3602     0.6545  -0.550  0.58211    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 221.94  on 223  degrees of freedom
    Residual deviance: 212.86  on 221  degrees of freedom
    (488 observations deleted due to missingness)
    AIC: 218.86

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                                OR     2.5 %    97.5 %
    (Intercept)              0.1869919 0.1168547 0.2859197
    CE.Stom.Noise.Freqbis_2  2.8312020 1.3645873 5.8504195
    CE.Stom.Noise.Freqgroe_3 0.6975425 0.1565385 2.2223888
        
           0   1
    phy    123  23
    bis_2   34  18
    groe_3  23   3
        
             0     1
    phy    68.33 52.27
    bis_2  18.89 40.91
    groe_3 12.78  6.82

#### BS.BHBA.1.2 ~ CE.Waste.Consistency.2

    glm(formula = BS.BHBA.1.2 ~ CE.Waste.Consistency.2, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7832  -0.6303  -0.6303  -0.6303   1.8515  

    Coefficients:
                            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)                  -1.5154     0.1116 -13.583   <2e-16 ***
    CE.Waste.Consistency.2thick   0.4908     0.3309   1.483    0.138    
    CE.Waste.Consistency.2thin    0.1825     0.2552   0.715    0.474    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 692.13  on 709  degrees of freedom
    AIC: 698.13

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                                   OR     2.5 %    97.5 %
    (Intercept)                 0.2197309 0.1756313 0.2721084
    CE.Waste.Consistency.2thick 1.6336996 0.8284874 3.0598428
    CE.Waste.Consistency.2thin  1.2002691 0.7156744 1.9533102
       
          0   1
    norm  446  98
    thick  39  14
    thin   91  24
       
            0     1
    norm  77.43 72.06
    thick  6.77 10.29
    thin  15.80 17.65

#### BS.BHBA.1.2 ~ CE.Waste.Digestion

    glm(formula = BS.BHBA.1.2 ~ CE.Waste.Digestion, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7040  -0.6339  -0.6339  -0.6339   1.8460  

    Coefficients:
                        Estimate Std. Error z value Pr(>|z|)    
    (Intercept)              -1.5029     0.1134 -13.249   <2e-16 ***
    CE.Waste.Digestionmaess   0.2344     0.2201   1.065    0.287    
    CE.Waste.Digestionschl  -13.0632   441.3717  -0.030    0.976    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 670.7  on 689  degrees of freedom
    Residual deviance: 667.9  on 687  degrees of freedom
     (22 observations deleted due to missingness)
    AIC: 673.9

    Number of Fisher Scoring iterations: 13

    Waiting for profiling to be done...
    values                                  OR     2.5 %       97.5 %
    (Intercept)             2.224824e-01 0.1771505 2.764943e-01
    CE.Waste.Digestionmaess 1.264145e+00 0.8136817 1.932578e+00
    CE.Waste.Digestionschl  2.121981e-06        NA 2.005102e+16
       
          0   1
    gut   427  95
    maess 128  36
    schl    4   0
       
            0     1
    gut   76.39 72.52
    maess 22.90 27.48
    schl   0.72  0.00

#### BS.BHBA.1.2 ~ CE.Locomotion.Score

    glm(formula = BS.BHBA.1.2 ~ CE.Locomotion.Score, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -1.1774  -0.6350  -0.6222  -0.6095   1.8841  

    Coefficients:
                     Estimate Std. Error z value Pr(>|z|)    
    (Intercept)          -1.54369    0.13560 -11.384  < 2e-16 ***
    CE.Locomotion.Score2  0.04491    0.21798   0.206  0.83676    
    CE.Locomotion.Score3 -0.04555    0.37255  -0.122  0.90269    
    CE.Locomotion.Score4  1.36136    0.44913   3.031  0.00244 ** 
    CE.Locomotion.Score5  1.54369    1.42070   1.087  0.27723    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 664.03  on 687  degrees of freedom
    Residual deviance: 654.39  on 683  degrees of freedom
    (24 observations deleted due to missingness)
    AIC: 664.39

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                            OR     2.5 %      97.5 %
    (Intercept)          0.2135922 0.1624220   0.2766184
    CE.Locomotion.Score2 1.0459381 0.6786679   1.5980299
    CE.Locomotion.Score3 0.9554731 0.4374151   1.9116569
    CE.Locomotion.Score4 3.9015152 1.5854797   9.4242092
    CE.Locomotion.Score5 4.6818182 0.1835843 119.4044849
   
      0   1
    1 309  66
    2 188  42
    3  49  10
    4  12  10
    5   1   1
   
        0     1
    1 55.28 51.16
    2 33.63 32.56
    3  8.77  7.75
    4  2.15  7.75
    5  0.18  0.78

#### BS.BHBA.1.2 ~ CE.Lame

    glm(formula = BS.BHBA.1.2 ~ CE.Lame, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.7638  -0.6355  -0.6355  -0.6355   1.8435  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -1.4973     0.1032  -14.52   <2e-16 ***
    CE.Lame1      0.4147     0.2727    1.52    0.128    
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 692.27  on 710  degrees of freedom
    AIC: 696.27

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept) 0.2237354 0.1819541 0.2727376
    CE.Lame1    1.5138850 0.8700739 2.5469113
   
      0   1
    0 514 115
    1  62  21
   
        0     1
    0 89.24 84.56
    1 10.76 15.44


#### BS.BHBA.1.2 ~ BS.NEFA.0.7

    glm(formula = BS.BHBA.1.2 ~ BS.NEFA.0.7, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.9518  -0.5672  -0.5672  -0.5672   1.9527  

    Coefficients:
             Estimate Std. Error z value Pr(>|z|)    
    (Intercept)   -1.7456     0.1176 -14.850  < 2e-16 ***
    BS.NEFA.0.71   1.1888     0.2113   5.625 1.85e-08 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 664.43  on 710  degrees of freedom
    AIC: 668.43

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR     2.5 %    97.5 %
    (Intercept)  0.174538 0.1377193 0.2184596
    BS.NEFA.0.71 3.283146 2.1643013 4.9624374
   
      0   1
     0 487  85
     1  89  51
   
        0     1
    0 84.55 62.50
    1 15.45 37.50

#### BS.BHBA.1.2 ~ FPR.1.4

    glm(formula = BS.BHBA.1.2 ~ FPR.1.4, family = binomial(link = logit), 
    data = hp9)

    Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
    -0.8627  -0.8627  -0.4907  -0.4907   2.0864  

    Coefficients:
            Estimate Std. Error z value Pr(>|z|)    
    (Intercept)  -2.0562     0.1517 -13.553  < 2e-16 ***
    FPR.1.41      1.2594     0.1992   6.321 2.59e-10 ***
    ---
    Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

    (Dispersion parameter for binomial family taken to be 1)

    Null deviance: 694.46  on 711  degrees of freedom
    Residual deviance: 652.54  on 710  degrees of freedom
    AIC: 656.54

    Number of Fisher Scoring iterations: 4

    Waiting for profiling to be done...
                   OR      2.5 %    97.5 %
    (Intercept) 0.1279373 0.09388698 0.1703984
    FPR.1.41    3.5234218 2.39452884 5.2359645
   
      0   1
    0 383  49
    1 193  87
   
        0     1
    0 66.49 36.03
    1 33.51 63.97


