# Técnicas para Especificação de Requisitos

## 1. Pesquisa sobre Técnicas de Especificação

### Técnica 1: Casos de Uso

**Descrição:**  
Casos de uso são uma técnica de especificação funcional que descreve como os usuários (atores) interagem com um sistema para alcançar um objetivo específico. Representam cenários de uso típicos do sistema, detalhando as interações passo a passo.

**Cenários Aplicáveis:**  
- Sistemas com múltiplos tipos de usuários e funcionalidades.
- Quando se deseja entender os comportamentos esperados do sistema sob diferentes perspectivas de usuário.

**Vantagens:**  
- Clareza na comunicação com os stakeholders.
- Foco na experiência do usuário.
- Facilita a identificação de requisitos funcionais.

**Desvantagens:**  
- Pode não capturar todos os detalhes técnicos necessários.
- Pode ser difícil manter atualizado em sistemas grandes com muitas interações.

---

### Técnica 2: Especificação por Requisitos Funcionais em Linguagem Natural Estruturada

**Descrição:**  
Consiste em descrever os requisitos em forma de frases ou parágrafos estruturados, usando uma linguagem controlada e padronizada para evitar ambiguidade.

**Cenários Aplicáveis:**  
- Projetos em fases iniciais de levantamento de requisitos.
- Equipes com menor familiaridade com diagramas UML ou outras linguagens formais.

**Vantagens:**  
- Fácil de entender por todos os envolvidos, inclusive stakeholders não técnicos.
- Rápida de escrever e modificar.

**Desvantagens:**  
- Suscetível a ambiguidades se não for bem estruturada.
- Difícil de automatizar ou formalizar.

---

## 2. Especificação de Requisitos do Cenário do Grupo

### Requisito A (Especificado via Técnica 1 - Casos de Uso)

**Título:** Registrar Novo Usuário

**Ator Principal:** Usuário

**Pré-condições:**  
- O usuário não pode estar logado no sistema.

**Fluxo Principal:**
1. O usuário acessa a tela de cadastro.
2. O sistema solicita as informações: nome, e-mail, senha.
3. O usuário preenche os dados e confirma.
4. O sistema valida as informações.
5. O sistema armazena os dados e confirma o cadastro.

**Fluxo Alternativo:**
- 4a. Caso algum campo esteja inválido, o sistema exibe uma mensagem de erro e permite nova tentativa.

**Pós-condições:**  
- O usuário está cadastrado no sistema e pode fazer login.

---

### Requisito B (Especificado via Técnica 2 - Linguagem Natural Estruturada)

**Requisito:**  
O sistema **deve permitir** que o **administrador** gere **relatórios mensais** de atividade dos usuários, contendo dados de acesso, uso das funcionalidades e tempo médio de sessão.

**Justificativa:**  
Este requisito é necessário para análise de engajamento e planejamento de melhorias na plataforma.

**Critérios de Aceitação:**
- O relatório deve ser exportável em formato PDF.
- Deve conter filtros por período, usuário e tipo de atividade.
- A geração do relatório não pode demorar mais de 30 segundos.

---

