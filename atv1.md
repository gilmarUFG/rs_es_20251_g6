
#### Requisitos funcionais

|Id|Descrição|
|---|---|
|RF1|O sistema deve permitir ao usuário o login usando seu login único, ou CPF, e senha|
|RF2|O sistema deve permitir ao estudante o envio de atividades de extensão, incluindo seus detalhes como tipo de ação, descricação e data de realização|
|RF3|O sistema deve permitir o estudante solicitar em matrícula de turmas ofertadas para determinadas disciplinas|
|RF4|O sistema deve permitir o estudante consultar suas turmas em que há ou houve vínculo, permitindo a visualização de detalhes|
|RF5|O sistema deve ter suporte à multiplas linguagens|
|RF6|O sistema deve permitir upload de arquivos|

### Requisitos Não Funcionais

|Id|Descrição|
|---|---|
|RNF1|Incluir verificação de usuário bot, aumentando a segurança do login, por meio de captcha|
|RNF2|O sistema deve ser responsivo|
|RNF3|O login deve ser persistido no navegador do usuário durante determinado tempo|
|RNF4|O tamanho máximo dos arquivos de upload deve ser de 10mb|
|RNF5|Deve haver persistência automática dos formulários preenchidos pelo usuário enquanto não houver um "salvamento" definitivo|

### Regras de Negócio

|Id|Descrição|
|---|---|
|RN1|O sistema deve permitir que apenas professores tenham acesso ao controle de frequência|
|RN2|O sistema deve permitir ao coordenador do respectivo instituto, realizar o cadastramento de matérias|
|RN3|O aluno deve poder submeter a atividade na plataforma somente dentro do período estipulado pelo professor|
|RN4|Protocolo de cadastramento de aluno em matérias deve seguir índice de prioridade de cada aluno|
|RN5|O cancelamento de matrícula numa turma só pode ser feito dentro do prazo estipulado|