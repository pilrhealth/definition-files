# Actigraph Minute-by-Minute Counts Data

This instrument was created for use with Actigraph data that has been processed into 60 second epochs using the ActiLife PC Software.

| Filename | Description |
| --- | --- |
| Filetype-definition | A CSV of the Actigraph counts data after being processed into 60 second epochs |
| dataset-schema | This dataset is daily summaries of energy expenditure, intensity thresholds, nonwear, etc. This is produced by running the R processing unit included in this folder. |
| job-definition | This defines an R Processing Unit which takes the CSV (included filetype) and processes it with the R package 'accelerometry'. |
| dashboard-intensities-definition | This defines a dashboard which displays total time spent at each intensity threshhold, grouped by day. |
| dashboard-steps-definition | This defines a dashboard which simply displays total number of steps taken per day. |
| sample-data | A sample CSV of Actigraph data that has already been processed into 60 second epochs. |