# GENEActiv Activity Monitor

This instrument was created for use with raw binary GENEActiv data files. These .bin files are generally quite large (>1GB) and may take significant time to upload and process.

| Filename | Description |
| --- | --- |
| instrument-definition | A simple instrument including the raw datafile and no settings |
| filetype-definition-raw | The raw binary datafile (.bin extension) |
| filetype-definition-report | A PDF report outputted by the included job. Visual summaries include energy expenditure, activity intensities, and daily sleep summaries. |
| job-definition | A processing job that uses the "GENEActivR" package to read in the raw data. Data is then summarized and visualized with a number of custom functions. |