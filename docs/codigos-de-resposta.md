# Códigos de Resposta 

Toda requisição retorna um código de resposta, esses códigos são padrão HTTP para facilitar o entendimento do tipo de resposta retornada.

Tabela de códigos para referência:


Código | Significado
---------|----------
 200 | Requisição foi bem sucedida.
 201 | Requisição foi bem sucedida e que um novo recurso foi criado.
 400 | Servidor não pode ou não irá processar a requisição.
 401 | Solicitação não foi aplicada porque não possui credenciais de autenticação válidas.
 404 | Servidor não conseguiu encontrar o recurso solicitado.
 406 | Servidor não pode produzir uma resposta que combine com a lista de valores aceitáveis.
 500 | Encontrou uma condição inesperada e que o impediu de atender à solicitação.


Referência: [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/status)