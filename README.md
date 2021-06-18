# COVID-19 Age-Based Stats
Processed version of the [https://osf.io/7tnfh/](https://osf.io/7tnfh/) dataset which shows the cumulative number of COVID-19 cases and deaths by age as of the most recent dates in the OSF dataset.

# Output Data
The processed data is stored on this repo:

- [COVID-19 Cases and Deaths by Age and Country](Data/COVID-cases-and-deaths-by-age-and-country.csv) (CSV)
- [COVID-19 Cases and Deaths by Age and Country](Data/COVID-cases-and-deaths-by-age-and-country.md) (Markdown)
- [COVID-19 Cases and Deaths by Age and Region](Data/COVID-cases-and-deaths-by-age-and-region.csv) (CSV)
- [COVID-19 Cases and Deaths by Age and Region](Data/COVID-cases-and-deaths-by-age-and-region.md) (Markdown)

# Running the Data Processor
To compile and run the data processing program and regenerate the output data:

1. Install [Rogue](https://github.com/AbePralle/Rogue).
2. Download and unzip the `Output_5.csv` dataset from [https://osf.io/7tnfh/](https://osf.io/7tnfh/).
3. Run `rogo path/to/Output_5.csv`.

# Sample Output
Country|Region|Date|Age|Cases|Deaths
-------|------|----|---|-----|------
USA|All|2021.06.05|0|559241|115
||||5|721345|44
||||10|1064843|63
||||15|1710880|228
||||20|2562311|711
||||25|3030192|1594
||||30|2482282|2568
||||35|2169932|4176
||||40|2029837|6406
||||45|2218440|11206
||||50|2147740|18259
||||55|2034211|30198
||||60|1661719|43791
||||65|1260333|58206
||||70|949950|72361
||||75|675685|79822
||||80|487348|81423
||||85|293898|64533
||||90|346305|94429
||||95|49967|16355
||||100|393|160

