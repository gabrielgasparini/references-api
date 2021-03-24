# Erros

Message | Significado
---------|----------
 Incomplete URL | A URL enviada para a nossa aplicação está incompleta
 Not found response | Não possuimos ou encontramos a resposta para a método enviado 
 Reference application not found | Não recebemos a aplicação enviada {slug-landingpage}
 There are no results for this application | Não encontramos resultado para a aplicação enviada {slug-landingpage}
 Token Unauthorized | O Token enviado não condiz com o token esperado
 Token Undefined | Não recebemos o token em nossa aplicação
 Internal Server Error | Erro interno de processamento do servidor
 Method not found | Não recebemos ou o método enviado
 Method does not exist | O método enviado não existe
 Error in the past parameters | Erro ou ausência nos parâmetros esperados pela aplicação

#### Exemplo de retorno da API

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
