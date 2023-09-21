# RDL PROJECT FILE MAKER

**How the application works**

The application processes the template file. The application duplicates the appropriate blocks of XML code, changes the content of elements in the block related to the structure of the RDL file.

**Run application**

From https://rdlmaker.pages.dev/RDL_maker

**How create project from template file**

- click the button **Load RDL TEMPLATE / FIELDS** and load template from the ".rdl" file
- click the button **Load RDL TEMPLATE / FIELDS** and load column list from ".csv" file 
- save project by clicking **Create RDL**

**What does a file containing a list of report columns look like?**

The file should have the ".csv" or ".txt" extension.

The definition of the columns is written in the following lines of the file.

The line consists of fields:
- column header,
- data field name,
- field width in cm,
- description of how to justify text in the result column (allowed values are: Left, Center, Right)
- description of formatting method (e.g. dd.mm.yyyy, #.00)

The fields in a line are linked together using a tab character.

See [RDL_Sample.csv](https://github.com/Jacek-Kaleta/RDL_maker/blob/main/RDL_Sample.csv) and [RDL_template.rdl](https://github.com/Jacek-Kaleta/RDL_maker/blob/main/RDL_Template.rdl) files.

**Description of the structure of the RDL file**

See the description on the website: [MS-RDL Report Definition Language File Format](https://learn.microsoft.com/en-us/openspecs/sql_server_protocols/ms-rdl/53287204-7cd0-4bc9-a5cd-d42a5925dca1)

**How to download Microsoft® Report Builder**

See [Microsoft® Report Builder](https://www.microsoft.com/en-us/download/details.aspx?id=53613)  and [RDL XML Schemas](https://learn.microsoft.com/en-us/openspecs/sql_server_protocols/ms-rdl/4299384a-e826-4f69-bb06-f56d37155197)
