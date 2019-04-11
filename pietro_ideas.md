# Python and R results differ

For the same models, in statmodels SARIMAX or R astsa sarima, results are wildly
different. Why?

# R

R provides sane residuals acf, pacf, but why? Residuals are returned
uncorrelated. Could we do better with exog vars? denser series?

Make it _stationary_ first by regression on weather? could be tried

regression on weather first or during regression on season? Could be different

check influence of smaller holidays compared to bigger (1st may vs easter)

school holidays?

# TODO

- new repo
