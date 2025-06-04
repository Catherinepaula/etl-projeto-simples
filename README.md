
# 🧪 Projeto ETL Simples com Python

Este repositório contém um projeto prático de ETL (Extração, Transformação e Carga) feito com Python, utilizando um conjunto de dados fictício de vendas.

---

## 📌 Objetivo

Demonstrar de forma simples o funcionamento de um pipeline de dados ETL, com as seguintes etapas:

### ✅ Extração
Leitura de um arquivo CSV (`vendas.csv`) contendo informações brutas de vendas.

### ✅ Transformação
- Padronização dos nomes das colunas
- Preenchimento de valores nulos
- Criação de uma nova coluna `valor_total` (quantidade × preço)

### ✅ Carga
Salvamento dos dados transformados em um novo arquivo CSV chamado `vendas_tratadas.csv`.

---

## 📁 Estrutura do Projeto

```
etl-projeto-simples/
├── vendas.csv              # Arquivo original com os dados de entrada
├── vendas_tratadas.csv     # Arquivo final com os dados tratados
├── etl_vendas.ipynb        # Notebook com o código do pipeline ETL
└── README.md               # Este arquivo de documentação
```

---

## ▶️ Como Executar

1. Faça o clone do repositório:
   ```bash
   git clone https://github.com/seu-usuario/etl-projeto-simples.git
   ```

2. Abra o arquivo `etl_vendas.ipynb` no Google Colab ou Jupyter Notebook.

3. Execute todas as células para rodar o pipeline ETL.

---

## 📊 Exemplo de Saída

| data       | produto  | quantidade | preco_unitario | valor_total |
|------------|----------|------------|----------------|-------------|
| 2025-01-01 | Camiseta | 3          | 50.0           | 150.0       |
| 2025-01-02 | Calça    | 2          | 100.0          | 200.0       |

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- pandas
- Google Colab

---

## 🙋‍♀️ Sobre

Este projeto foi desenvolvido por **Catherine** como parte dos estudos em Ciência de Dados e Análise de Dados na EBAC.  

