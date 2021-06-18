# COVID-19 Age-Based Stats
Processed version of the [https://osf.io/7tnfh/](https://osf.io/7tnfh/) dataset which shows the cumulative number of COVID-19 cases and deaths by age as of the most recent dates in the OSF dataset.

# Output Data
The processed data is stored on this repo:

- [COVID-19 Cases and Deaths by Age](Data/COVID-cases-and-deaths-by-age.csv) (CSV)
- [COVID-19 Cases and Deaths by Age](Data/COVID-cases-and-deaths-by-age.md) (Markdown)
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
World|All|2020.06.21|0|1572881|18027
||||5|2173475|2596
||||10|3213838|2233
||||15|4887325|3609
||||20|7308793|7415
||||25|8840219|13852
||||30|8317237|25522
||||35|7656992|43631
||||40|7210590|65529
||||45|7246402|95749
||||50|6844390|135438
||||55|6119221|191269
||||60|4800887|249711
||||65|3669025|293539
||||70|2802263|327299
||||75|2039962|351227
||||80|1686868|372933
||||85|1124796|307005
||||90|831692|260273
||||95|222274|95697
||||100|26054|14798
