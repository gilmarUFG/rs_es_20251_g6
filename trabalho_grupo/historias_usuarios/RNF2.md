# RNF2 - Precisão e Confiabilidade do Sistema de Geoposicionamento

## Narrativa:

* **Como** usuário passageiro
* **Eu quero** que o sistema identifique com precisão minha localização e o destino informado
* **Para** que a solicitação do veículo ocorra corretamente e eu não tenha problemas com embarque ou trajeto

## Cenário 1: Geolocalização precisa ao solicitar o veículo

* **Como** usuário passageiro
* **Quando** eu abrir o aplicativo para solicitar um veículo
* **Então** o sistema deve identificar automaticamente minha localização atual com precisão de até 10 metros
* **E** exibir essa localização no mapa para que eu possa confirmar ou ajustar, se necessário

## Cenário 2: Detecção e correção de falhas de localização

* **Como** usuário passageiro
* **Quando** houver falhas na identificação da localização atual ou do destino (por sinal fraco de GPS ou dados inconsistentes)
* **Então** o sistema deve exibir uma mensagem de aviso
* **E** solicitar confirmação manual da localização e/ou destino antes de prosseguir com a solicitação

## Cenário 3: Geoposicionamento falha e impede solicitação

* **Como** usuário passageiro
* **Quando** o sistema não conseguir obter uma localização válida após múltiplas tentativas
* **Então** a solicitação do veículo deve ser bloqueada
* **E** o usuário deve ser informado de que é necessário verificar sua conexão ou ativar o GPS para prosseguir
