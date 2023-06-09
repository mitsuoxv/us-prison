# US prison data
Mitsuo Shiota
2023-06-07

Updated: 2023-06-10

## Data source

I have downloaded zip files on annual prison data from [Bureau of
Justice
Statistics](https://bjs.ojp.gov/library/publications/list?series_filter=Prisoners),
extracted, and saved csv files on imprison rates and sentenced prisoners
by state in `data` directory.

I have also downloaded some Excel, csv, text files on state resident
population from [Census
Bureau](https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html),
and saved them in `data` directory.

## 7 csv files created

From files in `data` directory, I have made 6 csv files:

- imprison_rate.csv: Number of sentenced prisoners per 100,000 residents
  by state and year from 2007 to 2021,

- prisoners.csv: Number of prisoners by state and year from 1997 to
  2021,

- sentenced_prisoners.csv: Number of (more than one year) sentenced
  prisoners by state and year from 1997 to 2021,

- admissions.csv: Number of admitted sentenced prisoners by state and
  year from 2006 to 2021,

- releases.csv: Number of released sentenced prisoners by state and year
  from 2006 to 2021,

- custody.csv: Number of inmates held in custody of facilities operated
  by the state from 2007 to 2021 (note: lacks 2012 data, and includes
  some NAs), and

- population.csv: Resident population by state and year from 1997 to
  2021.

## Plot

<img src="README_files/figure-commonmark/plot_rates-1.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_rates-2.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_numbers-1.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_numbers-2.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_numbers-3.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_admissions-1.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_admissions-2.png"
style="width:70.0%" />

<img src="README_files/figure-commonmark/plot_admissions-3.png"
style="width:70.0%" />
