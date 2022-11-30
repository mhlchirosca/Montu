# Montu

Montu was the powerful falcon-god of war.

## Purpose & Mindset

Core functionality that Montu project aims to offer:

* http-requests-collections-as-code
* readable, user-friendly and unambigous schema to define http-requests-collections
* the ability to make assertions based on the http received responses.
* the ability define, pass, and perform operations on variables and certain bits of the request and response body
* a translator/transpiller from the here defined schema to Postman Collection v2.1
* a collection linter


Possible extensions:

* a translator/transpiller from the here defined schema to a curl based collection;
* a plugin system that allows to expand the schema
* a VSCode compatible linter
* a validator that uses/leverages existing OpenAPI v3 schemas to enforce/check the existence of certain groups/flows/http-requests

Remarks:
* at this point in time Montu wont be able to run the collection itself and will relly on the translator/transpiller to create `Postman` and/or `curl` runnable collections. The reason for this is: Montu doesn't want to re-invent the wheel, at least not yet ;).


Disclaimer! Any of the above statements is up for discussion.
