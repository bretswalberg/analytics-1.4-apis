# SavePaidSearchDetection

Saves the paid search settings for the requested report suites.

## ReportSuite.SavePaidSearchDetection parameters

|Name|Type|Description|
|----|----|-----------|
|**rsid_list** |`string[]` |A list of report suite IDs.|
|**search_engine** |[search_engine_enum](../../data_types/r_search_engine_enum.md#) | The name of the search engine. |
|**operator** |[paid_search_operator_enum](../../data_types/r_paid_search_operator_enum.md#) | Specifies the type of paid search rule. One of the following values: `contains` `not_contains` |
|**query_string** |`string` |The string value to use when matching a search engine referring URL.|

## ReportSuite.SavePaidSearchDetection response

|Type|Description|
|----|-----------|
|`boolean` |Returns `true` if the operation is successful.|

**Parent topic:** [Report Suite](../../methods/report_suite/r_methods_reportsuite.md)
