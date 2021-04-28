# Errors

Message | Meaning
--------- | ----------
Incomplete URL | The URL sent to our application is incomplete.
Not found response | We do not have or find the answer to the method sent.
Reference application not found | We did not receive the submitted application ** {slug-landingpage} **.
There are no results for this application | We did not find any results for the submitted application ** {slug-landingpage} **.
Unauthorized Token | The Token sent does not match the expected token.
Token Undefined | We did not receive the token in our application.
Internal Server Error | Internal server processing error.
Method not found | We have not received or the method sent.
Method does not exist | The submitted method does not exist.
Error in the past parameters | Error or absence in the parameters expected by the application.

#### API return example

```json
{
  "errors": [
    {
      "message": "Token Unauthorized",
    }
  ],
  "status_code": 401
  "method": "GET"
}
```
