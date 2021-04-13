# **redist-data**

Larger sample data for the [`redist` package](http://alarm-redist.github.io/redist/).

## Contents
* [`data/king_county.rds`](https://github.com/alarm-redist/redist-data/raw/main/data/king_county.rds): 
  precincts, vote data, and county council districts for King County, Washington.
* [`data/nc.rds`](https://github.com/alarm-redist/redist-data/raw/main/data/nc.rds): precincts, vote 
  data, and 2013 and 2017 congressional districts for North Carolina.

## Usage
R code to load a file
```r
data_url = "<URL HERE>"
download.file(data_url, data_path <- tempfile())
shp = readRDS(data_path)
```

