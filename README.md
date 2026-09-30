# Geneva Stroke Study

Analysis code for the Geneva Stroke Study (first-ever strokes in the canton of Geneva, 2018-2019).

## Structure

- `incidence/` original paper: ICD-10 vs ICD-11 comparison, 90-day survival, mRS distribution
- `followup/` 5-year follow-up: survival by stroke type, SMR by pandemic period, survival by period

## Requirements

Python 3 with pandas, matplotlib, seaborn, lifelines, statsmodels, patsy, pymer4 (R backend).

## Reference

Dirren E, Escribano Paredes JB, Klug J, et al. Stroke Incidence, Case Fatality, and Mortality Using the WHO International Classification of Diseases 11: The Geneva Stroke Study. *Neurology*. 2025;104(5):e213353. [doi:10.1212/WNL.0000000000213353](https://doi.org/10.1212/WNL.0000000000213353)
