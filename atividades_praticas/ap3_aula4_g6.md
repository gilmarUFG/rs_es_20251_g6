# Descrição
1. &nbsp;&nbsp;Ao entrar na interface gráfica do sigaa, encontrada no site https://sigaa.sistemas.ufg.br, o usuário terá acesso aos campos de inserção do login único ou CPF, senha e CAPTCHA para verificação de acessos por bot (RNF1).
2. &nbsp;&nbsp;Ao preencher os campos e submeter o formulário de login, os dados são verificados pela aplicação e caso estejam válidos, o usuário tem acesso ao sistema pós login. Caso os dados estejam inválidos, o usuário é informado com uma mensagem de erro.
3. &nbsp;&nbsp;Caso o login seja bem sucedido, o login será persistido no navegador do usuário durante determinado período (RNF3).
Como

O login é realizado através de uma interface web responsiva, onde o usuário preenche os campos de login e senha. A autenticação é feita por meio de uma requisição ao servidor, que valida as credenciais e retorna o status da autenticação.

### Onde

O acesso ao sistema é realizado através do portal SIGAA (https://sigaa.sistemas.ufg.br) e pode ser acessado por meio de navegadores web em dispositivos desktop ou móveis.

### Quando

O login deve ser realizado sempre que um usuário desejar acessar os serviços oferecidos pelo SIGAA. Dependendo da configuração de sessão, um novo login pode ser necessário após um período de inatividade.

### Quem

Os usuários que podem acessar a tela de login incluem estudantes, docentes, coordenadores e técnicos administrativos da instituição.

### O quê

O requisito de login define o processo de autenticação de usuários, garantindo a segurança e o controle de acesso ao sistema SIGAA.

### Por quê

O login é necessário para garantir que apenas usuários autorizados tenham acesso ao sistema, protegendo informações sensíveis e assegurando a integridade dos dados acadêmicos e administrativos.

# Fontes de requisitos
Brainstorm, engenharia reversa e entrevisa com usuários.

# Fluxo de execução
![Diagrama sem nome drawio (1)](https://github.com/user-attachments/assets/acb82709-3e8d-4f34-a7e7-59fbceb9a0e2)

# Perfis de usuário com permisão de execução
Estudantes, docentes, coordenadores e técnicos administrativos da instituição devem ter acesso a tela de login.
