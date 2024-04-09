# Characterization & Analysis of Messy Crab Measurement Data.

## Background:
Every year, fishery observers are hired to monitor snow crab fishing operations in Atlantic Canada. When crab are brought on board the fishing vessel, these observers measure the characteristics 
of the crab that are caught. The primary goal is to monitor the sizes of crab in catches, as well as monitor the quantity of soft-shelled crab. These crab are have recently shed their shells and 
not sold by fishermen because of their low meat yield. High levels of soft-shelled crab can lead to local closures of the fishery. The data provided by fishery observers varies widely in quality 
and presents a wide range of issues, such as : **improper measurement**, **poor data recording**, **data rounding**, and **data fabrication**.

## Data description:
Individual crab measurements and qualitive observations. This is a **very large data set**. There are **millions** of individual crab observations, made by hundreds of different fishery observers, over a 30-40 year span of time.

## Strategy :
- Review likely mechanisms that generate the observed patterns.
- Build generating models which can simulate data for testing.
- Build different multinomial discrete probability distributions for analyzing different issues that have been identified.
- Combine different data error mechanisms using probability mixture models.
- Fit models to simulated data and observed data.

## Benefits:
- Characterizing and quantify different sources of biases and behaviors for individual observers. This can be used to deliver training which targets specific issues.
-	Account for these issues in analyses : produce bias-corrected results.
