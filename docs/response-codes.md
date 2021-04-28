# Response Codes

Every request returns a response code, these codes are standard HTTP to facilitate understanding of the type of response returned.

Code table for reference:

Code | Meaning
--------- | ----------
200 | Request was successful.
201 | Request was successful and a new resource was created.
400 | Server cannot or will not process the request.
401 | Request was not applied because it does not have valid authentication credentials.
404 | Server was unable to find the requested resource.
406 | Server cannot produce a response that matches the list of acceptable values.
500 | He encountered an unexpected condition that prevented him from fulfilling the request.


Reference: [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/status)