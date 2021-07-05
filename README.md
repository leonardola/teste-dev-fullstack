# Teste para Desenvolvedor Full Stack Imovago

## Conhecimentos que você precisará:

- php
- css
- javascript
- html
- bootstrap (https://getbootstrap.com/)

## Iniciando o projeto:
- Crie um repositório **privado** com o nome teste-dev-fullstack-imovago
- Inclua o usuário leonardola no repositório
- Configure algum servidor com apache, php e mysql (mamp, lamp, wamp, xamp, wampps, etc)
- Abra o arquivo index em seu navegador

## O que precisa ser feito:
### Crie uma página com um formulário de cadastro de pessoas
- O formulário deve ter os campos nome, email, telefone e foto
- Crie uma forma de armazenar estes dados no servidor
- Os dados devem ser salvos no banco de dados e a imagem na pasta /images
- O formulário precisa funcionar em desktop e mobile 

### Crie um painel admin com um cabeçalho e menu
- O menu deve ser colapsavel para smartphones
- Adicione um menu pessoas e sair
- Este painel deve ser acessível apenas por administradores utilizando login e senha cadastrados no banco de dados
- Este painel servirá de template para várias páginas por tanto crie-o de uma forma que possa ser reutilizado

### Dentro do admin crie uma página de listagem de pessoas cadastradas mostrando todos os dados
- Você pode utilizar as tabelas do bootstrap para isso https://getbootstrap.com/docs/5.0/content/tables/   
- Permita uma pesquisa por nome ou email
- Permita remover pessoas
- Permita editar os dados de uma pessoa
- Permita baixar todos os dados de todas as pessoas com link das imagens em um csv. O link da imagem pode ser http://localhost/images/<imagem>

### Dentro do admin crie uma página para listagem de usuários admin
- Utilize a tabela do bootstrap para isso.
- Mostre apenas nome e login
- Permitir remover um usuário
  
### Dentro do admin crie uma página para criação de usuários admin
- Deve conter os campos nome, login e senha

## Quer se destacar?
- Utilize o framework symfony https://symfony.com/
- Escreva todo o código em inglês deixando apenas os textos em português
- Crie nomes de funções e váriaveis que sejam fáceis de entender
- Crie o código de uma forma que seja o máximo reutilizável e fácil de entender
- Faça os salvamentos via ajax
- Faça a pesquisa na listagem de pessoas via javascript
- Armazene as senhas de forma segura 
- Crie uma páginação na listagem de pessoas
- Utilize o conceito MVC
- Crie rotas amigáveis utilizando um htaccess
- Crie um design elegante
- Crie e modele o banco de dados utilizando o mysql workbench e adicione o arquivo no repositório
- Hospede seu código em algum servidor que possa ser acessado publicamente e envie o link no email de conclusão


## Quando concluir:
- Envie um email para suporte@imovago.com.br com o titulo "Teste vaga Imovago" avisando da conclusão e com o link do repositório
- O repositório deve conter tudo o que é necessário para iniciar o projeto. Por tanto adicione o script de criação do banco de dados
- Documente no readme.md os passos para que este projeto possa ser testado
