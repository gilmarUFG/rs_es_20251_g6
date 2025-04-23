# Técnicas para Especificação de Requisitos

## 1. Técnicas de Especificação

### 1.1. Técnica: Prototipação

**Descrição:**  
A prototipação consiste na criação de representações visuais e interativas (protótipos) das telas ou funcionalidades do sistema, permitindo aos usuários e stakeholders visualizarem e testarem as funcionalidades antes da implementação.

**Cenários de Aplicação:**  
- Projetos com foco em interface gráfica (UI/UX).  
- Quando há dificuldade dos usuários em compreender requisitos textuais.  
- Quando se deseja validar ideias antes do desenvolvimento.

**Vantagens:**  
✅ Facilita o feedback imediato dos usuários.  
✅ Reduz riscos de retrabalho com validação prévia.  
✅ Excelente para detalhar interfaces e interações visuais.

**Desvantagens:**  
❌ Pode gerar expectativa de que o sistema já está pronto.  
❌ Requer ferramentas e tempo extra para criação.  
❌ Foco excessivo em layout pode ofuscar regras de negócio.

---

### 1.2. Técnica: Especificação por Requisitos Funcionais (RF)

**Descrição:**  
Consiste em descrever detalhadamente as funcionalidades que o sistema deve oferecer. Cada requisito funcional representa uma ação ou comportamento esperado do sistema.

**Cenários de Aplicação:**  
- Projetos com documentação mais formal e estruturada.  
- Equipes que seguem processos tradicionais (ex: RUP).  
- Quando é necessário um contrato claro com o cliente.

**Vantagens:**  
✅ Foco direto nas funcionalidades a serem desenvolvidas.  
✅ Clareza sobre o comportamento esperado do sistema.  
✅ Facilita testes e validações técnicas.

**Desvantagens:**  
❌ Pode ser difícil para o cliente interpretar sem auxílio.  
❌ Nem sempre reflete a experiência real do usuário.  
❌ Pode ser rígido demais em contextos ágeis.

---

## 2. Especificação de Requisitos

### Cenário: Sistema de Transporte Autônomo Urbano

---

### Requisito A – Técnica: Prototipação

**Requisito:** Interface de Escolha do Nível de Privacidade

**Descrição:**  
O sistema deve permitir que o passageiro selecione o nível de privacidade desejado durante a viagem (ex: cortinas fechadas, vidros escurecidos, silêncio total).

**Representação:**  
Protótipo interativo com três botões (modo aberto, intermediário, privado), exibindo a alteração imediata da configuração do veículo.

**Justificativa:**  
A prototipação permite ao usuário final testar e visualizar as alterações no ambiente do veículo, essencial para validar conforto e preferências.

---

### Requisito B – Técnica: Requisitos Funcionais

**Requisito Funcional:** RF-08 – Emissão de Relatório Pós-Viagem

**Descrição:**  
O sistema deve gerar automaticamente um relatório de viagem contendo: horário de início e fim, distância percorrida, valor cobrado, eventos registrados e feedback do usuário.

**Pré-condições:**  
- Viagem deve estar finalizada.  
- O usuário deve estar logado.

**Pós-condições:**  
- O relatório deve ser salvo no histórico do usuário e enviado por e-mail.

