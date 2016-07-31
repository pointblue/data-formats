# Defining Input Formats

### Input Formats
there are three kinds of input formats:
1. multi-tab excel
1. multi-csv tarfile
1. csv file

### Field Attributes
* **type**: the data type of the field (see "Data Types" for allowed values)
* **format**: parser instructions and validation constraints on the field value (see "Formats" for allowed values)
* **units**: units of measure, applied to numerical types (see "Units" for allowed values)
* **primaryKey**
* **instructions**
* **dictionary**
* **list**
* **range**
* **regex**
* **value**

### Data Types
* character:
    * **string**: character string; format expressed as PHP regex
* numeric:
    * **integer**: 32-bit integer
    * **decimal**:
    * **percent**:
    * **scientific**:
* time-based:
    * **date**:
    * **time**:
    * **datetime**:
    * **duration**:

### Formats
* **dictionary**: mostly used with string and integer types.
* **list**: used with all data types.
* **range**: used with numeric and time-based data types.
* **regex**: mostly used with character data types.  for numeric types, use a list or range if possible.

### Units
* distance
    * **meters**
    * **centimeters**
    * **inches**
    * **feet**
    * **yards**
* angle
    * **angular degrees**
* temperature
    * **degrees Fahrenheit**




### Magic Columns
* RowNum: ordinal number of the data row in the spreadsheet, starting at 1 at the first data row



