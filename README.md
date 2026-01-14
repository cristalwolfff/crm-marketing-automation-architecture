# ☀️ Solar Eco Solutions: CRM Architecture & Automation
*(Technical Case Study: Renewable Energy & Logistics)*

![Salesforce Marketing Cloud](https://img.shields.io/badge/Stack-Salesforce_Marketing_Cloud-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![Industry](https://img.shields.io/badge/Industry-Solar_Energy_&_Utilities-F2C94C?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-LTV_&_Logistics_Automation-4B275F?style=for-the-badge)

> **Projeto de arquitetura de CRM para gestão de ciclo de vida de clientes de Energia Solar.**
> *Foco: Onboarding, Adoção de App (Monitoramento de Energia) e Automação Logística de Instalação.*

---

## 🎯 O Desafio (The Challenge)
Desenhar uma arquitetura de CRM para a **Solar Eco Solutions** capaz de reduzir o "remorso pós-compra" (High Ticket), garantir o sucesso da instalação técnica e fomentar o uso do App de monitoramento de energia.

### 🚫 Restrições do Cenário (Constraints):
Para este case, trabalhei com limitações técnicas propositais para exercitar a **resolução de problemas com recursos fundamentais**:
1.  **Canal Único:** Comunicação restrita a **E-mail**, exigindo máxima relevância para garantir a taxa de abertura.
2.  **Sem IA Nativa:** Solução desenhada sem depender do *Salesforce Einstein* ou algoritmos preditivos ("Caixa Preta"), focando em **segmentação determinística** e lógica de negócios sólida.

---

## 🏗️ Arquitetura da Solução

### 1. Welcome Journey (Onboarding & Educação)
O objetivo não é apenas dar "oi", mas validar a compra complexa e iniciar a mudança de comportamento do cliente.
* **Estratégia Neural:** Uso de viés de confirmação para parabenizar pela "decisão inteligente" (economia financeira).
* **App Adoption:** Incentivo ao download do App para que o cliente monitore a geração de energia (o "ganho" real do produto).
- [📄 Ver Fluxos Visuais](./journey.pdf)
---

### 2. Jornada Logística (Tracking & Instalação)
Uma régua **desacoplada** focada exclusivamente na operação. O objetivo é reduzir o *No-Show* (cliente não estar em casa) e o volume de chamados no SAC.
* **Gatilhos:** Lembretes automáticos em T-3 e T-1 dia da instalação.
* **Gestão de Crise:** Fluxo automatizado para reagendamento em caso de falha na visita.
- [📄 Ver Fluxos Visuais](./logistica.pdf) 

---

## 📊 Estrutura de Dados & KPIs
A inteligência do projeto está na **Modelagem de Dados** (Data Extensions) que permite personalização avançada sem IA.

| KPI Estratégico | Meta de Negócio | Métrica Técnica |
| :--- | :--- | :--- |
| **Redução de OPEX** | Diminuir chamados no SAC sobre "quando é minha instalação?" | Taxa de Confirmação via E-mail |
| **App Stickybility** | Criar hábito de verificar a economia diária | Cliques no Link "Ver meu Gráfico de Economia" |
| **NPS & Lealdade** | Transformar economia em prova social | % de Promotores (Notas 9-10) convertidos em Reviews |

### 🛠️ Diferenciais Técnicos Implementados
* **SQL Automation:** Queries para tratamento de dados brutos e cálculo de datas (T-3, T-1) no Automation Studio.
* **AMPscript Avançado:** Personalização dinâmica do conteúdo do e-mail baseada no status da instalação.
* **CloudPages:** Criação de páginas de aterrissagem para captura de feedback (NPS) e confirmação de agendamento.

---

## 📂 Documentação Completa (Download)
Clique abaixo para acessar os arquivos originais com todo o detalhamento técnico:

- 📕 **[Ler Documentação Técnica Completa (PDF)](case_solar.pdf)**
- 🗺️ **[Ver Diagrama de Welcome (PDF)](journey.pdf)**
- 🚛 **[Ver Diagrama de Logística (PDF)](logistica.pdf)**

---
*Desenvolvido por [Cristalwolf](https://github.com/cristalwolfff)*
