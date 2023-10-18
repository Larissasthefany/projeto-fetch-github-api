# projeto-fetch-github-api

Este é um projeto que interage com a API do GitHub para buscar informações de um usuário e seus repositórios. Ele consiste em várias partes, incluindo módulos JavaScript para a API, a lógica de busca e renderização de informações, bem como a interface de usuário.

## Funcionalidades

- Busca e exibição de informações de um usuário do GitHub.
- Exibição dos repositórios do usuário, caso existam.
- Tratamento de caso em que o usuário não é encontrado na API do GitHub.

## Estrutura do Código

O código do projeto está organizado em módulos e funções para manter a clareza e a manutenibilidade. Aqui está uma breve visão geral dos principais módulos:

- `variables.js`: Define variáveis de configuração, como a URL base da API do GitHub.
- `services/user.js`: Contém funções para buscar informações do usuário na API.
- `services/repositories.js`: Contém funções para buscar os repositórios do usuário na API.
- `objects/user.js`: Define um objeto para armazenar informações do usuário.
- `objects/screen.js`: Define um objeto para renderizar informações na tela.

## Como Usar

Para utilizar o projeto, siga estas etapas:

1. Clone o repositório para o seu ambiente de desenvolvimento.
2. Configure as variáveis em `variables.js`, se necessário.
3. Abra o arquivo HTML principal em seu navegador.
4. Insira o nome de usuário do GitHub e clique no botão de pesquisa ou pressione Enter.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas, sugestões ou enviar solicitações de pull para melhorar o projeto.❤️
