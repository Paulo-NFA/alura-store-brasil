# Análise de Desempenho de 4 Lojas - Data Science Challenge

## Descrição do Projeto
Este projeto faz parte do **Data Science Challenge da Alura** e tem como objetivo analisar o desempenho de 4 lojas diferentes para auxiliar o Sr. João na decisão de qual loja deve ser vendida. A análise considera múltiplos fatores como faturamento, satisfação do cliente, categorias de produtos, e custos de frete.

## Objetivo
Recomendar qual loja o Sr. João deve vender, baseando-se em análises de dados quantitativos e qualitativos, incluindo:
- Faturamento total
- Avaliação média dos clientes
- Produtos mais e menos vendidos
- Custo médio de frete
- Categorias de produtos mais populares

## Tecnologias Utilizadas
- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **Matplotlib** - Visualização de dados
- **Jupyter Notebook** - Ambiente de desenvolvimento

## Estrutura dos Dados
Cada loja possui um arquivo CSV com as seguintes colunas:
- Produto
- Categoria do Produto
- Preço
- Frete
- Data da Compra
- Vendedor
- Local da compra
- Avaliação da compra
- Tipo de pagamento
- Quantidade de parcelas
- lat (latitude)
- lon (longitude)

## Como Executar o Projeto

### Pré-requisitos
```bash
pip install pandas matplotlib
```

### Executando
1. Clone este repositório
```bash
git clone https://github.com/seu-usuario/analise-lojas-challenge.git
cd analise-lojas-challenge
```

2. Abra o Jupyter Notebook
```bash
jupyter notebook
```

3. Execute o notebook `analise_lojas.ipynb`

## Análises Realizadas

### 1. Faturamento por Loja
Calculado através da soma dos preços de todos os produtos vendidos em cada loja.

### 2. Categorias de Produtos
Análise da quantidade de produtos vendidos por categoria em cada loja usando `value_counts()`.

### 3. Avaliação dos Clientes
Média das avaliações recebidas pelos clientes em cada loja.

### 4. Produtos Mais e Menos Vendidos
Identificação dos top 5 produtos mais vendidos e os 5 menos vendidos por loja.

### 5. Custo Médio de Frete
Análise do custo médio de frete pago pelos clientes em cada loja.

## Visualizações
O projeto inclui 3 gráficos principais:
1. **Gráfico de Barras**: Faturamento total por loja
2. **Gráfico de Barras**: Média de avaliação por loja
3. **Gráfico de Barras Horizontais**: Top 10 produtos mais vendidos

## Resultados Principais

| Critério              | loja | loja2 | loja3 | loja4 |
|-----------------------|------|-------|-------|-------|
| Faturamento           | 1º   | 2º    | 3º    | 4º    |
| Avaliação Cliente     | 4º   | 2º    | 1º    | 3º    |
| Frete (cliente paga)  | 4º   | 3º    | 2º    | 1º    |

## Conclusão
**Recomendação: Vender a loja original**

Apesar de ter o maior faturamento, a loja original apresenta:
- Pior avaliação dos clientes (3.98)
- Frete mais caro (34,69 reais)
- Sinais de deterioração na experiência do cliente

As outras lojas (loja2, loja3 e loja4) apresentam melhor equilíbrio entre faturamento, satisfação do cliente e custos operacionais.

## Arquivos do Projeto
```
├── analise_lojas.ipynb       # Notebook principal com todas as análises
├── README.md                  # Este arquivo
└── dados/
    ├── loja_1.csv            # Dados da loja 1
    ├── loja_2.csv            # Dados da loja 2
    ├── loja_3.csv            # Dados da loja 3
    └── loja_4.csv            # Dados da loja 4
```

## Autor
**Paulo Martin**

Projeto desenvolvido como parte do **Data Science Challenge - Alura**

## Licença
Este projeto é open source e está disponível para fins educacionais.

---

*Desenvolvido com Python e muito aprendizado em Data Science!*
