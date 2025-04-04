Aqui está um **template em Markdown** integrando as sete técnicas para definição de escopo de projetos. Cada técnica tem sua seção individual, e no final há um **exemplo consolidado** combinando todas.

# 📌 Template de Definição de Escopo de Projeto

## 📍 1. Escopo SMART
> **Objetivo:** Definir um escopo claro e mensurável.

- **Específico (Specific):** Desenvolver um sistema web para agendamento de consultas médicas.
- **Mensurável (Measurable):** O sistema deve suportar 10.000 usuários e processar agendamentos em menos de 2 segundos.
- **Alcançável (Achievable):** Utilizar tecnologia web escalável com banco de dados otimizado.
- **Relevante (Relevant):** Alinhado à estratégia da empresa para digitalizar processos.
- **Prazo (Time-bound):** Entrega do MVP em 6 meses.

---
## 📍 2. Priorização MOSCOW
> **Objetivo:** Determinar o que é essencial e o que pode ser adiado.

- **Must-have (Obrigatório)** ✅
  - Cadastro de pacientes e médicos.
  - Agendamento e cancelamento de consultas.
  - Notificações via e-mail.

- **Should-have (Importante, mas não essencial)** 🔜
  - Chat entre pacientes e médicos.
  - Relatórios de histórico de consultas.

- **Could-have (Desejável, mas opcional)** 🤔
  - Suporte a múltiplos idiomas.
  - Dark mode na interface.

- **Won’t-have (Fora do escopo)** ❌
  - Integração com operadoras de saúde nesta fase.

---
## 📍 3. User Stories + Critérios de Aceitação (INVEST)
> **Objetivo:** Definir requisitos do usuário de forma detalhada.

📌 **User Story:**  
*"Como um paciente, quero agendar consultas online para evitar filas e economizar tempo."*

✅ **Critérios de Aceitação:**  
- O paciente pode escolher médicos disponíveis por data e horário.  
- O sistema envia confirmação por e-mail e SMS.  
- O paciente pode visualizar seu histórico de agendamentos.

---
## 📍 4. Matriz de Responsabilidades (RACI)
> **Objetivo:** Definir claramente as responsabilidades no projeto.

| Atividade                      | R (Responsible) | A (Accountable) | C (Consulted) | I (Informed) |
|--------------------------------|----------------|----------------|--------------|-------------|
| Desenvolvimento do Frontend    | Dev Team       | PM             | UX Designer  | Cliente     |
| Desenvolvimento do Backend     | Dev Team       | Tech Lead      | Arquitetos   | Cliente     |
| Testes e QA                    | QA Team        | PM             | Dev Team     | Cliente     |

---
## 📍 5. Inclusões e Exclusões no Escopo
> **Objetivo:** Especificar claramente o que está e o que não está no projeto.

✅ **Inclusões:**  
- Desenvolvimento do sistema de agendamentos.  
- Implementação de login seguro (OAuth).  
- Envio de notificações automáticas.  

❌ **Exclusões:**  
- Integração com sistemas legados.  
- Pagamentos online nesta versão.  

---
## 📍 6. Estrutura Gelkwin (Gerar, Especificar, Limitar + Keep, Win, Improve, Negotiate)
> **Objetivo:** Estruturar o escopo considerando melhorias e negociações.

### **📌 GEL (Gerar, Especificar, Limitar)**
- **Gerar:** O sistema precisa permitir agendamentos ágeis e seguros.  
- **Especificar:** O agendamento será validado por um token e armazenado no banco.  
- **Limitar:** O sistema não terá suporte para múltiplas clínicas inicialmente.  

### **📌 KWIN (Keep, Win, Improve, Negotiate)**
- **Keep:** Manter a estrutura de login já utilizada em outros sistemas da empresa.  
- **Win:** Reduzir cancelamentos de consultas em 30% com notificações.  
- **Improve:** Melhorar o UX para facilitar marcação de consultas via mobile.  
- **Negotiate:** A integração com plano de saúde pode ser incluída em uma fase futura.  

---

## 📍 7. Exemplo Consolidado (Integrando as 7 Técnicas)
### 🔷 Definição Completa do Escopo do Projeto "Sistema de Agendamento Médico"
> **Objetivo:** Criar um sistema escalável para agendamento de consultas médicas.

### 🎯 **Escopo SMART**
- **Objetivo:** Criar um sistema web para agendamento de consultas médicas.
- **Métrica:** 10.000 usuários, tempo de resposta < 2s.
- **Relevância:** Digitalização de processos.
- **Prazo:** MVP em 6 meses.

### 📊 **Priorização MOSCOW**
- **Must-have:** Login, agendamento, notificações.
- **Should-have:** Chat, relatórios.
- **Could-have:** Dark mode, multi-idioma.
- **Won’t-have:** Integração com planos de saúde nesta fase.

### 👤 **User Story + Critérios de Aceitação**
- "Como um paciente, quero agendar consultas online para evitar filas e economizar tempo."
- **Critérios:** Escolha de médicos, notificações confirmadas, histórico acessível.

### 🏗 **Matriz RACI**
| Atividade                | R | A | C | I |
|--------------------------|---|---|---|---|
| Frontend (UI/UX)        | Dev Team | PM | UX | Cliente |
| Backend (APIs)          | Dev Team | Tech Lead | Arquitetos | Cliente |
| Testes (QA)             | QA Team | PM | Dev Team | Cliente |

### ⚖ **Inclusões e Exclusões**
✅ **Inclusões:** Agendamentos, notificações, login seguro.  
❌ **Exclusões:** Pagamentos online, integração com convênios.  

### 🔄 **Estrutura Gelkwin**
**GEL:**  
- Gerar: Criar um sistema de consultas online.  
- Especificar: Funcionalidade de marcação e cancelamento.  
- Limitar: Sem integração com outros hospitais inicialmente.  

**KWIN:**  
- **Keep:** Login via Google OAuth.  
- **Win:** Reduzir cancelamentos de consulta em 30%.  
- **Improve:** Melhor UX mobile.  
- **Negotiate:** Integração futura com planos de saúde.  

---
### 🚀 **Conclusão**
Este template fornece um **modelo completo** de definição de escopo de projetos utilizando múltiplas técnicas complementares. Ele pode ser adaptado conforme necessário, combinando a clareza do **SMART**, a priorização do **MOSCOW**, a estruturação do **INVEST**, a organização do **RACI**, a transparência das **Inclusões/Exclusões** e a flexibilidade estratégica do **Gelkwin**.

