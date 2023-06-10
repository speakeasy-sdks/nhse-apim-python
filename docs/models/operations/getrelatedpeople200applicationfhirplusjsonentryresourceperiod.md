# GetRelatedPeople200ApplicationFhirPlusJSONEntryResourcePeriod

Business effective period when name was, is, or will be in use.



## Fields

| Field                                                                                               | Type                                                                                                | Required                                                                                            | Description                                                                                         | Example                                                                                             |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| `end`                                                                                               | [datetime](https://docs.python.org/3/library/datetime.html#datetime-objects)                        | :heavy_minus_sign:                                                                                  | End date of time period, if known and if not ongoing, in format `yyyy-mm-dd`. Can be a future date. | 2021-12-31                                                                                          |
| `start`                                                                                             | [datetime](https://docs.python.org/3/library/datetime.html#datetime-objects)                        | :heavy_check_mark:                                                                                  | Start date of time period, if known, in format `yyyy-mm-dd`. Can be a future date.                  | 2020-01-01                                                                                          |