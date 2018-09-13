# Station capacity data

All timestamps are in UTC, and the date intervals are also in UTC, e.g. the data
in "2018-09-12" is in UTC.

Three hours of data from one early day is missing, because the disk on my server
filled up and I didn't recognize it.

GoBike has changed a station's ID at least once. Tools exist in
github.com/kevinburke/gobike for retrieving and normalizing the station ID list;
see gobike.go and the `client` package for examples of each.
