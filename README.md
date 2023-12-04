# API REST e Implementação RESTful

API REST, também chamada de API RESTful, é uma interface de programação de aplicações (API ou API web) que segue as restrições do estilo de arquitetura REST. REST é a sigla em inglês para "Representational State Transfer", que em português significa transferência de estado representacional. Essa arquitetura foi criada pelo cientista da computação Roy Fielding.

## Métodos HTTP

Os métodos HTTP são responsáveis por indicar a ação a ser executada para um dado recurso. Os principais métodos HTTP são:

- **GET**: Solicita a representação de um recurso específico.
- **HEAD**: Solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.
- **POST**: Utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
- **PUT**: Substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
- **DELETE**: Remove um recurso específico.
- **CONNECT**: Estabelece um túnel para o servidor identificado pelo recurso de destino.
- **OPTIONS**: Descreve as opções de comunicação para o recurso de destino.
- **TRACE**: Executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
- **PATCH**: Utilizado para aplicar modificações parciais em um recurso.

## Códigos de Status HTTP

Os códigos de status HTTP indicam se uma solicitação HTTP específica foi concluída com sucesso. Eles são agrupados em cinco classes:

- **1xx**: Informativo.
- **2xx**: Sucesso.
- **3xx**: Redirecionamento.
- **4xx**: Erro do cliente.
- **5xx**: Erro do servidor.

Cada código de status tem um significado específico e é retornado na resposta do servidor. Por exemplo, "200 OK" indica que a solicitação foi bem-sucedida, enquanto "404 Not Found" indica que o recurso solicitado não pôde ser encontrado no servidor.
# resumoApiREST
