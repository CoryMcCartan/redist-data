# **redist-data**

Larger sample data for the [`redist` package](http://alarm-redist.github.io/redist/).

## Contents

### King County Council Districts
File: [`data/king_county.rds`](https://github.com/alarm-redist/redist-data/raw/main/data/king_county.rds)

Contains precincts, vote data, and county council districts for King County,
Washington.

Processed from Harvard Election Data Archive data.
  
Stephen Ansolabehere; Jonathan Rodden, 2011, "Washington Data Files", <https://doi.org/10.7910/DVN/DHWJVE>, Harvard Dataverse, V1
  
### North Carolina Congressional Districts
File: [`data/nc.rds`](https://github.com/alarm-redist/redist-data/raw/main/data/nc.rds)

Contains precincts, vote data, and 2013 and 2017 congressional districts for
North Carolina.

## Usage
R code to load a file:
```r
data_url = "<URL HERE>"
download.file(data_url, data_path <- tempfile())
shp = readRDS(data_path)
```

