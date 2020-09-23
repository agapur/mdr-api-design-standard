# mdr-api-design-standard
MDR API Repository

### Table of Contents <a name="TOC"></a>
- [Rest API Permen Naming Conventions](#1)

## Rest API Permen Naming Conventions <a name="1"></a>

1. URIs follow RFC 3986 Spec.
2. URI component : https://36.89.146.92:8040/namespace/project-name/v1/search
3. URI maximum Length <=2000. Allowable chars : commas, underscore, question mark, hyphens, plus, slash 
4. URI Naming Conventions
	- the URI MUST be specified in all lower case
	- only hyphens '-' can be used to separate words or path parameters for readability (no spaces or underscores)
	- only underscores '_' can be used to separate words in query parameter names but not as part of the base URI
5 Resource Names / Collections
	* Nouns MUST be used - not verbs for names.
	* Resource names MUST be plural
	+ Resource names MUST be lower-case and use only alphabetic characters and hyphens
	+ The hyphen character, ( - ), MUST be used as a word separator in URI path parameters
6. Query
	- Literals/expressions in query strings SHOULD be separated using underscore ( _ ).
	- Query parameters values MUST be percent-encoded.
	- Query parameters MUST start with a letter and SHOULD be all in lower case. Only alpha characters, digits and the underscore ( _ ) character SHALL be used.
	- Query parameters SHOULD be optional.
7. Field Names
	- Based on JSON Spec
	- Key names MUST be lower-case words, separated by an underscore character, ( _ ).
	- Fields that represent arrays SHOULD be named using plural nouns
8.Formatted date follow ISO8601
