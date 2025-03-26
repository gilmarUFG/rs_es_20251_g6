## 🎯 Mural - Processo de Engenharia de Requisitos
---
## Definição de Engenharia de Requisitos
- Engenharia de Requisitos é o processo de definição,
documentação e gestão dos requisitos de um sistema.
  ![IMG1](https://engsoftmoderna.info/figs/cap3/requisitos.svg)

## Etapas do Processo de Engenharia de Requisitos

### 1️⃣ Elicitação de Requisitos
- Elicitar requisitos é o processo de identificar, coletar e entender as necessidades dos usuários e stakeholders para o desenvolvimento de software.
#### Fontes de Requisitos
- **Stakeholders**: Clientes, usuários, gerentes e outros envolvidos no projeto.
- **Documentação existente**: Manuais e sistemas anteriores.

#### Técnicas para Elicitação de Requisitos
- **Entrevista**: Conversas diretas com stakeholders para entender suas necessidades.
- **Questionários**: Formulários para coletar informações.
- **Análise de documentos**: Revisão de materiais existentes para extrair requisitos.
  ![IMG2](https://slideplayer.com.br/slide/2262775/8/images/19/T%C3%A9cnicas+Espec%C3%ADficas+de+Elicita%C3%A7%C3%A3o.jpg)

<hr/>

### 2️⃣ Análise de Requisitos
- A análise de requisitos representa o processo de refinamento dos requisitos coletados durante a elicitação. Durante essa etapa, são feitas inspeções nos requisitos coletados, em busca de erros e deficiências a serem corrigidas; é feita a decomposição de requisitos de alto nível em requisitos com maiores níveis de detalhe, conforme a necessidade técnica do requisito; a avaliação de viabilidade de implementação, construção de protótipos e negociação dos requisitos prioritários. O objetivo final é gerar um conjunto de requisitos com precisão e detalhamento suficiente para ser usado na base de cálculo do cronograma e do orçamento.

#### Modelagem dos Requisitos
- Uma das bases para a devida inspeção e compreensão dos requisitos entre os desenvolvedores e os usuários é a correta e diversificada modelagem do requisito. Nesse contexto, os requisitos possuem várias formas de representação de modo a favorecer análises em diferentes perspectivas, como na descrição por meio da linguagem natural:
<br/><br/>
**RF1: O sistema deve permitir os usuários realizarem login inserindo suas credenciais como nome de usuário e senha.**
<br/><br/>
Que também pode ser representado por meio de um protótipo de interface gráfica que o usuário consiga confirmar a conformidade de acordo com suas necessidades:
<br/><br/>
![Screenshot 2025-03-24 at 23-33-11 Login - Autenticação UFG](https://github.com/user-attachments/assets/d3bb51e3-5abc-4ad7-b2d4-82866d55a7b5)
<br/><br/>
Ou, em uma representação de mais baixo nível, com mais detalhes de implementação, pode ser modelado como no diagrama de sequência abaixo:
<br/><br/>
![DiagramaDeLogin](https://github.com/user-attachments/assets/aada078b-08d3-4063-89ed-8979f69e23c7)
<hr/>


### 3️⃣ Especificação de Requisitos
 - O objetivo principal dessa etapa é criar um documento com o nível de detalhamento correspondente dos requisitos. Este documento conterá todos os requisitos que devem ser impostos ao projeto e verificação do produto. Ele também conterá outras informações relacionadas necessárias para o projeto, verificação e manutenção do produto.

- A especificação de requisitos também é conhecida como documentação, é um processo de anotar todos os requisitos do sistema e do usuário na forma de um documento. Esses requisitos devem ser claros, completos, abrangentes e consistentes. 

- No próprio documento, podemos encontrar diagramas UML, casos de uso, conforme abaixo:
  
## Diagrama de casos de uso
![Diagrama sem nome drawio (3)](https://github.com/user-attachments/assets/0ae5db1a-2373-4a48-96b7-339d9d71763c)


### 4️⃣ Validação dos Requisitos  
A **Validação de Requisitos** é a etapa que assegura que os requisitos coletados e especificados atendem às necessidades dos stakeholders e são viáveis para implementação. O objetivo principal é identificar erros, inconsistências, ambiguidades ou lacunas antes que o desenvolvimento do sistema inicie, reduzindo retrabalho e custos.  

#### Técnicas de Validação  
- **Revisões**: Análises detalhadas dos requisitos por especialistas e stakeholders.  
- **Prototipação**: Criação de modelos ou versões preliminares do sistema para validar a compreensão dos requisitos.  
- **Casos de Teste**: Geração de cenários que verificam se os requisitos são testáveis e bem definidos.  
- **Rastreamento de Requisitos**: Uso de matrizes para garantir que cada requisito esteja devidamente ligado a um objetivo do sistema.  

#### Benefícios da Validação  
- Garante que os requisitos refletem corretamente as necessidades do usuário.  
- Reduz falhas e retrabalho ao longo do desenvolvimento.  
- Assegura que o projeto atenda aos padrões de qualidade.  


### 5️⃣ Gerenciamento dos Requisitos
O **Gerenciamento de Requisitos** é um processo essencial no desenvolvimento de software, garantindo que as necessidades dos stakeholders sejam bem definidas, documentadas, rastreadas e controladas durante todo o ciclo de vida do projeto.

## Componentes Principais
- **Elicitação**: Identificação das necessidades dos stakeholders. Exemplo: No SIGAA, alunos e professores precisam acessar informações acadêmicas de forma intuitiva.

![IMG4](https://github.com/user-attachments/assets/5766353f-fb0d-4295-a6a3-f57dc27470d8)

  
- **Documentação**: Registro formal dos requisitos.
- **Validação**: Revisão e testes dos requisitos.
- **Gerenciamento de Mudanças**: Controle de alterações. Exemplo: Atualizações no SIGAA para novas diretrizes acadêmicas.
- **Rastreamento**: Monitoramento do impacto dos requisitos.

## Importância do Gerenciamento de Requisitos

- **Minimiza riscos** ao evitar ambiguidades e falhas de comunicação.
- **Garante alinhamento** entre as partes interessadas e a equipe de desenvolvimento.
- **Facilita a manutenção e evolução do software** ao longo do tempo.
- **Melhora a qualidade do produto final**, reduzindo retrabalho e custos adicionais.

## Atores Envolvidos
- **Clientes e Usuários**: Definem necessidades.
- **Analistas**: Documentam e gerenciam requisitos.
- **Desenvolvedores**: Implementam os requisitos.
- **Gerentes de Projeto**: Monitoram o progresso.
- **Testadores**: Validam os requisitos. 

![IMG5](https://github.com/user-attachments/assets/03014530-56b6-4c1b-9c8d-16caba2cf0ec)


## Ferramentas e Boas Práticas
- Uso de **Jira, IBM DOORS, Azure DevOps**.
- Definição clara dos requisitos.
- Revisões periódicas. Exemplo: O SIGAA passa por revisões constantes para atender novas demandas institucionais.

O gerenciamento eficaz de requisitos garante alinhamento entre expectativas e entrega da solução.
<hr/>
