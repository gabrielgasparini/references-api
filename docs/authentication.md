# Authentication

The solutions of this application use ** Bearer Token **, in all requests it is necessary that the token (authentication key) is informed.

Each landing page has its unique authentication key. Your authentication key is available in the top bar of your landing page's administrative panel.

All requests for our solution follow the same URL prefix: `https://api.lpquevende.com/{slug-landingpage}`

** {slug-landingpage} **: is the name of the store used for reference in our API, it is the same prefix used for the landingpage domain.

`example.lpquevende.com.br` your slug is: `example`.   

`Content-type` default content type: `application/json`.

For more information on: [Bearer Token](https://swagger.io/docs/specification/authentication/bearer-authentication/)

[Get your token here!](https://app.lpqv.com.br/acesso/entrar)