# 🚀 Sistema Automatizado de Gestão de Estoque & Analytics — Loja X

## 📌 Contexto e Escopo de Trabalho (Scope of Work)
Este projeto foi desenvolvido como uma solução prática de engenharia de dados, automação e *business intelligence* aplicada à realidade de um **pequeno comércio local** de varejo no segmento de dispositivos móveis. O objetivo principal foi mitigar a ausência de controle automatizado de fluxos de entradas/saídas e preencher a lacuna de indicadores estratégicos para a tomada de decisão gerencial em um negócio de bairro.

> **Nota:** Para fins de portfólio e conformidade com as diretrizes de privacidade de dados comerciais, o nome real da empresa foi omitido (adotando-se "Loja X"), preservando integralmente a lógica de negócios, o histórico analítico de vendas e a arquitetura técnica desenvolvida.

---

## 🎯 Objetivos do Projeto
*   **Centralização e Robustez:** Estruturar um repositório único, confiável e escalável para o histórico de movimentações, processando com alta performance um ecossistema com **mais de 3.000 células de cadastro de produtos**.
*   **Automação Logística & IA Operacional:** Desenvolver um controle de inventário inteligente que calcula saldos de forma automatizada e aciona tomadas de decisão internas em tempo real por meio de inteligência artificial.
*   **Business Intelligence (BI):** Consolidar um dashboard executivo para monitoramento de faturamento, ticket médio, comportamento de consumo e fluxos de horários de pico.
*   **Acessibilidade e Custo Zero:** Implementar a solução utilizando o ecossistema em nuvem do Google Sheets, garantindo custo zero de licenciamento para o **pequeno comerciante** e aplicando conceitos de *Data UX* (Experiência do Usuário com Dados) para operadores de qualquer nível de maturidade tecnológica.

---

## 🛠️ Arquitetura e Modelagem dos Dados
O sistema foi desenhado seguindo os princípios de modelagem de bancos de dados relacionais para garantir a consistência e a integridade referencial:

1. **Camada de Ingestão (Tabela Fato — Lançamentos):** Base unificada alimentada cronologicamente de forma operacional. Contém chaves exclusivas (IDs/SKUs de produtos), tipo de movimentação (*Entrada/Saída*), volumes, valores unitários, totais calculados e métodos de pagamento.
2. **Camada de Processamento (Tabelas Dimensão — Estoque):** Abas segmentadas por categoria (`Estoque Capa` e `Estoque Película`). Uma estrutura massiva para um comércio local, gerenciando **mais de 3.000 células de dados de SKUs específicos**, cruzando variáveis complexas (modelos de aparelhos *versus* atributos como cores e tipos de blindagem) via fórmulas dinâmicas e matriciais.
3. **Camada de Integração GenAI (SheetGPT):** Motor de Inteligência Artificial integrado via API que atua como um consultor de negócios analítico direto na planilha.
4. **Camada de Visualização (Dashboard Executivo):** Painel gerencial alimentado em tempo real, sintetizando dados brutos em métricas acionáveis.

---

## 💡 Regras de Negócio Otimizadas & Diferenciais Técnicos

### 🤖 1. Automação de Ações de Negócio via Inteligência Artificial (GenAI)
O maior diferencial técnico do sistema é a transição da análise passiva para a **ação automatizada voltada à equipe da loja**. Utilizando o `SheetGPT`, a planilha analisa o saldo atual de cada um dos produtos cadastrados e gera comandos textuais customizados de forma preditiva na coluna **"Ação Automatizada (IA)"**:
*   **Estoque Crítico (Qtd < 10):** Se o estoque de um item atinge o nível de segurança (abaixo de 10 unidades), a IA gera instantaneamente um alerta de atenção urgente focado no operador da loja para evitar a perda de vendas de balcão.
*   **Estoque Cheio / Oportunidade (Qtd > 20):** Se há excesso de um produto (acima de 20 unidades), imobilizando o capital do pequeno comércio, a IA cria automaticamente uma estratégia de oferta padronizada. Esse texto serve de guia de vendas para o funcionário oferecer no balcão ou disparar nas redes sociais (TikTok/Instagram) para girar o estoque rápido.
*   **Estoque Saudável:** O sistema valida o equilíbrio do inventário, sinalizando a estabilidade operacional do item.

### 🎨 2. Data UX e Redução de Carga Cognitiva (Formatação Condicional Dinâmica)
Para evitar que o responsável perca tempo lendo relatórios extensos, foi aplicada uma camada de **Experiência do Usuário (UX)** através de formatação condicional por palavras-chave na coluna de IA:
*   Alertas de **Reposição Crítica** acionam automaticamente preenchimentos em tons vermelhos (Urgência).
*   Gatilhos de **Estoque Cheio** ganham destaque em **verde claro**, incentivando o usuário e os vendedores a priorizarem as estratégias de vendas e promoções para esses produtos específicos.

### 🔍 3. Tratamento de Exceções e Eliminação de "Falsos Positivos"
Em vez de aplicar regras genéricas de coloração para células zeradas, as fórmulas matriciais foram configuradas para contextualizar o mercado de tecnologia. Modelos de smartphones que sabidamente não possuem fabricação de determinadas variações (ex: películas de cerâmica para modelos específicos) ignoram os alertas visuais de desabastecimento. Isso poupa a atenção do gestor do pequeno comércio, direcionando o foco apenas para o que realmente precisa ser comprado.

### 📅 4. Análise Temporal Sazonal
O dashboard consolida de forma automatizada e preditiva as janelas de horários de pico e a distribuição do volume de vendas por dia da semana (identificando a quinta-feira como o período de maior tráfego), otimizando a escala de funcionários e o planejamento logístico da empresa.

---

## 🚀 Como Visualizar e Interagir com o Projeto
Você pode explorar diretamente toda a engenharia de fórmulas, a árvore de SKUs com mais de 3.000 células cadastradas e a interface de IA acessando o link oficial do projeto:

🔗 Acesse o Projeto de Forma Interativa Clicando no Dashboard!
[![Acesse o Projeto de Forma Interativa](https://github.com/user-attachments/assets/a813d026-7a44-4630-a804-e7ee32a85017)](https://docs.google.com/spreadsheets/d/1DnY4iPnXM5w8HTaNlF9ycDwNeiHDSNcCR_t2HNPLl3I/edit?usp=sharing)
