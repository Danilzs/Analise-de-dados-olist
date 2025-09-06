# Análise de Dados Olist

Este projeto realiza uma análise exploratória dos dados do e-commerce brasileiro Olist, utilizando Python e Jupyter Notebook. O foco principal está em responder perguntas de negócio relevantes a partir dos dados, com visualizações e interpretações.

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura dos Dados](#estrutura-dos-dados)
- [Principais Análises Realizadas](#principais-análises-realizadas)
- [Como Executar](#como-executar)
- [Resultados e Insights](#resultados-e-insights)
- [Dependências](#dependências)
- [Autor](#autor)

---

## Sobre o Projeto

Este projeto faz parte de uma análise de dados sobre o marketplace Olist, abordando questões como atraso de entregas, métodos de pagamento, relação entre tempo de entrega e satisfação do cliente, e análise das categorias de produtos. As análises são feitas em Python, utilizando Pandas, Matplotlib e Seaborn para manipulação e visualização dos dados.

## Estrutura dos Dados

Os dados utilizados são públicos e podem ser baixados do Kaggle ([Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)). Os principais arquivos analisados são:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_products_dataset.csv`
- `olist_customers_dataset.csv`
- `product_category_name_translation.csv`

## Principais Análises Realizadas

1. **Percentual de Entregas Atrasadas**
   - Cálculo do percentual de pedidos entregues após a data estimada.
   - Visualização em gráfico de pizza e barras.
   - Insight: 8,1% dos pedidos são entregues com atraso.

2. **Método de Pagamento Mais Utilizado em Pedidos Acima de R$150**
   - Identificação do método de pagamento mais escolhido em compras acima de R$150.
   - Visualização em gráfico de barras.
   - Insight: Cartão de crédito é o método mais utilizado, com ampla vantagem.

3. **Relação entre Tempo de Entrega e Nota de Avaliação**
   - Cálculo da correlação entre tempo de entrega e satisfação do cliente.
   - Visualizações: scatter plot, boxplot, heatmap, histogramas.
   - Insight: Correlação negativa (-0.35), ou seja, entregas mais rápidas tendem a receber notas melhores.

4. **Top 5 Categorias de Produtos Mais Vendidas e Receita**
   - Quantificação e receita total das 5 categorias mais vendidas.
   - Gráficos de barras e pizza demonstrando participação das categorias.
   - Insight: As categorias `bed_bath_table`, `health_beauty`, `sports_leisure`, `furniture_decor` e `computers_accessories` lideram em vendas e receita.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Danilzs/Analise-de-dados-olist.git
   ```
2. Instale as dependências recomendadas:
   ```bash
   pip install -r requirements.txt
   ```
3. Baixe o conjunto de dados do Kaggle ou utilize o notebook para baixar automaticamente via `kagglehub`.
4. Abra e execute o notebook `Analise_Dados1.ipynb` em Jupyter Notebook ou Google Colab.

## Resultados e Insights

- **Eficiência Logística:** Mais de 91% dos pedidos são entregues dentro do prazo.
- **Preferência de Pagamento:** Cartão de crédito é amplamente preferido em compras de maior valor.
- **Satisfação do Cliente:** Entregas mais rápidas resultam em notas mais altas.
- **Categorias Líderes:** Algumas categorias geram grande volume de vendas e receita.

## Dependências

- Python 3.x
- Jupyter Notebook / Google Colab
- pandas
- numpy
- matplotlib
- seaborn
- kagglehub

> Recomenda-se utilizar ambiente virtual para evitar conflitos de dependências.

## Autor

- [Danilzs](https://github.com/Danilzs)
- [slnntk](https://github.com/slnntk)

---

**Repositório:** [Danilzs/Analise-de-dados-olist](https://github.com/Danilzs/Analise-de-dados-olist)
