## NODE.JS

E um interpretador Javascript que não depende do navegador, ou seja, ele totalmente desvinculado do navegador.

## VANTAGENS

muito leve,pouco uso de memoria Ram, melhor aproveitamento da cpu. 
utiliza Javascript
tem um dos maiores ecossistema de bibliotecas, modulos e plug-ins do mundo
suporta um número imenso de requisições.
as empresas que usa: ebay, Netflix, microsoft, paypal, uber.

## ABAIXANDO APLICATIVO

entra no site do node.js e vai ter duas opções para vc baixar o node.js, uma de teste e a outra.

## TESTANDO NODE.JS

criar uma pasta na área de trabalho,
abrir o cmd é uma ferramenta que nós vai usar muito no curso,
pelo cmd ele quer chegar até a pasta na área de trabalho,
o comando que  nós vai usar cd para mudar o diretorio,
logo em seguida nos entra com o comando cd desktop,
continuando nós vai colocar o comando  cd e o nome da pasta da area de trabalho e pegar é arrastar a pasta no cdm,
abrir o vs code 
e colocar app.js na pasta do vs code para usar a linguagem js, 
e aqui nós já está testando alguns comando no vs code, colocar console.log("helloo world")
no terminal coloca cd helloworld,
na mesma pasta do vs code coloca var nome = "joao",
na outra linha colocar var sobrenome = "policate",
e depois colocar  console.log(nome, " ",sobrenome);
vai no terminal e coloca node app.js.

## API

API, ou Interface de Programação de Aplicações (Application Programming Interface), é um conjunto de definições e protocolos que permite a comunicação entre diferentes softwares. As APIs são fundamentais para a integração de sistemas, permitindo que diferentes aplicações troquem dados e funcionalidades de maneira eficiente.

## Função E Importância Das APIs

Cadastro e Consulta: Permite cadastrar, consultar e tratar manifestações feitas por usuários.
Listagem de Tipos de Formulário: Oferece endpoints para listar diferentes tipos de formulários e manifestações.
Consulta a Órgãos Públicos: Possibilita a consulta e listagem de órgãos públicos, assuntos relacionados e canais de entrada para manifestações.

## Exemplos de Endpoints

GET api/tipos-formulario: Para listar os tipos de formulário disponíveis.
GET api/orgaos-siorg: Para consultar os órgãos registrados no sistema.
POST api/manifestacoes: Para registrar novas manifestações.

## MYSQL

Para criar uma API utilizando MySQL, você pode seguir diversas abordagens, dependendo da linguagem de programação e do framework que escolher.

## Criando uma API com Node.js

Configuração Inicial:
Crie um novo projeto Node.js e inicialize-o com npm init -y.
Instale os pacotes necessários como mysql2, dotenv, e express.
Implementação:
Crie um arquivo de configuração .env para armazenar as credenciais do banco de dados.
Construa as rotas da API que interagem com o MySQL, permitindo operações como adicionar, buscar e deletar registros.

## Passos Gerais para Criar uma API com MySQL

Instalação do MySQL: Certifique-se de que o MySQL está instalado e configurado corretamente no seu sistema.
Criação do Banco de Dados: Defina um banco de dados e crie as tabelas necessárias para armazenar os dados.
Desenvolvimento da API: Escreva o código que define as rotas e a lógica de negócios da sua API, utilizando a linguagem e framework escolhidos.
Testes: Utilize ferramentas como Postman ou Insomnia para testar as funcionalidades da sua API.