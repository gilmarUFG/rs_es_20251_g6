# Técnicas para Especificação de Requisitos

## 1. Casos de Uso

### O que é:

Casos de uso são como histórias que mostram o passo a passo do que um usuário pode fazer dentro do sistema. Eles descrevem as interações entre o sistema e quem está usando (chamado de ator). Também podem ser representados por desenhos (diagramas UML) junto com descrições em texto.

### Quando usar:

-   Quando o projeto é mais organizado e já se sabe mais ou menos o que o sistema vai precisar fazer.
-   Quando a equipe gosta de usar documentação mais detalhada e formal.
-   Quando o sistema tem várias funções e diferentes tipos de usuários.

### Vantagens:

-   Ajuda a entender bem como o sistema vai funcionar na prática.
-   Facilita a conversa entre quem está desenvolvendo e o cliente.
-   Mostra direitinho os caminhos que o usuário pode seguir no sistema.

### Desvantagens:

-   Dá um pouco mais de trabalho para manter atualizado se as coisas mudarem muito.
-   Precisa ter uma noção básica de UML para entender bem.
-   Não fala muito sobre requisitos técnicos ou de desempenho, por exemplo.

## 2. User Stories (Histórias de Usuário)

### O que é:

As User Stories são descrições simples e rápidas do que o usuário quer fazer no sistema. Sempre seguem um formato padrão, tipo: "Como [tipo de usuário], eu quero [o que ele quer fazer] para que [benefício ou motivo]".

### Quando usar:

-   Quando o projeto está usando métodos ágeis, como Scrum.
-   Quando os requisitos ainda podem mudar bastante durante o desenvolvimento.
-   Quando a equipe prefere comunicação mais direta e menos papelada.

### Vantagens:

-   É fácil de escrever e qualquer pessoa entende, mesmo quem não é técnico.
-   Coloca o foco no que o usuário realmente precisa.
-   Permite mudar e adaptar conforme o projeto vai evoluindo.

### Desvantagens:

-   Às vezes falta detalhe, então precisa conversar bastante com o cliente.
-   Pode não ser suficiente sozinha em projetos muito grandes ou complexos.
-   Requer uma documentação extra se for necessário mais aprofundamento técnico.

## Requisitos Selecionados para o Aplicativo de Mobilidade Urbana com Veículos Autônomos

### Requisito 1: Agendamento de Veículo

**Técnica de Especificação:** Histórias de Usuário

**História de Usuário 1:**

> **Como** usuário do sistema do aplicativo,  
> **eu quero** poder agendar a solicitação de um veículo para um horário e rota específicos,  
> **para que** eu possa garantir que o transporte estará disponível no momento e local desejados, evitando atrasos e imprevistos.

---

### Requisito 2: Acompanhamento de Viagem por Familiares

**Técnica de Especificação:** Caso de Uso

**Caso de Uso: Acompanhar Viagem em Tempo Real**

-   **Ator Primário:** Familiar autorizado
-   **Pré-condição:** O usuário principal autorizou o compartilhamento da rota com o familiar em sua conta ou gerou um link de compartilhamento da rota.

**Fluxo Principal:**

1. O familiar acessa o aplicativo e entra na área “Acompanhar Viagem” ou o link de acesso compartilhado pelo usuário.
2. O sistema lista os usuários vinculados e as viagens em andamento.
3. O familiar seleciona a viagem desejada.
4. O sistema exibe em tempo real:
    - A localização do veículo
    - O status da viagem (em andamento ou concluído)
    - O tempo estimado de chegada

**Fluxos Alternativos:**

1. Nenhuma viagem em andamento: o sistema exibe uma mensagem de que não há viagens em curso.

**Pós-condição:**  
O familiar consegue visualizar o trajeto e o status da viagem em tempo real.

---
