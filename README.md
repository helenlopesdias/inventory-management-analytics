# Sistema Automatizado de Gestão de Estoque & Analytics — Loja X

## 📌 Contexto e Escopo de Trabalho (Scope of Work)
Este projeto foi desenvolvido como uma solução de engenharia de dados e business intelligence aplicada a um cenário real de varejo no segmento de dispositivos móveis. O objetivo foi resolver a ausência de controle automatizado de entradas/saídas e a falta de indicadores estratégicos para a tomada de decisão da gerência.

*Nota: Para fins de portfólio e conformidade com a privacidade de dados comerciais, o nome real da empresa foi omitido (adotando-se "Loja X"), preservando integralmente os dados analíticos de um período de 7 dias de vendas, a lógica de negócios e a arquitetura técnica do sistema.*

### 🎯 Objetivos do Projeto
- **Centralização:** Criar um repositório único, estruturado e confiável para o histórico de movimentações da loja.
- **Automação de Estoque:** Desenvolver um controle de inventário inteligente que calcula saldos de forma automatizada e sinaliza alertas visuais de reposição.
- **Business Intelligence:** Estruturar um dashboard executivo para monitoramento de faturamento, ticket médio, comportamento de consumo e fluxos de horários de pico.
- **Acessibilidade e Custo Zero:** Implementar a solução utilizando o **Google Sheets**, garantindo operação em nuvem sem custos de licença para o cliente e com foco em UX (User Experience) para operadores com baixa maturidade tecnológica.

---

## Arquitetura e Modelagem dos Dados

O sistema foi desenhado seguindo princípios de bancos de dados relacionais para garantir consistência, performance e escalabilidade:

1. **Camada de Ingestão (Lançamentos):** Uma tabela fato unificada, alimentada cronologicamente pelos operadores da loja. Contém chaves exclusivas (IDs/SKUs de produtos), registros de tipo de movimentação (Entrada/Saída), volumes, valores unitários, totais automáticos e métodos de pagamento.
2. **Camada de Processamento (Dimensões de Estoque):** Abas separadas por categoria de produto (*Estoque Capa* e *Estoque Película*) que processam as movimentações da tabela fato utilizando fórmulas dinâmicas e matriciais.
3. **Camada de Visualização (Dashboard):** Painel executivo dinâmico alimentado em tempo real pelas camadas anteriores, sintetizando dados brutos em insights acionáveis.

---

## 💡 Regras de Negócio Otimizadas e Diferenciais Técnicos

- **Escalabilidade Sem Manutenção (À prova de futuro):** O uso de tabelas estruturadas e referências dinâmicas garante que novas linhas inseridas na rotina diária da loja sejam computadas automaticamente, eliminando a necessidade de manutenção manual ou reescrita de fórmulas.
- **Tratamento de Exceções na Formatação Condicional (Foco em UX):** Em vez de aplicar uma regra genérica que pinta de vermelho qualquer estoque zerado, o sistema foi configurado para remover a formatação condicional dos modelos que sequer possuem aquele tipo de produto no mercado (por exemplo, modelos de celular que não têm fabricação de película de cerâmica). Isso evita "falsos positivos" visuais de estoque zerado, poupando a atenção do gestor e permitindo que ele foque apenas nos produtos que realmente precisam de reposição. Modelos de smartphones que não possuem fabricação de películas de cerâmica, por exemplo, ignoram o alerta visual de desabastecimento. Isso elimina "falsos positivos", poupa a atenção do gestor e otimiza o foco apenas nas reposições que são criticamente necessárias.
- **Análise Temporal e Comportamental:** O dashboard consolida de forma automatizada os horários de maior movimento na loja e os dias da semana com maior volume de vendas, permitindo à gerência planejar melhor as escalas de funcionários e ações promocionais de forma preditiva.

--- 

Você pode interagir diretamente com a estrutura do sistema, fórmulas e layout do dashboard através do link abaixo:

🔗 [![Acesse o Projeto de Forma Interativa](<img width="1286" height="495" alt="Dashboard Sistema Automatizado de Gestão de Estoque" src="https://github.com/user-attachments/assets/779c1da0-a1b6-4932-8480-e523e7fe45c6" />
)](https://docs.google.com/spre![Uploading Dashboard Sistema Automatizado de Gestão de Estoque.png…]()
adsheets/d/1DnY4iPnXM5w8HTaNlF9ycDwNeiHDSNcCR_t2HNPLl3I/edit?usp=sharing)
