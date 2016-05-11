# PiLR EMA App
The PiLR EMA App allows you to setup surveys and messages to deliver to participants through their mobile phone (Android or iOS).  It also allows you to set a delivery schedule and triggering events to initiate them.

| Filename | Description |
| --- | --- |
| base-instrument.json | Adds the instrument to the project, without any sample EMA Configurations (i.e. no surveys, triggers, or tab content). |
| sample-config-bundle.json | Adds the instrument to the project, and also a sample EMA Configuration with a single survey, trigger, and some sample tab content. |


##Datasets
###Data Columns Value range:

| Dataset | Column | Value Range |
| --- | --- | --- |
| Survey Data | Event Type | survey_submitted, survey_header, response, survey_started |
| App Log | Tag | EMPTY_CARDWALL, UPDATE, SAVE, REMOVE, SCAN, OPENED_APP, LOGIN, SYNC |
| Compliance Events | Type |  TIMER_NOTIFICATION, SELF_REPORT |
| Personal Venues | Venue Type |  general |
