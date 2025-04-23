## TÉCNICAS PARA ESPECIFICAÇÃO DE REQUISITOS
### PARTE 1 - ANÁLISE DE TÉCNICAS DE ESPECIFICAÇÃO
### TÉCNICA 1: HISTÓRIAS DE USUÁRIO
* * *

> **O QUE É:**
> 
> Técnica ágil que descreve requisitos no formato "Como [tipo de usuário], eu quero [objetivo] para que [benefício]".

| QUANDO APLICAR | 
|:---------------|
| ✓ Projetos ágeis (Scrum, XP) |
| ✓ Sistemas centrados no usuário |
| ✓ Requisitos que precisam ser capturados rapidamente |

### PONTOS POSITIVOS (+)
* Fácil compreensão por stakeholders
* Foco no valor para o usuário
* Flexibilidade e adaptabilidade

### PONTOS NEGATIVOS (-)
* Pode ser vaga para requisitos complexos
* Nem sempre captura requisitos não-funcionais adequadamente
* Requer complementação com critérios de aceitação

---

### TÉCNICA 2: CASOS DE USO
* * *

> **O QUE É:**
> 
> Documentação estruturada que detalha interações entre sistema e atores para atingir um objetivo específico.

| QUANDO APLICAR |
|:---------------|
| ✓ Sistemas com fluxos de interação complexos |
| ✓ Quando é necessário documentação detalhada |
| ✓ Processos de desenvolvimento tradicionais |

### PONTOS POSITIVOS (+)
* Captura fluxos principais, alternativos e exceções
* Boa base para casos de teste
* Facilita rastreabilidade

### PONTOS NEGATIVOS (-)
* Processo burocrático e demorado
* Difícil manter atualizado em ambientes de mudança rápida
* Pode ser complexo para stakeholders não técnicos

---

### PARTE 2 - APLICAÇÃO PRÁTICA NO CENÁRIO DE VEÍCULOS AUTÔNOMOS
### REQUISITO A: SISTEMA DE SEGURANÇA VEICULAR PROATIVA
### Especificado via CASOS DE USO

```
IDENTIFICADOR: UC001 - Sistema de Detecção de Riscos e Prevenção de Acidentes
```

**DESCRIÇÃO GERAL:**  
O sistema identifica riscos no ambiente e toma ações preventivas.

**ATORES ENVOLVIDOS:**  
Veículo autônomo, outros veículos, pedestres, obstáculos

**PRÉ-REQUISITOS:**
- [x] Veículo em operação
- [x] Sensores funcionando
- [x] Sistema de navegação ativo

**SEQUÊNCIA PRINCIPAL:**
1.  Sistema monitora ambiente com sensores
2. Processa dados para identificar objetos
3. Analisa trajetórias e comportamentos
4. Calcula probabilidade de risco
5. Se detectar risco:
   - Alerta passageiro
   - Calcula ação evasiva
   - Executa ação preventiva
     
6️. Registra evento para análise

**CAMINHOS ALTERNATIVOS:**  
◻️ Para riscos de baixa severidade: ajuste suave sem alerta  
◻️ Múltiplos riscos: prioriza por severidade

**CAMINHOS DE EXCEÇÃO:**  
⚠️ Falha em sensores: avalia operação segura ou para  
⚠️ Ação preventiva impossível: busca alternativa ou minimiza danos

**ESTADO FINAL:**  
◽ Operação segura continua  
◽ Dados enviados para aprimoramento

---

## REQUISITO B: SISTEMA DE MONITORAMENTO DE ESTADO DO VEÍCULO
### Especificado via HISTÓRIA DE USUÁRIO

```
HISTÓRIA PRINCIPAL:
```

> 📝 Como gestor do sistema, quero que o sistema identifique quando um veículo precisa ser recarregado e o remova da lista de disponíveis, para que usuários nunca sejam atendidos por veículos com carga insuficiente.

### CRITÉRIOS DE ACEITAÇÃO:

▶️ **MONITORAMENTO DE ENERGIA**
* Sistema monitora nível de energia continuamente
* Calcula autonomia restante considerando condições operacionais

▶️ **ANÁLISE DE DISPONIBILIDADE**
* Veículo deve ter pelo menos 20% de carga acima do necessário para viagem máxima
* Veículos abaixo do limiar não aparecem como disponíveis

▶️ **REDIRECIONAMENTO PARA RECARGA**
* Veículos no limiar são automaticamente direcionados para recarga
* Rota otimizada considerando carga atual

▶️ **REINTEGRAÇÃO AO SISTEMA**
* Após recarga, veículo volta a ser listado como disponível
* Distribuição otimizada para cobertura geográfica

▶️ **SEGURANÇA**
* Métodos redundantes para verificação do nível de energia
* Modo de segurança em caso de falha total
