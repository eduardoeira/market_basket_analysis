# Market Basket Analysis com Efficient Apriori

Este repositório contém um projeto de Market Basket Analysis utilizando o pacote `efficient_apriori` em Python. O objetivo é identificar padrões de compra e associações entre produtos com base em um conjunto de transações.

## 📌 Descrição do Projeto

A análise foi realizada em um conjunto de 500.000 transações, aplicando o algoritmo Apriori para extrair regras de associação entre os itens comprados. O foco foi calcular as métricas de suporte, confiança e lift para interpretar as relações entre os produtos.

## 🛠 Tecnologias Utilizadas
- Python
- Pandas
- Efficient Apriori
- NumPy

## 📊 Análises Realizadas
- **Análise Estatística Descritiva**: Exploração inicial dos dados para entender a distribuição dos itens comprados e padrões gerais de compra.
- **Identificação de Itens Frequentes**: Uso do Apriori para encontrar conjuntos de itens que ocorrem frequentemente nas transações.
- **Geração de Regras de Associação**: Extração de regras do tipo "Se um cliente compra X, há uma probabilidade de que ele compre Y".
- **Cálculo das Métricas de Associação**:
  - **Suporte**: Probabilidade de um item ou conjunto de itens aparecer nas transações.
  - **Confiança**: Probabilidade de compra de um item B, dado que o item A foi comprado.
  - **Lift**: Impacto da relação entre os produtos comparado à compra independente dos itens.

## 📈 Principais Resultados
- Produtos como **"Organic Fuji Apple"** e **"Banana"** apresentaram forte associação, com alta confiança e lift.
- O algoritmo identificou itens frequentemente comprados juntos, permitindo insights para estratégias de marketing e recomendações personalizadas.

## 📂 Estrutura do Repositório
- `market_basket_analysis.ipynb` - Notbook contendo a implementação do Apriori e o cálculo das métricas de associação.
- `README.md` - Este arquivo com informações sobre o repositório.
- Os arquivos com os dados são muito pesados, por isso não estão nesse repositório.

## 🚀 Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/market-basket-analysis.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute os notebooks para visualizar as análises.

## 📌 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests com sugestões e melhorias.

---
📧 Para mais informações, entre em contato!

