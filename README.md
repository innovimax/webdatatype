# Web Datatypes
Web Data Types (idea stolen to Alex Milowski)
## Why?
The idea is to take some approach about having some datatype definition about languages of the web. It comes from a discussion with Alex Milowski at XML Prague 2016

## Already existing stuffs
There is multiple sources here :
* *SON
** JSON datatype (boolean, number, null, string) http://json.org/
** BSON datatypes https://docs.mongodb.org/manual/reference/bson-types/
* HTML5 datatype https://www.w3.org/TR/html-markup/datatypes.html
* XML Schema Datatypes https://www.w3.org/TR/xmlschema-2/ and https://www.w3.org/TR/xmlschema11-2/
* SQL
** Transact-SQL https://msdn.microsoft.com/library/ms187752%28v=sql.120%29.aspx
* etc.

## Approach


## First draft
### EMPTY pointer : null (JSON), xsd:nil
### Floating point number : number (JSON), xsd:double
### Boolean representation : boolean (JSON), xsd:boolean
### DateTime : BSON
### ...
### (top of the hierarchy) String : any Unicode string
