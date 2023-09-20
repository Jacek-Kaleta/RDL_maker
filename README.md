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

The file should have the extension ".csv".
The definition of the columns is written in the following lines of the file.

The line consists of fields:
- column header,
- data field name,
- field width in cm,
- description of how to justify text in the result column (allowed values are: Left, Center, Right)
- description of formatting method (e.g. dd.mm.yyyy, #.00)

The fields in a line are linked together using a tab character.

See a sample file: [RDL_Sample](https://github.com/Jacek-Kaleta/RDL_maker/blob/main/RDL_Sample.csv)
