# F1-Data-Analysis

This is a project which focuses on simple analyses of F1 data. Specifically, the following questions are discussed.
- Which year had the fastest lap time for each circuit?
- Which track has the biggest improvement in lap time?
- How do lap time vary throughout the years?

## Libraries used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Files

There are 5 files in the repo:

- This README.md file which outlines the project motivations, files used and a summary of the results
- drivers.csv file which contains data on F1 drivers including their name, dob and nationality
- lapTimes.csv file which contains data about lap times for a specific driver and race as well as their positions and lap number
- races.csv file which contains data about the races including the year, the race date and the race name
- Project 1 - F1 Analysis.ipynb is the main file that needs to be run for the analysis. The file loads in the 3 datasets, merges them together and uses statistics and plots to the answer the questions

## Results

Below is a summary of the results:

- The year 1996 had the fastest lap times at 16 circuits, significantly outperforming the rest of the years
- The Canadian Grand Prix saw the largest change in laptimes, increasing by 7433925 milliseconds
- In general laptimes stayed somewhat consistent throughout the years, however, there were outliers in some of the races

## Acknowledgements

Kaggle provided the datasets and can be found here: https://www.kaggle.com/code/jonathanbouchet/f1-data-analysis/data
