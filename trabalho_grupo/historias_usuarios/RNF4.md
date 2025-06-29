# RNF4 - Tolerância a Falhas de Conexão

## Narrativa

-   **Como** um usuário do sistema,
-   **Eu quero**  que o sistema continue funcionando mesmo com instabilidade na rede,
-   **Para** que não haja atrasos na viagem.

## Cenários:

### Cenário 1: Operação Offline com Sincronização Posterior

-   **Quando**  o usuário e o sistema embarcado estão em uma área com conexão instável,
-   **E**  a conexão falhar durante o envio de dados,
-   **Então** o sistema deve armazenar os dados localmente e sincronizá-los automaticamente quando a conexão for restabelecida,
-   **Resultado para a qualidade do sistema:**  Para evitar que dados sejam perdidos ou ocorram insconsistencias quando for necessário usá-los


### Cenário 2: Recuperação após queda brusca de conexão

-   **Quando**  o sistema está consultando o trajeto antes de solicitar embarque do passageiro,
-   **E** a conexão cair repentinamente,
-   **Então** o sistema deve avisar o usuário da instabilidade e dar um pequeno prazo para realizar uma nova tentativa,
-   **Resultado para a qualidade do sistema:** Não seja necessário a intervenção do usuário.

### Cenário 3: Notificação e alternativas em caso de falha

-   **Quando**  o usuário tenta acessar o aplicativo para solicitar uma viagem,
-   **E** o sistema detectar ausência de conectividade,
-   **Então** deve exibir uma mensagem clara sobre o problema e oferecer opções offline (ex.: acessar a FAC),
-   **Resultado para a qualidade do sistema:** Não bloquear outras funcionalidades que não dependam de rede.
