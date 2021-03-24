# Autenticação

As soluções dessa aplicação utilizam **Bearer Token**, em todas as requisições é necessário que o token (chave de autenticação) seja informado. 

Cada landingpage tem a sua chave de autenticação única. Sua chave de autenticação é disponibilizada na barra superior do painel administrativo da sua landingpage.

Todas as requisições para a nossa solução seguem o mesmo prefixo de URL: https://api.lpquevende.com.br/{slug-landingpage}

**{slug-landingpage}**: é o nome da loja utilizado para referência na nossa API, é o mesmo prefixo utilizado para a domínio da landingpage.

`example.lpquevende.com.br` seu slug é: `example`.   

`Content-type` tipo do conteúdo padrão: `application/json`.

Para mais informações sobre [Bearer Token](https://swagger.io/docs/specification/authentication/bearer-authentication/) 

[Obtenha aqui o seu token!](url)