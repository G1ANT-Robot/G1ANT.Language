# datatable

The datetable structure stores information about the excel sheets, sql queries, etc.:

| Field                         | Type    | Description           |
| ----------------------------- | ------- | --------------------- |
| 'colcount'                    | integer | number of columns     |
| `count`                       | integer | number of rows        |
| `columns`                     | list    | list of column names  |
| row-index                     | list    | row values            |
| column-name                   | list    | column values         |
| column-name,row-index         |         | cell value            |
| column-index,row-index        | integer | Year value            |
| filter ...                    | string  | any filter expression |

See also: [filter expression has been described in the Microsoft manual](https://docs.microsoft.com/en-us/dotnet/api/system.data.datacolumn.expression?view=netcore-3.1#System_Data_DataColumn_Expression)