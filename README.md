# DAXDUTIL
Microsoft Dynamics AX Utilities for developers

This is a list with some utilities and tools that might be useful at DAX development process. Each file represents a single project and were written in a clean AX environment.
 
You are more than welcome to contribute with your awsome utility/tool.

##Tools
### DAX 2012 tools
* [Tables](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Tables)
  * [Find method](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Tables/DAXD_TableFindMethod.xpo) - Creates the method finds based on table's key/index properties. In order of relevance: *ReplacementKey* and *PrimaryIndex*. To use it, create a new table method and *right click > Scripts > template > table > find*
  * [Table 2 Form](https://github.com/anderson-joyle/DAXDUTIL/blob/dev/Tables/DAXD_Table2Form.xpo) - Creates a form based on a table. Its considered the table group property to define witch form template will be used. To use it, follow the [manual](http://andersonjoyle.com/2016/06/08/daxdutil-table-2-form-manual).

* [Queries](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Queries)
  * [Build query](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Queries/DAXDUtil_QueryBuildQuery.xpo) - Creates x++ query code. By default, declares two query datasources using {TABLE_NAME#} notation, wich you can replace with any table name. Also, two query range are declared with {FIELD_NAME#} notation. Note that by definition, the {FIELD_NAME1} refers to {TABLE_NAME1} and {FIELD_NAME2} refers to {TABLE_NAME3}.To use it, *right click > Scripts > template > database > buildQuery* or simply type *buildQuery* on code editor.

* [Projects](https://github.com/anderson-joyle/DAXDUTIL/tree/master/Projects)
  * [Multi project export](https://github.com/anderson-joyle/DAXDUTIL/blob/master/Projects/DAXD_MultiProjectExport.xpo) - Enable the developer to export multiple projects at once, filtering by prefix, suffix and/or layer. To use it, follow the [manual](http://andersonjoyle.com/2016/08/02/daxdutil-multiple-project-export-manual).

##Exams
Hints for all Dynamics AX developers who are going to take certification exams. If this file was usefull to you, please don't exitate to contribute with your own hints.

Kindly find below the current exams file structure:
* Microsoft Dynamics 365 for Operations
 * [MB6-890 - Microsoft Dynamics AX Development Introduction] (https://github.com/anderson-joyle/DAXDUTIL/blob/master/Exams/AX7/MB6_890-Development_Introduction.md)
 * [MB6-892 - Microsoft Dynamics AX Distribution and Trade] (https://github.com/anderson-joyle/DAXDUTIL/blob/master/Exams/AX7/MB6_892-Distribution_and_Trade.md)
 * [MB6-893 - Microsoft Dynamics AX Financials] (https://github.com/anderson-joyle/DAXDUTIL/blob/master/Exams/AX7/MB6_893-Financials.md)
