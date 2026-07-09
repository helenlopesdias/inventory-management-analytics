https://github.com/user-attachments/assets/1232570c-1f33-469c-91b1-1c18378354c4
# Sistema Automatizado de Gestão de Estoque & Analytics - Loja X

## 📌 Contexto do Projeto

Este projeto foi desenvolvido como uma solução prática de análise de dados, automação e business intelligence aplicada à realidade de um comércio local do segmento de dispositivos móveis.

O objetivo foi solucionar problemas relacionados ao controle de estoque, registro de vendas e geração de informações para tomada de decisão, substituindo processos manuais por uma solução estruturada, acessível e orientada por dados.

> **Nota:** Para preservar a privacidade do negócio, o nome da empresa foi omitido e substituído por "Loja X". Todos os dados, regras de negócio e funcionalidades apresentados refletem a solução real desenvolvida.

---

## 🎯 Objetivos do Projeto

- Centralizar o controle de entradas e saídas de produtos em uma única plataforma.
- Estruturar e organizar uma base com mais de 3.500 células relacionadas ao cadastro e controle de produtos.
- Automatizar a identificação de itens que precisam de reposição.
- Desenvolver indicadores para acompanhamento de vendas e desempenho do negócio.
- Implementar uma solução de baixo custo utilizando Google Sheets e Inteligência Artificial Generativa.

---

## 🛠️ Estrutura da Solução

### 1️⃣ Registro de Movimentações

Base responsável pelo registro de todas as entradas e saídas de produtos, contendo:

- ID do produto
- Tipo de movimentação
- Quantidade
- Valores unitários e totais
- Forma de pagamento
- Data e horário das operações

---

### 2️⃣ Controle de Estoque

Abas dedicadas ao gerenciamento do estoque de capas e películas.

A estrutura foi desenvolvida para controlar milhares de combinações de produtos, considerando:

- Modelos de aparelhos
- Cores
- Tipos de películas
- Tipos de capas
- Quantidades disponíveis

Foram utilizadas fórmulas dinâmicas, validações de dados e automações para garantir maior confiabilidade dos registros.

---

### 3️⃣ Integração com Inteligência Artificial

O projeto utiliza a extensão SheetGPT integrada ao Google Sheets para analisar os níveis de estoque e gerar recomendações automáticas.

Com base nas quantidades disponíveis, a IA é capaz de:

- Identificar produtos com estoque crítico.
- Recomendar reposição de itens.
- Sugerir ações para produtos com excesso de estoque.
- Auxiliar a tomada de decisão de forma rápida e prática.

> [!IMPORTANT]
> **Observação sobre a versão pública do projeto**
>
> A versão original utilizada pela Loja X conta com integração ativa da extensão **SheetGPT**, responsável por gerar automaticamente as recomendações da coluna **"Lista de Reposição (IA)"**.
>
> Como a licença da extensão possui prazo de validade e não está disponível nesta versão pública, foi necessário preservar uma cópia dos resultados gerados na implementação original.
>
> Dessa forma, a coluna **"Lista de Reposição (IA)"** apresenta exemplos reais de recomendações produzidas pela integração com IA, porém não realiza atualizações automáticas nesta versão disponibilizada para demonstração e portfólio.


---

### 4️⃣ Dashboard Gerencial

Painel desenvolvido para transformar dados operacionais em informações estratégicas.

Principais indicadores:

- Faturamento
- Ticket médio
- Quantidade de vendas
- Produtos mais vendidos
- Formas de pagamento mais utilizadas
- Horários de maior movimento
- Dias da semana com maior volume de vendas

---

## 💡 Principais Funcionalidades

### 🤖 Automação da Lista de Reposição

Antes da implementação da solução, a identificação de produtos para reposição era realizada manualmente, consumindo até dois dias de trabalho.

Com a integração entre Google Sheets e IA Generativa, o processo passou a ser realizado automaticamente, reduzindo significativamente o tempo necessário para análise.

---

### ✅ Validação e Qualidade dos Dados

Foram implementadas regras de validação para reduzir erros de preenchimento e garantir maior consistência das informações registradas.

---

### 🎨 Alertas Visuais

O sistema utiliza formatação condicional para destacar automaticamente situações importantes:

- Estoque crítico
- Produtos em excesso
- Oportunidades de reposição

Isso permite uma análise rápida mesmo para usuários sem conhecimento técnico.

---

### 📊 Análise de Comportamento de Vendas

A solução identifica padrões de vendas e períodos de maior movimento, apoiando decisões relacionadas a estoque, compras e operação da loja.

---

## 📈 Resultados Obtidos

- Redução do tempo de geração da lista de reposição de até 2 dias para poucos minutos.
- Centralização do controle de estoque e vendas em uma única plataforma.
- Padronização do cadastro e acompanhamento dos produtos.
- Maior confiabilidade dos dados utilizados na operação.
- Criação de indicadores para suporte à tomada de decisão.
- Implementação de uma solução acessível e de baixo custo para um pequeno negócio.

---

<a href="https://docs.google.com/spreadsheets/d/1DnY4iPnXM5w8HTaNlF9ycDwNeiHDSNcCR_t2HNPLl3I/edit?usp=sharing" target="_blank">
  <img width="1294" height="498" alt="Dashboard Sistema Automatizado de Gestão de Estoque" src="https://github.com/user-attachments/assets/22885cb0-b80e-481c-a8f4-fac3257e70a5">
</a>

### [Clique aqui para acessar o Dashboard Interativo e navegar pelos dados](https://docs.google.com/spreadsheets/d/1DnY4iPnXM5w8HTaNlF9ycDwNeiHDSNcCR_t2HNPLl3I/edit?usp=sharing)
