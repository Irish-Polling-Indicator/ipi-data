# Irish Polling Indicator Datasets: Development Version


## Introduction

The Irish Polling Indicator (https://pollingindicator.com) provides daily aggregated estimates of support for Irish political parties. The project started in 2014 and is maintained by Tom Louwerse and Stefan Müller. 

The [codebook](codebook_ipi-data.pdf) describes all datasets and variables in detail. 

We provide two datasets:

- `data_polls` contains the raw polling results, information on the field period (the days when the survey was conducted), the publication date, and the polling company.
- `data_pollingindicator` provides the daily aggregated estimates for parties, along with 95 per cent credible intervals.


## Dataset Versions 

### Development Version

Both of the datasets have been published in two data repositories. Everyone is welcome and free to use the estimates and polling results as long as the corresponding datasets are cited.

This GitHub repository [IrishPollingIndicator/ipi-data](https://github.com/IrishPollingIndicator/ipi-data) contains the "development version" of the datasets. These datasets are updated after the release of new polls and thus change over time. Moreover, the estimates for previous dates in the current term may change after the releases of new polls [for details see see @louwerse16].

If you use data from the development version, please cite: 

- Tom Louwerse and Stefan Müller. 2022. _Irish Polling Indicator Datatsets: Development Version._  URL: https://github.com/Irish-Polling-Indicator/ipi-data.

### Stable Version

Users who would like to access the most recent data should download and analyse the development version. 
Users who do not need access to the most recent files but only need data until the end of a calendar year should use and cite the stable version.  The "stable version" is stored at Harvard's Dataverse. New releases are published after an election cycle. The stable version has a unique identifier (DOI: [10.7910/DVN/BY5GXC](https://doi.org/10.7910/DVN/BY5GXC)), and the daily estimates will not change since all polls in an election cycle are considered.

- Tom Louwerse and Stefan Müller. 2022. _Irish Polling Indicator Datasets: Stable Version_. Harvard Dataverse, V1. DOI: [10.7910/DVN/BY5GXC](https://doi.org/10.7910/DVN/BY5GXC)

## File Formats

We provide `data_pollingindicator` and `data_polls` in four file formats. 

- `csv`: The [comma-separated values](https://en.wikipedia.org/wiki/Comma-separated_values) file ensures inter-operability as it can be opened in R, Python, Stata, SPSS, and Excel.
- `xlsx`: The [Excel spreadsheets](https://en.wikipedia.org/wiki/Microsoft_Excel) allow for an even more straightforward import of the data into Microsoft Excel.
- `dta`: This file can be used to import the datasets  with correct variable encodings into [Stata](https://stata.com).
- `rds`: The RDS file is optimised for the [R](https://r-project.org) statistical programming language and stores the variables in the correct data type.
