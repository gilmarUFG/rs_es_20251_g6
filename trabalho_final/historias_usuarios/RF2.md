# RF2 - Validação do Veículo por Código de Confirmação

## Narrativa:

* **Como** usuário passageiro
* **Eu quero** validar se o veículo que chegou é o correto por meio de um código de confirmação
* **Para** que eu tenha segurança de que estou embarcando no veículo correto

## Cenário 1: Validação com Código Correto

* **Como** usuário passageiro
* **Quando** o veículo chegar até minha localização
* **Eu quero** visualizar o código de confirmação no aplicativo
* **Assim que** o código exibido no painel do veículo for igual ao do aplicativo
* **Então** O sistema permitirá o embarque e iniciará a viagem

## Cenário 2: Validação com Código Incorreto

* **Como** usuário passageiro
* **Quando** o veículo chegar até minha localização
* **Eu quero** validar o código exibido no painel do veículo
* **Assim que** o código for diferente do exibido no aplicativo
* **Então** O sistema impedirá o embarque e exibirá uma mensagem de erro informando a inconsistência

## Cenário 3: Validação Não Realizada

* **Como** usuário passageiro
* **Quando** o veículo chegar até minha localização
* **Eu quero** confirmar o código antes de embarcar
* **Assim que** eu tentar embarcar sem validar o código
* **Então** O sistema impedirá o embarque e solicitará a validação do código exibido
