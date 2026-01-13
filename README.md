# TADA - Target Aggregate Data Adjustment Method for Transportability Analysis Utilizing Summary-Level Data from the Target Population
R codes to implement the simulation study and real case study analysis in "Target Aggregate Data Adjustment Method for Transportability Analysis Utilizing Summary-Level Data from the Target Population".

Here is a brief introduction to each R file. Comprehensive comments provide detailed instructions in each file. Setting the relative working path for storing results and loading data is necessary.

- `assistFunctions.R`: data generation functions for simulation in various scenarios.
- `TADA-simulation.R`: to conduct the main simulation across scenarios and obtain bias and coverage results.
- `TADA-SA-abnormalValue.R`: to perform sensitivity analysis under abnormal value settings in the target population.
- `TADA-SA-sampleSize.R`: to perform sensitivity analysis under different source sample sizes.
- `TADA-SA-truncProp.R`: to perform sensitivity analysis under various final weight truncation thresholds.
- `TADA-RCS-dataWrangling.R`: to preprocess raw data files and generate cleaned inputs for real-case study.
- `TADA-realCaseStudy.R`: to conduct the real-case study.

The simulation codes are for parallel computing to increase effectiveness. We suggest accessing the source IPD in the *Project Data Sphere* platform on your own at the time of reproduction, based on the NCT number provided in the paper and using the appropriate data wrangling code to get clean inputs. For detailed information on the use of the `transportTADA` function, please refer to the package documentation of `transportHealth`.

If you use this repository or the associated method in your work, please cite the following article:

Yan, Y., Vuong, Q., Metcalfe, R. K., Guan, T., Shi, H., & Park, J. J. (2025). *Target Aggregate Data Adjustment Method for Transportability Analysis Utilizing Summary‐Level Data From the Target Population*. Pharmaceutical Statistics, 24(5), e70029.

[![DOI](https://img.shields.io/badge/DOI-10.1002/pst.70029-blue)](https://doi.org/10.1002/pst.70029)

We will consistently provide the necessary maintenance for these major R files.
