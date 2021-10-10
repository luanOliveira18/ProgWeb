# Coletores
O projeto foi compilado usando o node 13.12.0, recomenda-se o uso do nvm para facilitar o controle da versão do node
Após a instalação da versão correta do node, basta acessar a pasta raiz do projeto e usar o comando npm install
Em seguida, o comando npm run dev
E o arquivo csv será gerado na pasta raiz do projeto

# Observação
Para trocar a api que gerará o csv, é necessário acessar src/app.js
E retirar o comentário de uma das linhas 30, 31 ou 32
Cada linha faz a chamada para execução de uma das api's e é necessário deixar apenas uma fora das linhas comentadas
