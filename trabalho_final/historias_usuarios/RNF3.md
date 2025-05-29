# História de Usuário – Conformidade com Normas de Trânsito

**ID:** HU-RNF03  
**Requisito relacionado:** RNF03 – Conformidade com Normas de Trânsito  
**Título:** Cumprimento das normas de trânsito locais  

**Como** passageiro de um veículo autônomo,  
**Quero** que o veículo respeite as leis de trânsito vigentes na região onde está circulando,  
**Para que** eu me sinta seguro e confiante durante o trajeto.

---

## Critérios de Aceitação e Cenários

### Cenário 1: Respeito ao limite de velocidade

**Dado que** o veículo autônomo está trafegando em uma via com limite de velocidade de 50 km/h,  
**Quando** o limite é identificado por placas ou dados do mapa,  
**Então** o veículo deve ajustar sua velocidade para não ultrapassar esse limite.

---

### Cenário 2: Parada obrigatória em sinal vermelho

**Dado que** o veículo autônomo se aproxima de um semáforo com sinal vermelho,  
**Quando** o sinal é identificado por sensores ou integração com o sistema de tráfego,  
**Então** o veículo deve parar completamente antes da faixa de pedestres e só prosseguir quando o sinal estiver verde.

---

### Cenário 3: Prioridade para pedestres em faixas

**Dado que** há um pedestre se aproximando de uma faixa de travessia,  
**Quando** o veículo autônomo detectar a presença do pedestre,  
**Então** ele deve reduzir a velocidade e parar para garantir a travessia segura do pedestre antes de continuar o trajeto.
