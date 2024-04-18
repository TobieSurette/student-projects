# Characterization & Analysis of Messy Crab Measurement Data.

## Background
Every year, fishery observers are hired to monitor snow crab fishing operations in Atlantic Canada. When crab are brought on board the fishing vessel, these observers measure the characteristics 
of the crab that are caught. The primary goal is to monitor the sizes of crab in catches, as well as monitor the quantity of soft-shelled crab. These crab are have recently shed their shells and 
not sold by fishermen because of their low meat yield. High levels of soft-shelled crab can lead to local closures of the fishery. The data provided by fishery observers varies widely in quality 
and presents a wide range of issues, such as : **improper measurement**, **poor data recording**, **data rounding**, and **data fabrication**.

## Data description
Individual crab measurements and qualitive observations. This is a **very large data set**. There are **millions** of individual crab observations, made by hundreds of different fishery observers, over a 30-40 year span of time.

## Observation bias mechanisms
- **Equipment failures** : Measurement equipement can become defective or uncalibrated, creating observable biases in the data.
- **Mismeasurement** : Equipement can be misread or measurement equipement can be misapplied, leading to biases and/or increased variance in the observations. Examples include impropoer application of the measurement caliper to measure the width of the crab carapace or the height of the crab claw.
- **Data legibility** : Data are recorded on paper sheets in the field. Data that are hard to read lead to increased observation errors and obvious outliers in the data.
- **Data frabrication** : In some cases, data are fabricated by field observers in order to avoid the effort of measuring all the required snow crab traits.
- **Rounding** : Recorded data observations are very often rounded to particular values, depending on the observer. Examples can be tendencies to round data to even or odd-values, to multiples of 5 or 10, or even cases where the rounding in concentrated to values between the major and minor intervals on the measurment devices, i.e. numbers which tend to avoid multiples or 5 or 10. Behavioural mechanisms included lack of attention to detail, or difficulty seeing or reading the field measurement equipment. 
- **Truncation** : there are threshold values in the measurement data, such as the minimum legal size for the snow crab fishery (carapace width of 95 millimeters), and the soft/hard-shelled crab threshold of 68 on th durometer (device for measuring carapce hardness). Sometimes measured values below these thresholds are recorded as other values, possibly as a way to avoid triggering fishery certain conservation measures.

## Strategy 
- Review likely mechanisms that generate the observed patterns.
- Build generating models which can simulate data for testing.
- Build different multinomial discrete probability distributions for analyzing different issues that have been identified.
- Combine different data error mechanisms using probability mixture models.
- Fit models to simulated data and observed data.

## Benefits
- Characterizing and quantify different sources of biases and behaviors for individual observers. This can be used to deliver training which targets specific issues.
-	Account for these issues in analyses : produce bias-corrected results.
