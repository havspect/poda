# Advanced Methods
Methods to examine the structure of a data set: 
- T-test
- Cluster Analysis 
- *Confirmatory Factor Analysis (CFA)* 

Methods to test relationships in data sets:
- Linear Regression
- Multiple Regression

General methods: 
- *Structural equation modelling*

## General Methods

### Structural equation modelling
Structural equation modelling is a multivariate statistical analysis technique used to analyse the complex structural relationship between measured variables and latent constructs. Usage: 

- assess unobservable (latent) constructs
- determine complex relationships between dependent and independent variables

## Structure of a dataset 
### Confirmatory factor analysis
Is a multivariate statistical technique used to verify how well measured variables represent latent constructs. Usage: 

- analyse wether data fit to a hypothesized measurement model (Model for a latent variable)
- test the model structure
- test quality of model 

## Relationship
We want to overcome the restrictions which come with using linear regression. 

__Additvity and linearity:__ If we want to use a different scale for our variables we can use different estimators: 

1. Linear outcomes:  OLS
2. Binary outcomes:  Logit/Probit
3. Ordinal outcomes: Ordered Probit
4. Categorial outcomes:  Multinomial Regression
5. Count outcomes:   Poisson / negative binominal regression (zero inflation)
6. Truncated outcomes in linear models: TOBIT regression

__Independent errors:__ Residual terms should be independet. If the assumption is violated the model suffers from endogenetiy. Endogeneity occurs when an explanatory variable is correlated with the error term. Can occur due to:

- measurement error (imperfect measure of the results)
- autocorrelated error terms (Panel data) -> Fixed effects model (time-variant vars); Random effects model (time-invariant vars)
- simultaneous causality (two independent variables affecting another)
- omitted variables (latent variable which influences the errors)

The problem of endogeneity can be solved by adding instrumental variables. Instrumental variables are used to estimate casual relationships when controlled experiments are not feasible.
