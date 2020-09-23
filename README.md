# mdr-api-design-standard
MDR API Repository

Rest API Permen Naming Conventions

1. URIs follow RFC 3986 Spec.
2. URI component : https://36.89.146.92:8040/namespace/project-name/v1/search
3. URI maximum Length <=2000. Allowable chars : commas, underscore, question mark, hyphens, plus, slash 
4. URI Naming Conventions
	4.1 the URI MUST be specified in all lower case
	4.2 only hyphens '-' can be used to separate words or path parameters for readability (no spaces or underscores)
	4.5 only underscores '_' can be used to separate words in query parameter names but not as part of the base URI
5 Resource Names / Collections
	5.1 Nouns MUST be used - not verbs for names.
	5.2 Resource names MUST be plural
	5.3 Resource names MUST be lower-case and use only alphabetic characters and hyphens
	5.4 The hyphen character, ( - ), MUST be used as a word separator in URI path parameters
6. Query
	6.1 Literals/expressions in query strings SHOULD be separated using underscore ( _ ).
	6.2 Query parameters values MUST be percent-encoded.
	6.3 Query parameters MUST start with a letter and SHOULD be all in lower case. Only alpha characters, digits and the underscore ( _ ) character SHALL be used.
	6.4 Query parameters SHOULD be optional.
7. Field Names
	7.1 Based on JSON Spec
	7.2 Key names MUST be lower-case words, separated by an underscore character, ( _ ).
	7.3 Fields that represent arrays SHOULD be named using plural nouns
8.Formatted date follow ISO8601
