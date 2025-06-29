# UFG - Técnicas para Especificação de Requisitos

> **Aluno:** Mateus Henrique Gandi 202201706 
> **Disciplina:** Requisitos de Software  
> **Data de Entrega:** 23/04/2025  


## Técnica 1: Casos de Uso

### Descrição
Casos de uso descrevem de forma estruturada as interações entre o sistema e seus usuários ou componentes externos, com foco em alcançar um objetivo específico.

### Aplicabilidade
Ideal para sistemas com várias formas de interação, como veículos autônomos que precisam lidar com sensores, usuários e ambientes, enfim, calcular e pensar todo um trajeto enquanto prossegue.

### Vantagens
- Fornece visão clara dos comportamentos esperados;
- Suporta identificação de exceções e fluxos alternativos;
- Facilita a rastreabilidade com os testes.

###  Desvantagens
- Pode ser dificil de implementar em sistemas com muitas interações;
- Requer atualização constante devido a mudanças de requisitos.

---

## Técnica 2: Histórias de Usuário com Critérios de aceitação

### Descrição
Histórias de usuário são declarações simples e voltadas ao usuário. Com critérios de aceitação são mais completas para guiar implementações e testes.

### Aplicabilidade
Muito útil em equipes que usam metodologias ágeis que trabalham com rotinas incrementais.

### Vantagens
- Escrita simples, entendível por qualquer membro da equipe;
- Permite priorização de funcionalidades;
- Foco na experiência do usuário final.

### Desvantagens
- Pode faltar detalhamento técnico;
- Critérios de aceitação mal definidos causam ambguidade.

---

## Sistema de Veículos Autônomos

### Requisito A (Técnica: Casos de Uso)

#### Título: "Navegação ate o destino"

**Ator Primário:** Passageiro  
**Pré-condição:** O veículo está ligado e pronto para iniciar a navegação.  
**Fluxo Principal:**
1. O passageiro informa o destino por comando de voz ou toque na tela.
2.O sistema valida o endereço e calcula a rota mais eficiente.
3. O veículo inicia o trajeto de forma autônoma.
4. O sistema monitora o tráfego e recalcula rotas, se necessário.
5. Ao chegar no destino, o sistema informa o passageiro.

**Pós-condição:** O veículo finaliza o trajeto com segurança.

---

### Requisito B (Técnica: História de Usuário)

**História:**  
"Como passageiro, quero receber uma notificação no meu celular quando o veículo estiver a 1 minuto de distância, para me preparar para embarcar."

**Critérios de Aceitação:**
- Dado que o passageiro solicitou um veículo autônomo e está aguardando em uma localização,
- Quando o veículo estiver a 1 minuto de distância,
- Então o sistema envia automaticamente uma notificação push para o aplicativo do passageiro.

