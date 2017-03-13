
# Fidelity Relative Performance Report

## Product

This report provides charts summarizing relative performance within
and among various asset groups.  It uses ETF proxies and daily returns
for the following groups: 
- Domestic equities 
- Emerging marketequities 
- Global macro


## Tooling

This is a Knitr document that requires both an R environment and a
LaTeX installation. To run the report, first clone the repo to a
platform having the required tools.  Run the document through the R
Sweave processor to yield TeX code, then run the TeX code through the
LaTeX processor to yield DVI, PDF, or HTML code.  As written the
product uses the LaTeX Beamer package to produce charts which we
produce as a PDF product.

## Data Sources

The analysis requires data archives from third-party sources.
Presently the document retrieves time series data from Yahoo Finance
and Quandl.




