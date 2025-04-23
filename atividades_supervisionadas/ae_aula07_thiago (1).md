# Atividade Extraordinária – Aula 07  
**Aluno:** Thiago  
**Disciplina:** Engenharia de Requisitos  
**Data:** 23/04/2025  

## Técnicas de Especificação de Requisitos

### 1. Casos de Uso

#### Descrição:
Casos de uso são uma técnica utilizada para descrever as interações entre um ator (usuário ou sistema externo) e o sistema, com foco no comportamento do sistema diante de um cenário específico. A modelagem é feita com auxílio de diagramas e descrições textuais que detalham o fluxo principal e os fluxos alternativos de cada caso de uso.

#### Cenários Aplicáveis:
- Projetos com foco em funcionalidades e interação entre usuários e o sistema.
- Aplicações em que o entendimento do fluxo de trabalho é essencial.
- Sistemas web ou aplicativos com múltiplos tipos de usuários.

#### Vantagens:
- Fácil de entender por todos os stakeholders, incluindo os não técnicos.
- Fornece uma visão clara do comportamento esperado do sistema.
- Ajuda a identificar atores e suas necessidades.

#### Desvantagens:
- Pode ser limitado na captura de requisitos não-funcionais.
- Pode tornar-se complexo com muitos fluxos alternativos.
- A modelagem pode demandar tempo em sistemas muito grandes.

---

### 2. Especificação por Histórias de Usuário

#### Descrição:
Histórias de usuário são uma técnica ágil que expressa requisitos de forma simples, do ponto de vista do usuário final. Geralmente seguem o formato: "Como [tipo de usuário], eu quero [alguma funcionalidade] para [benefício ou valor]".

#### Cenários Aplicáveis:
- Projetos com metodologia ágil (como Scrum ou Kanban).
- Equipes que priorizam entregas rápidas e incrementais.
- Quando há proximidade e comunicação constante com o cliente.

#### Vantagens:
- Simples, rápida de escrever e fácil de modificar.
- Facilita a priorização e planejamento incremental.
- Incentiva o foco na experiência do usuário.

#### Desvantagens:
- Pode faltar detalhes técnicos e ambiguidade na interpretação.
- Depende fortemente da comunicação constante com stakeholders.
- Necessita de critérios de aceitação bem definidos para testes.

---

## Especificação de Requisitos do Cenário do Grupo  
**Contexto:** Aplicativo de transporte com veículos autônomos.

### Requisito A – Técnica: Casos de Uso

**Título:** UC01 – Conformidade com normas de trânsito

**Ator Principal:** Sistema de controle de navegação autônoma

**Descrição:** Este caso de uso descreve a necessidade de os veículos autônomos seguirem todas as normas de trânsito estabelecidas no local de atuação (por exemplo, limites de velocidade, semáforos, sinalizações, faixas de pedestres).

**Fluxo Principal:**
1. O sistema identifica a localização atual do veículo.
2. O sistema carrega as normas de trânsito aplicáveis àquela localidade.
3. Durante a navegação, o sistema monitora as condições e aplica as normas em tempo real.
4. O sistema ajusta a velocidade, realiza paradas e manobras conforme a legislação local.
5. O trajeto é concluído com o veículo tendo obedecido integralmente às regras.

**Fluxos Alternativos:**
- 3a. Normas locais indisponíveis: o sistema emite alerta e adota velocidade de segurança mínima.

---

### Requisito B – Técnica: História de Usuário

**História de Usuário:**
Como um usuário do aplicativo,  
eu quero cadastrar e selecionar endereços como "favoritos" (ex: Casa, Trabalho),  
para facilitar a solicitação de viagens futuras sem precisar digitar o endereço novamente.

**Critérios de Aceitação:**
- O usuário pode adicionar um endereço aos favoritos com um nome personalizado.
- Os favoritos ficam salvos na conta do usuário.
- Ao solicitar uma viagem, o usuário pode escolher um destino diretamente da lista de favoritos.
- O sistema permite editar ou remover endereços favoritos.
