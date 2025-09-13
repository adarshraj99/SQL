* Unicode character data : Allow wide range of characters from different languages. eg: 你好世界
* Single ASCII characters generally requires 1 byte to store. ASCII are A-Z ,a-z, 1-9, special chracters like : !@$#,?*^ , space,tab,enter  etc
* Single Unicode character takes 2 Bytes or more. 
* Use DATALENGTH() or LENGTH() kmow the length of the data.


## Data Types: Majorly: Numeric ,String, Date.
## 1. Numeric : 10 numeric data types

![image](https://github.com/user-attachments/assets/676e00ad-54ff-4bd0-9bf4-b423deb779b8)

Majorly:
* Int : Integer : Stores whole Numbers typically from -2,147,483,648 to 2,147,483,647. Occupies 4 bytes for an int. So, use when number grater than 32,767 need to store.
* Float : Approximate fractional numbers. Store upto 7digits. 4 Bytes memory. If stored big numbers ,only approx values gets stored and can lead to calculation errors later.
* Double : Approximate fractional numbers. Stores upto 15digits. 8 Bytes memory.

Others:
* Decimal : Will be more near to exact numbers after decimal. Have no number rounding.  
* SmallInt : All Int types have different storage capacities. It occupies full 2Bytes from memory. So, if number is between -32,767 to 32,767 should use SmallInt. 
* BigInt : Used for very large numbers, ranging from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807. Stores 8 Bytes. 
* TinyInt : Stores 1byte of value. Used to store 0 to 255. 
* Money : It is for storing money values in data types. It is accurate to 10,000th of monetery units that they represent.  
* SmallMoney: It is accurate to 100th of the monetery unit that they represent. 

## 2. String :
Majorly: 
* Char :Fixed length, Single Byte character data: Fills 10 Bytes from storage.
*  If input is 6 Bytes, char will store it in 10 storage. So, it will waste extra more memory spaces. eg: "Hello" is 3character so, will take round 5Bytes.
* Varchar : It will store the data according to the data memory. So,it will not waste extra memory.
  
Others:
* Text : Large text data
* NChar :Fixed length, Unicode character data: For storing the diffrent human languages as string values. It is of fixed length character.
* NVarChar :Variable length: For storing the diffrent human languages (Unicode characters) as string values. It is of variable length character. "Hello" in Nvarchar will take 10 Bytes.

## 3. Date : 
Major:
* Date :
* Time :
* DateTime:

others:
* SmallDataTime:
* DateTime2:
* DateTimeOffSet:
* Timestamp:

## 4. Boolean : 
* True or False

## 5. BLOB (Binary Large Object): 
* used for images, files, etc.

## 4. Miscellaneous : 
* BIT:
* SQL_Varient:
* Binary Data Types:
* Table:
* Large Object Data Types:
* XML :
* JSON :
* UniqueIdentifier:
  
