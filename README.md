# projeto-fetch-github-api
Este simples aplicativo da web permite que você pesquise perfis de usuários do GitHub pelo nome de usuário. Ele recupera informações de usuário e repositórios da API do GitHub e exibe os dados de maneira amigável.

## Início

### Pré-requisitos

Certifique-se de ter um navegador da web moderno que suporte JavaScript.

### Instalação

1. Clone este repositório em sua máquina local ou faça o download do arquivo ZIP.
2. Abra o arquivo `index.html` em seu navegador da web.

## Uso

1. Insira o nome de usuário do GitHub que você deseja pesquisar no campo de entrada.
2. Clique no botão "Pesquisar" ou pressione a tecla "Enter".
3. As informações de perfil do usuário e uma lista de seus repositórios serão exibidas na página.

## Explicação do Código

A funcionalidade principal deste aplicativo é impulsionada pelo código JavaScript. Aqui está uma breve explicação dos principais componentes:

- O ouvinte de evento `click` no botão de pesquisa e o ouvinte de evento `keyup` no campo de entrada permitem que os usuários pesquisem perfis do GitHub, clicando no botão ou pressionando a tecla Enter.

- A função `getUserProfile` busca os dados do usuário na API do GitHub e os exibe na página, incluindo o nome do usuário, biografia e avatar.

- A função `getUserRepositories` busca os repositórios do usuário e os exibe em uma lista.

- Os dados do usuário e dos repositórios são buscados na API do GitHub usando `fetch` e, em seguida, processados e exibidos na página.
