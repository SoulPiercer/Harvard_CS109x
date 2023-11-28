# Linear Regression / Intorduction to Regression
## K Nearest Neighbors

Data Matrixes (Capital Letters) using Pandas and SKlearn


Predictor Varialbe, X.shape ->  (n,p)
Response Variable, Y.shape -> (n,) OR (n,1)

df[['x']] vs df['v']
df[['x']] returns a pd.DataFrame object whereas
df['x'] returns a pd.Series object

Assume response Variable Y, relates to the predictors, X, through some unknown function, f(X), which expresses an underlying rule for relating Y to X and a random amount ℰ (unrelated to X) that describes the difference Y from the rule F(X)
Y = f(x) + ℰ
⊽ᵢ = F(xᵢ₁, ..., Xᵢₐ)

inference problems, try to obtain F, our estimate of f vs. prediction problems, 
