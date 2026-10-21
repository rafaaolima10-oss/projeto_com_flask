# **Projeto Flask — Primeira Aplicação Web**

## **Apresentação**

Este projeto foi desenvolvido durante uma aula de Python para conhecer o Flask e aprender como utilizá-lo na criação de aplicações web. A atividade também apresentou o UV, ferramenta utilizada para gerenciar pacotes e dependências do Python.

Para iniciar o desenvolvimento, utilizamos o ambiente Python preparado anteriormente. Em seguida, instalamos o UV pelo terminal, configuramos o projeto e adicionamos o Flask para criar e executar as páginas web.

## **Desenvolvimento da atividade**

Ao longo da aula, implementamos diferentes rotas para compreender como o Flask recebe requisições e apresenta informações ao usuário:

- `/` — apresenta a mensagem inicial "Olá, Mundo!".
- `/pessoa?nome=SeuNome` — utiliza o nome enviado pela URL para montar uma saudação.
- `/usuario/SeuNome` — recebe o nome diretamente pelo caminho da rota.
- `/ola/` e `/ola/SeuNome` — acessam uma página HTML com a possibilidade de personalizar a mensagem.

Além das rotas, desenvolvemos o arquivo `ola.html`, responsável por exibir a saudação na página. O conteúdo pode variar de acordo com o nome informado ou apresentar uma mensagem padrão quando nenhum nome é fornecido.

Após finalizar os testes locais com o comando `uv run flask run`, criamos um repositório no GitHub para armazenar os arquivos e facilitar o acesso ao código do projeto.

## **Ferramentas e linguagens**

- **Python:** linguagem utilizada no desenvolvimento da aplicação.
- **UV:** ferramenta para gerenciamento de pacotes e dependências.
- **Flask:** framework utilizado para criar as rotas e estruturar a aplicação web.
- **HTML:** linguagem utilizada na construção da página apresentada ao usuário.
- **Git e GitHub:** ferramentas utilizadas para controlar versões e armazenar o projeto em um repositório remoto.

## **Passos para executar o projeto**

Primeiro, clone o repositório para o computador e abra o terminal na pasta do projeto.

Depois, execute o comando abaixo:

```plaintext
uv run flask run
```

Quando a aplicação iniciar, o terminal exibirá o endereço local para acesso. Normalmente, ele será:

[http://127.0.0.1:5000](http://127.0.0.1:5000)

Abra esse endereço no navegador para visualizar a aplicação e testar as rotas implementadas.

## **Considerações finais**

A realização dessa atividade permitiu compreender os conceitos iniciais do Flask e sua utilização na criação de páginas web com Python. Durante o desenvolvimento, pratiquei a criação de rotas, o recebimento de parâmetros pela URL e a utilização de templates HTML para apresentar informações personalizadas.

Também aprendi a utilizar o UV na configuração do ambiente e o GitHub para manter os arquivos do projeto organizados e disponíveis para consulta.

*Projeto desenvolvido em aula com finalidade educacional.*