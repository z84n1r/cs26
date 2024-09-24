java c
STAT 5900 F: Longitudinal Data Analysis
Assignment 1
Due Friday, October 4, 2024
Instructions: Use R for statistical analysis. Show details of your work for full marks. Scan your answer sheet as a single PDF file with the correct page order in a clear manner, and submit it to Brightspace.
1. The data file “stat5900.assign1.datafile.txt” uploaded in Brightspace contains bivariate data on the response y and covariate x obtained from 20 subjects, each with four measurements. Consider fitting the linear mixed effects model
yij = β0 + β1xij + ui + ϵij   (i = 1, . . . , 20; j = 1, . . . , 4),                         (1)
where ui’s are independent N(0, σ2u), ϵij ’s are independent N(0, σϵ2), and ui and ϵij are independent of each other.
(a) Derive Var(yij ), Cov(yij , yij′) and Cov(yi′j, yij ).
(b) For simultaneous maximum likelihood (ML) estimation of τ = (βt, θt)t with β = (β0, β1)t and θ = (σ2u, σϵ2)t, derive the Fisher Information matrix (show details of your calculation)

(c) Compute the ML estimate of τ using the Newton-Raphson iterative equation
τ(m+1) = τ(m) + [I(τ)]−1U(τ),
where the score function U(τ ) = ∂ log L/∂τ and the Fisher Information I(τ ) are evaluated at τ(m)(s代 写STAT 5900 F: Longitudinal Data Analysis Assignment 1 2024R
代做程序编程语言how details of your computation).
(d) Compute the standard errors of the ML estimates from the Fisher Information matrix.
(e) Test H0 : β1 = 0 versus H1 : β1 ≠ 0 using asymptotic properties of ML estimators. What is the p-value of the test?
(f) Compute the efficiency of the ML estimates of (β0, β1) under a “misspecified” model with σ2u = 0.
2. Recall the Sitka spruce data as discussed in Example 4.1 in the textbook (also, see the R code given in class). Refit the model below using data from only Chambers 1 (treated with ozone) and 4 (control) for year 1988:
yij = β1xi1 + . . . + β5xi5 + ηTreati + γTimej + ϵij ,
where xij = 1 for time tj and 0, otherwise (i = 1, . . . , m, j = 1, . . . , 5), Treatiis 1 for control and 0 for treatment, and Timej = dayj/100 for control and 0 for treatment.
(a) Find the REML estimate of the variance-covariance matrix V0 of the response vector yi.
(b) Find estimates of the regression coefficients and their standard errors.
(c) Assuming normality of the errors ϵij , test the hypothesis of no treatment effect, that is test H0 : η = γ = 0. What is the p-value of the test? Draw conclusions of the test.





         
加QQ：99515681  WX：codinghelp
