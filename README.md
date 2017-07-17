# Game Error And Messages

### Login Response
Message: | Description:
----------------- | ------------------
LOGIN_RESULT_0 | Login Successful
LOGIN_RESULT_1 | Invalid Bet
LOGIN_RESULT_2 | Not In Bet Time
LOGIN_RESULT_3 | Not A Member
LOGIN_RESULT_4 | Insuffcient Fund
LOGIN_RESULT_5 | Cannot Bet
LOGIN_RESULT_6 | Bet Exceeds Limit
LOGIN_RESULT_7 | Bet Is Over Maximum Limit
LOGIN_RESULT_8 | Bet Is Over Minimum Limit

### Bet Response
Message: | Description:
----------------- | ------------------
BET_RESULT_0 | Bet Successful
BET_RESULT_1 | Invalid Ticket
BET_RESULT_2 | Account Does Not Exist
BET_RESULT_3 | Incorrect Username Or Password 
BET_RESULT_4 | Account Is Locked
BET_RESULT_5 | Acocunt Already Login
BET_RESULT_6 | Login Failed


# HTTP Status Messages
### 4xx: Client Error

Message: | Description:
----------------- | ------------------
400 Bad Request | The request cannot be fulfilled due to bad syntax
401 Unauthorized | The request was a legal request, but the server is refusing to respond to it. For use when authentication is possible but has failed or not yet been provided
402 Payment Required | Reserved for future use
403 Forbidden | The request was a legal request, but the server is refusing to respond to it
404 Not Found | The requested page could not be found but may be available again in the future
405 Method Not Allowed | A request was made of a page using a request method not supported by that page
406 Not Acceptable | The server can only generate a response that is not accepted by the client
407 Proxy Authentication Required | The client must first authenticate itself with the proxy
408 Request Timeout | The server timed out waiting for the request
409 Conflict | The request could not be completed because of a conflict in the request
410 Gone | The requested page is no longer available
411 Length Required | The "Content-Length" is not defined. The server will not accept the request without it 
412 Precondition Failed | The precondition given in the request evaluated to false by the server
413 Request Entity Too Large | The server will not accept the request, because the request entity is too large
414 Request-URI Too Long | The server will not accept the request, because the URL is too long. Occurs when you convert a POST request to a GET request with a long query information 
415 Unsupported Media Type | The server will not accept the request, because the media type is not supported 
416 Requested Range Not Satisfiable | The client has asked for a portion of the file, but the server cannot supply that portion
417 Expectation Failed | The server cannot meet the requirements of the Expect request-header field

### 5xx: Server Error

Message: | Description:
----------------- | ------------------
500 Internal Server Error | A generic error message, given when no more specific message is suitable
501 Not Implemented | The server either does not recognize the request method, or it lacks the ability to fulfill the request
502 Bad Gateway | The server was acting as a gateway or proxy and received an invalid response from the upstream server
503 Service Unavailable | The server is currently unavailable (overloaded or down)
504 Gateway Timeout | The server was acting as a gateway or proxy and did not receive a timely response from the upstream server
505 HTTP Version Not Supported | The server does not support the HTTP protocol version used in the request
511 Network Authentication Required | The client needs to authenticate to gain network access
