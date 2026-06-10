# Análise Comparativa de Rentabilidade: Planos Telefônicos Surf vs. Ultimate

## Descrição do Projeto
Este projeto foi desenvolvido com foco em Análise Estatística e Comportamento do Consumidor para a empresa de telecomunicações Megaline. O desafio consistiu em avaliar o desempenho financeiro de dois planos pré-pagos (Surf e Ultimate) para determinar qual deles gera maior receita por cliente e sustenta o melhor ROI para o orçamento de publicidade. A análise envolveu o processamento e a limpeza de dados de 500 clientes, cálculo de consumo mensal (chamadas, mensagens e tráfego de dados) e a aplicação de testes de hipóteses estatísticas para validar se as médias de receita entre os planos diferem significativamente, permitindo uma decisão baseada em evidências.

---

## Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python
* **Análise e Manipulação de Dados:** Pandas e NumPy
* **Análise Estatística:** SciPy (Testes de Hipóteses)
* **Visualização de Dados:** Matplotlib e Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook

---

## Pipeline de Dados e Metodologia

### 1. Auditoria e Preparação de Dados
* Carga e inspeção de dados brutos de 500 clientes, incluindo informações demográficas e histórico detalhado de uso (chamadas, mensagens e tráfego de dados) referente ao ano de 2018.
* Saneamento e tratamento de tipos de dados, convertendo variáveis temporais e numéricas para garantir a acurácia nos cálculos de faturamento mensal.

### 2. Engenharia de Variáveis de Consumo
* Agregação do volume de uso mensal (minutos, SMS e gigabytes) por cliente, aplicando regras de arredondamento conforme a política de tarifação da operadora.
* Cálculo da receita mensal total por cliente, considerando a mensalidade do plano e os custos extras incidentes quando o consumo supera o pacote contratado.

### 3. Análise Exploratória e Visualização (EDA)
* Análise estatística descritiva das médias e desvios-padrão de cada plano para identificar o perfil de consumo dos usuários.
* Construção de histogramas e gráficos de caixa (*boxplots*) para visualizar a distribuição da receita e identificar outliers (clientes com consumo muito acima da média).

### 4. Testes Estatísticos de Hipóteses
* Formulação e teste de hipóteses para comparar se a receita média dos usuários dos planos Surf e Ultimate diferem entre si.
* Aplicação do Teste t de Student para amostras independentes, com nível de significância de 5%, garantindo que os resultados não sejam fruto do acaso.

---

## Principais Insights & Impacto de Negócio
* **Rentabilidade por Perfil:** A análise estatística permitiu mapear claramente como o comportamento de uso (especialmente o consumo de dados) impacta a receita final de cada plano.
* **Validação Estatística:** Os testes de hipóteses confirmaram as diferenças de comportamento entre os dois grupos, fornecendo ao departamento comercial um embasamento sólido para ajustar a estratégia de marketing.
* **Orientação de Investimento:** Com base na receita média identificada, o projeto sugere ao setor de publicidade em quais planos focar o orçamento para maximizar a conversão de novos usuários e o retorno financeiro.

---

