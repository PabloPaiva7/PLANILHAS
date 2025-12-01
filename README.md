# 🚀 Sistema de Gestão Inteligente com Google Apps Script

> Transformando planilhas estáticas em Aplicações Web dinâmicas, seguras e focadas em Business Intelligence.

Este projeto demonstra como utilizar o ecossistema Google (Sheets + Apps Script) para criar um **ERP/CRM personalizado de baixo custo**, eliminando a necessidade de licenças de software caras e oferecendo uma experiência de usuário (UX) profissional.

---

## 🎯 O Que Foi Desenvolvido?

O sistema é dividido em duas frentes de atuação:

### 1. Front-end Administrativo (Web App)
Uma interface web moderna (SPA - Single Page Application) que roda no navegador, ocultando a planilha bruta do usuário final.
- **Login Seguro:** Controle de acesso simples.
- **Dashboard Executivo:** KPIs em tempo real (Ticket Médio, Taxa de Cancelamento, Faturamento).
- **Gráficos Interativos:** Visualização de dados com Chart.js.
- **CRUD Completo:** Formulários para inserção de dados com validação, evitando erros de digitação.

### 2. Automação Operacional (Add-on Interno)
Um menu personalizado ("Utilitários") dentro do Google Sheets para a equipe operacional.
- **Sidebar de Busca:** Localização instantânea de clientes/contratos.
- **Formatação Condicional Automática:** Script que destaca inadimplência ou altos valores.
- **Relatórios Rápidos:** Geração de resumos de status com um clique.

---

## 🛠️ Tecnologias Utilizadas

O projeto utiliza uma arquitetura **Serverless** baseada no Google Cloud:

*   **Backend:** Google Apps Script (JavaScript Cloud).
*   **Database:** Google Sheets (Atuando como Banco de Dados Relacional).
*   **Frontend:** HTML5, CSS3.
*   **Frameworks & Libs:**
    *   🎨 **Bootstrap 5:** Para responsividade e design moderno.
    *   📊 **Chart.js:** Para inteligência de dados visual.
    *   📅 **DataTables:** Para tabelas avançadas com busca e paginação.
    *   🔔 **SweetAlert2:** Para alertas e feedbacks visuais elegantes.

---

## 🧠 Conceitos de Administração Aplicados

Este sistema não é apenas código; é **Gestão Aplicada**:

1.  **Business Intelligence (BI):** Transformação de dados brutos (linhas da planilha) em informação estratégica (Gráficos de Pizza, Barras e KPIs).
2.  **Gestão à Vista:** O Dashboard permite que tomadores de decisão vejam a saúde do negócio em segundos.
3.  **Gestão de Risco:** Ao tirar o acesso direto à planilha e usar formulários web, eliminamos o risco de exclusão acidental de dados (DLP - Data Loss Prevention).
4.  **Padronização de Processos:** O uso de dropdowns e máscaras de input garante a integridade dos dados (Data Quality).

---

## ⏳ Impacto e Economia de Tempo

A implementação desta tecnologia gera um ROI (Retorno sobre Investimento) imediato na operação:

| Processo Antigo (Manual) | Novo Processo (Automatizado) | Economia Estimada |
| :--- | :--- | :--- |
| **Buscar um Contrato** | `Ctrl+F` manual, rolagem infinita, risco visual. | **Sidebar de Busca:** Digite e Enter. O sistema acha e pinta a linha. | **~90% mais rápido** |
| **Relatórios Gerenciais** | Copiar dados, criar Tabela Dinâmica, ajustar gráficos. | **Dashboard Web:** Atualizado em tempo real automaticamente. | **100% (Instantâneo)** |
| **Cadastro de Venda** | Digitação livre (erros de R$, datas, nomes). | **Formulário Web:** Campos validados e padronizados. | **Redução drástica de retrabalho** |

---

## 📈 Melhoria nos Processos Internos

1.  **Segurança da Informação:** O usuário final não precisa ter permissão de edição na planilha inteira, apenas acesso ao Web App.
2.  **Acessibilidade Mobile:** O sistema web é responsivo, permitindo que vendedores ou gestores consultem dados pelo celular, fora do escritório.
3.  **Foco no Core Business:** A equipe para de perder tempo "arrumando planilha" e passa a gastar tempo "analisando resultados".

---

## 📂 Estrutura do Repositório

*   `VENDAS - VENDAS.csv`: Exemplo da estrutura de banco de dados utilizada.
*   `script código.pdf`: Documentação técnica dos scripts desenvolvidos (Backend e Frontend).
*   `planilhas ideias.pdf`: Conceitos e wireframes das soluções.

---

By [PabloPaiva7](https://github.com/PabloPaiva7)
