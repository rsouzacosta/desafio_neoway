# Neoway - Teste Técnico
## Desafio: Análise de documentos e criação de cenários de testes
No repositorio voce ira encontrar a pasta cenarios_sugestoes que possui os arquivos "cenarios" e "sugestoes", no arquivo cenarios esta os cenarios criados em Gherkin e no arquivo sugestoes estao todas sugestoes de melhoria

##  Desafio: Testes Funcionais - API
No repositorio voce ira encontrar a pasta testes_funcionais_api que possui os arquivos ServeRest "Tests.postman_collection.json" e "ServeRest.postman_environment.json", que sao os testes feitos para o segundo desafio em Postman, o "Tests.postman_collection.json" deve ser importado em Collections e "ServeRest.postman_environment.json" deve ser importado em Environments.

Para baixar o Postman, basta acessar https://www.postman.com/downloads/

- No primeiro arquivo "ServeRest Tests.postman_collection.json" voce encontra uma colecao de requestes para os cenarios 1 e 2 do segundo desafio e com seus respectivos testes.
    - Cenario 1, voce ira encontrar os teste para cadastrar, editar, deletar e pesquisar um usuario, cada requeste possui seus testes dentro da aba de teste
        - No request de cadastro voce deve executar o cadastro preenchendo na aba body as informacoes de cadastro.
        - Para editar o usuario, voce deve possuir a _id do usuario que deseja editar, informar ela
        na linha id na coluna Value, tambem na aba body informar os dados que deseja editar.
        - Deletando um usuario e necessario informar a _id na linha id na coluna Value, o usuario que deseja deletar.
        - Pesquisando um usuario por nome, basta apenas informar o nome do usuario no campo Value na linha nome.

    - Cenario 2, voce ira encontrar os requestes para cadastrar, login, cadastrar produto, adicionar o produto ao carrinho, finalizar a compra e verificar que quantidade foi debitada do produto.
        - No request de cadastro voce deve executar o cadastro preenchendo na aba body as informacoes de cadastro.
        - Apos executar o cadastro, execute o request de login, informando na aba body email e senha do usuario cadastrado, como resposta voce ira receber o token de authorization, o qual voce de ir na aba Environments, selecionar ServeRest, selecionar a linha loginToken e preencher a coluna "Current value" com o valor do que veio no token de authorization.
        - Possuindo o token voce agora pode cadastrar produto preenchendo na aba body as informacoes do produto, como resposta voce ira receber o _id do produto, que deve ser guardado e utilizado no proximo passo.
        - Apos ter os _id dos produtos que voce cadastrou, informe eles na aba body do request Adicionar produto ao carrinho e quantidade daquele produto que deseja adicionar ao carrinho
        - Para finalizar a compra utilize o request de Finalizar compra.
        - Para verificar a quantidade debitada do estoque do produto, pegue os _id dos produtos e informe na aba Params na linha idProduto na coluna Value do request Verificar quantidade debitada.

##  Desafio: Testes de Performance
Nessa parte do desafio foi usado o JMeter para aplicar o teste de perfomance, entao sera necessario instalar o JMeter para rodar os teste.

Para instalar o JMeter acesse https://jmeter.apache.org/download_jmeter.cgi

