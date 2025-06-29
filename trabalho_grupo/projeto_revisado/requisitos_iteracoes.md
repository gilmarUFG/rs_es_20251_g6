# Requisitos do Sistema de Veículos Autônomos

## Primeira Iteração (Core & Segurança Essencial)

**RF01 – Solicitação de Veículo Autônomo**  
O sistema deve permitir que o usuário solicite um veículo informando origem e destino, com validação de dados e atribuição automática de um veículo disponível.

**RF02 – Validação por Código de Confirmação**  
O embarque deve ser permitido apenas mediante código de confirmação correspondente entre o veículo e o aplicativo.

**RF05 – Detecção de Riscos**  
O veículo deve identificar riscos (obstáculos, pedestres, sinalização) e reagir para evitar acidentes. Deve alertar sobre limitações em condições climáticas adversas.

**RF06 – Cálculo de Rotas Otimizadas**  
Deve calcular e recalcular rotas com base em trâfego e clima, e usar dados anteriores em caso de falha de conexão.

**RF07 – Sistema de Geoposicionamento**  
Deve localizar usuário e destino com precisão, bloquear solicitação sem localização válida e atualizar a rota durante o trajeto.

**RF09 – Relato de Problemas Durante a Viagem**  
Deve oferecer canal de emergência e contato com a central, com transmissão de dados da viagem e protocolo automático em caso de falhas críticas.

**RF10 – Detecção de Baixa Carga**  
Deve remover da frota veículos com baixa carga, verificar autonomia antes da corrida e alertar a central em caso de carga crítica.

## Segunda Iteração (Melhorias e Experiência do Usuário)

**RF03 – Central de Ajuda**  
O app deve incluir FAQs por categoria, busca por temas e opções de contato com o suporte.

**RF04 – Comunicação via Voz**  
O sistema deve fornecer instruções faladas, responder comandos por voz e adaptar o áudio ao ambiente. Deve haver alternativa visual em caso de falha.

**RF08 – Avaliação do Serviço**  
Após a viagem, o usuário pode avaliar o serviço com nota e comentário, inclusive relatando incidentes prioritários.

