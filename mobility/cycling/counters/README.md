# counters

Data from automated counters.

All files are in CSV format and have the fields:

* `name`: name of the counter
* `date`: `YYYY-MM-DD` when count was observed
* `hour`: hour of `date` when count was observed (for example, `1` covers the 1:00 AM hour)
* `count`: trips counted during the hour

Counters (especially ones that use tubes) have [bad days](https://twitter.com/bikehfxstats/status/880388148106330112). For example, `agricola-sb.csv` has questionable data from times it was broken, especially in 2017.
