# 📝 Técnicas para Especificação de Requisitos  
**Disciplina**: Engenharia de Requisitos  
**Cenário**: 4 (Sistema de Veículos Autônomos)  

---

## 1. 🛠️ Técnicas de Especificação  

### a) **User Stories (Histórias de Usuário)**  
**📌 Descrição**:  
Descrições curtas escritas na perspectiva do usuário, no formato:  
`"Como [papel], eu quero [objetivo] para que [benefício]."`  

**🎯 Cenários de Aplicação**:  
- Projetos ágeis com requisitos dinâmicos.  
- Captura de necessidades diretas do usuário final.  

**✅ Vantagens**:  
✔ Simples e intuitivas.  
✔ Facilitam a priorização.  
✔ Promovem colaboração.  

**❌ Desvantagens**:  
✖ Vagas sem critérios de aceitação.  
✖ Limitadas para requisitos técnicos complexos.  

---

### b) **Casos de Uso**  
**📌 Descrição**:  
Modelam interações entre atores (usuários/sistemas) e o sistema para atingir um objetivo, incluindo fluxos básicos e alternativos.  

**🎯 Cenários de Aplicação**:  
- Sistemas com interações bem definidas (ex: apps de transporte).  
- Detalhamento de cenários de sucesso e falhas.  

**✅ Vantagens**:  
✔ Abrangem comportamentos e regras de negócio.  
✔ Clarificam cenários alternativos.  

**❌ Desvantagens**:  
✖ Documentação mais extensa.  
✖ Pode ser excessivo para requisitos simples.  

---

## 2. 📋 Especificação de Requisitos do Cenário 4  

### **Requisito 1 (User Story)**  
**📜 Descrição**:  
`"Como passageiro, eu quero avaliar o serviço após a viagem e relatar problemas, para que a empresa possa melhorar a qualidade."`  

**🔹 Detalhamento**:  
| **Prioridade** | **Critérios de Aceitação** |  
|----------------|---------------------------|  
| Média          | 1. App exibe formulário de avaliação (1-5 estrelas + campo opcional). <br> 2. Relatos são enviados automaticamente ao suporte. <br> 3. Usuário recebe confirmação de envio. |  

---

### **Requisito 2 (Caso de Uso)**  
**🎬 Título**: Validação do Veículo via Código de Confirmação  

**🔸 Atores**: Passageiro, Sistema.  

**📊 Fluxos**:  
1. **Fluxo Básico**:  
   - Sistema gera código único e exibe no app e no veículo.  
   - Passageiro confere códigos.  
   - Se coincidirem → viagem inicia.  

2. **Fluxo Alternativo (Código Incorreto)**:  
   - Passageiro reporta inconsistência.  
   - Sistema cancela viagem e notifica a central.  

---

### ✨ **Justificativa das Técnicas**  
- **User Story**: Ideal para requisitos centrados no usuário (ex: feedback), com linguagem acessível.  
- **Caso de Uso**: Necessário para interações complexas com múltiplos cenários (ex: validação de segurança).  
