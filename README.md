# webdatatype
Web Data Types (idea stolen to Alex Milowski)
## why?
The idea is to take some approach about having some datatype definition about languages of the web. It comes from a discussion with Alex Milowski at XML Prague 2016

## already existing stuffs
There is multiple sources here :
* JSON datatype (boolean, number, null, string) http://json.org/
* BSON datatypes https://docs.mongodb.org/manual/reference/bson-types/
* HTML5 datatype https://www.w3.org/TR/html-markup/datatypes.html
* XML Schema Datatypes https://www.w3.org/TR/xmlschema-2/ and https://www.w3.org/TR/xmlschema11-2/
* etc.

## first draft
### EMPTY pointer : null (JSON), xsd:nil
### Floating point number : number (JSON), xsd:double
### Boolean representation : boolean (JSON), xsd:boolean
### DateTime : BSON
