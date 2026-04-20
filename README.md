# 📊 Case Técnico: NovaShop - Digital Consulting (Peers Group)

Este repositório contém a resolução do case técnico **NovaShop**, focado em análise de dados e consultoria digital para identificação de gargalos operacionais e oportunidades de crescimento.

## 📖 Contextualização
A NovaShop é um e-commerce em rápida expansão que enfrenta desafios comuns ao crescimento acelerado: alta taxa de cancelamentos e aumento nos tickets de suporte. Este projeto utiliza Python para transformar dados brutos em inteligência de negócio.

## 🎯 Questões de Negócio Abordadas
A análise respondeu, através de código e exploração de dados, às seguintes questões norteadoras:

* **Status dos Pedidos:** Distribuição percentual do volume de pedidos (entregues, cancelados, em trânsito, devolvidos).
* **Top Produtos:** Identificação dos 10 produtos mais vendidos (em volume) e a respetiva receita gerada.
* **Ticket Médio B2C vs B2B:** Análise comparativa com teste de validação de significância estatística.
* **Sazonalidade:** Evolução mensal do volume de pedidos ao longo de 2023 e 2024, identificando picos, quedas e hipóteses.
* **Canais de Aquisição:** Análise de rentabilidade e retenção, cruzando a taxa de cancelamento com o maior valor médio de compra por canal.
* **Qualidade dos Dados:** Identificação, tratamento e documentação de inconsistências na base (campos nulos e *outliers*).

## 💡 Principais Insights e Recomendações
Através do processamento dos dados em Python, foram obtidas as seguintes conclusões estratégicas:

1.  **Comportamento Distinto por Segmento:** O teste de hipóteses comprovou de forma estatisticamente relevante (**P-Valor: 0.000000**) que o comportamento de compra difere significativamente entre os segmentos. O **B2B** apresenta um Ticket Médio muito superior (**R$ 7.778,34**) face ao **B2C** (**R$ 1.264,72**).
2.  **Alerta no Tráfego Pago:** O canal de aquisição *Paid Search* (Busca Paga) apresentou a pior taxa de retenção, com **30,74% de evasão (cancelamentos)**. Hipótese: desalinhamento de expectativas ou gatilhos muito agressivos nas campanhas.
3.  **O "Quadrante de Ouro":** Canais baseados em prova social (*Redes Sociais* e *Indicação*) atraem os clientes mais rentáveis, com os maiores Tickets Médios (ex: Redes Sociais com **R$ 2.645,86**) e baixas taxas de cancelamento. 
    * **Recomendação:** Redirecionar parte do orçamento de *Paid Search* para alavancar programas de *Member-Get-Member*.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python 3.14+
* **Ambiente:** Jupyter Notebook (`.ipynb`)
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Estatística:** SciPy (Testes de Hipóteses e Estatística T)

## 🚀 Como Executar o Projeto

1. **Clone este repositório** para a sua máquina local:
   ```bash
   git clone [https://github.com/teu-usuario/nome-do-repositorio.git](https://github.com/teu-usuario/nome-do-repositorio.git)
