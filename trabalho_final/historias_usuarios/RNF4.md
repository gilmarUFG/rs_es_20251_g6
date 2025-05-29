História de Usuário
RNF4: Tolerância a Falhas de Conexão
Como um usuário do sistema,
Eu quero que o sistema continue funcionando mesmo com instabilidade na rede,
Para que não haja atrasos na viagem.

Cenários
Cenário 1: Operação Offline com Sincronização Posterior
Dado que o usuário e o sistema enbarcado estão em uma área com conexão instável,
Quando a conexão falhar durante o envio de dados,
Então o sistema deve armazenar os dados localmente,
E sincronizá-los automaticamente quando a conexão for restabelecida,


Cenário 2: Recuperação após queda brusca de conexão
Dado que o sistema está consultando o trajeto antes de solicitar embarque do passageiro,
Quando a conexão cair repentinamente,
Então o sistema deve avisar o usuário da instabilidade e dar um pequeno prazo para realizar uma nova tentativa,
Sem haja a necessidade do usuário intervir.

Cenário 3: Notificação e alternativas em caso de falha
Dado que o usuário tenta acessar o aplicativo para solicitar uma viagem,
Quando o sistema detectar ausência de conectividade,
Então deve exibir uma mensagem clara sobre o problema,
E oferecer opções offline (ex.: acessar a FAC),
Sem bloquear outras funcionalidades que não dependam de rede.
