# Project 3

## Challenge 1

![c1](https://christinamauer.github.io/data100/challenge1.png)

![c2](https://christinamauer.github.io/data100/challenge2.png)


## Challenge 2

![c3](https://christinamauer.github.io/data100/challenge3.png)

Call:
lm(formula = pop20 ~ ntl...54 + dst190...62 + dst200...63, data = lbr_adm2)

Residuals:
   Min     1Q Median     3Q    Max 
-17950  -4125   -997   3654  16211 

Coefficients:
              Estimate Std. Error t value Pr(>|t|)    
(Intercept)  6.330e+03  1.782e+03   3.553 0.000592 ***
ntl...54     3.968e-01  1.878e-02  21.129  < 2e-16 ***
dst190...62  1.441e-03  1.077e-03   1.338 0.183989    
dst200...63 -9.681e-03  1.321e-03  -7.329 7.26e-11 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 6343 on 96 degrees of freedom
Multiple R-squared:  0.8252,	Adjusted R-squared:  0.8197 
F-statistic:   151 on 3 and 96 DF,  p-value: < 2.2e-16


![c4](https://christinamauer.github.io/data100/challenge4.png)

Call:
lm(formula = pop20 ~ water...16 + dst011...56 + dst040...57 + 
    dst130...58 + dst140...59 + dst150...60 + dst160...61 + dst190...62 + 
    dst200...63 + topo...25 + slope...26 + ntl...27, data = lbr_adm2)

Residuals:
     Min       1Q   Median       3Q      Max 
-17534.1  -4214.7   -836.5   3458.8  15173.4 

Coefficients: (1 not defined because of singularities)
              Estimate Std. Error t value Pr(>|t|)    
(Intercept)  7.384e+03  1.917e+03   3.852 0.000222 ***
water...16   5.293e-03  2.918e-03   1.814 0.073063 .  
dst011...56         NA         NA      NA       NA    
dst040...57 -8.766e-03  5.913e-03  -1.482 0.141820    
dst130...58 -1.901e-03  8.042e-03  -0.236 0.813668    
dst140...59 -4.632e-05  1.057e-04  -0.438 0.662434    
dst150...60 -7.829e-03  1.570e-02  -0.499 0.619282    
dst160...61 -6.706e-04  5.053e-04  -1.327 0.187885    
dst190...62  1.567e-03  1.732e-03   0.905 0.368055    
dst200...63 -3.993e-03  4.357e-03  -0.917 0.361858    
topo...25   -3.143e-04  2.360e-04  -1.332 0.186395    
slope...26   7.105e-03  5.963e-03   1.191 0.236688    
ntl...27     3.933e-01  1.973e-02  19.932  < 2e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 6304 on 88 degrees of freedom
Multiple R-squared:  0.8417,	Adjusted R-squared:  0.8219 
F-statistic: 42.53 on 11 and 88 DF,  p-value: < 2.2e-16
