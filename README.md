# Statistical Analysis of F1 2019-2024 Seasons

## Project Overview
This project is conducted as part of the *Probability Theory and Statistics* course at AGH University of Kraków. It aims to analyze Formula 1 seasons from 2019 to 2024 using statistical methods. The project is implemented in a Jupyter Notebook using Python and employs various libraries for data collection, processing, visualization, and statistical analysis. 

**Note:** The project and its documentation are written in Polish.

## Technologies & Libraries Used
The project is written in Python and utilizes the following libraries:

```python
import sqlite3
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import fastf1 as ff1
import fastf1.plotting
import statsmodels
from scipy import stats
import requests
```

- **fastf1**: For fetching and analyzing Formula 1 timing data.
- **requests**: To collect data from [Ergast API](https://ergast.com/api).
- **sqlite3**: To save collected data.
- **pandas, numpy**: For data manipulation and statistical computation.
- **matplotlib, seaborn**: For visualization.
- **statsmodels, scipy**: For statistical tests and regression analysis.

## Chapters
The project is structured into the following sections:
1. **Introduction** – Overview of the project and objectives.
2. **Data Gathering and Cleaning** – Collecting data using Ergast API and processing it.
3. **Visual Analysis** – Creating graphical representations of key insights.
4. **Exploratory Analysis** – Examining statistical properties and distributions.
5. **Statistical Tests and Regression Analysis** – Applying hypothesis tests and regression models.
6. **Conclusion** – Summarizing findings and potential applications.

## Data Exports
The project provides two export files:
- [**With code blocks**](/Export/Statystyczna%20analiza%20sezonów%202019-2024%20Formuły%201%20(codeblocks).pdf): Includes all the implemented Python code.
- [**Without code blocks**](/Export/Statystyczna%20analiza%20sezonów%202019-2024%20Formuły%201.pdf): A clean export with analysis and results, excluding code.

## Data Source
The project uses the [Ergast API](https://ergast.com/mrd/) and [fastf1](https://docs.fastf1.dev/) python library to retrieve F1 race data for statistical analysis.

## License
This project is for academic purposes and follows an open-source license. Contributions and feedback are welcome!

