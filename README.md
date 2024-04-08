# Neoway - Teste Técnico
## Desafio: Análise de documentos e criação de cenários de testes
No repositorio voce ira encontrar a pasta cenarios_sugestoes que possui os arquivos "cenarios" e "sugestoes", no arquivo cenarios esta os cenarios criados em Gherkin e no arquivo sugestoes estao todas sugestoes de melhoria

##  Desafio: Testes Funcionais - API
No repositorio voce ira encontrar a pasta testes_funcionais_api que possui os arquivos ServeRest "Tests.postman_collection.json" e "ServeRest.postman_environment.json", que sao os testes feitos para o segundo desafio em Postman, o "Tests.postman_collection.json" deve ser importado em Collections e "ServeRest.postman_environment.json" deve ser importado em Environments.

Para baixar o Postman, basta acessar https://www.postman.com/downloads/

- No primeiro arquivo "ServeRest Tests.postman_collection.json" voce encontra uma colecao de requestes para os cenarios 1 e 2 do segundo desafio e com seus respectivos testes.
    - Cenario 1, voce ira encontrar os teste para cadastrar, editar, deletar e pesquisar um usuario, cada requeste possui seus testes dentro da aba de teste
        - TBD
    - Cenario 2, voce ira encontrar os requestes para cadastrar, login, cadastrar produto, adicionar o produto ao carrinho, finalizar a compra e verificar que quantidade foi debitada do produto.
        - Nesse cenario voce deve executar o cadastro preenchendo na aba body as informacoes de cadastro.
        - Apos executar o cadastro, execute o request de login, informando na aba body email e senha do usuario cadastrado, como resposta voce ira receber o token de authorization, o qual voce de ir no segundo arquivo "ServeRest.postman_environment.json" e preencher a coluna "Current value" com o valor do que veio no token de authorization.