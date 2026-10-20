# Atividade de Revisão — Tratamento de Dados

Notebook com cinco exercícios de limpeza e preparação de dados em Python, feitos na disciplina de Ciência de Dados (Unidade II).

## Exercícios

| # | Tema | Dataset |
|---|------|---------|
| 1 | Valores ausentes | [Melbourne Housing Snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot) (`melb_data.csv`) |
| 2 | Duplicatas | [Customer Transaction Dataset (KPMG)](https://www.kaggle.com/datasets/archit9406/customer-transaction-dataset) |
| 3 | Padronização e escalonamento | [Adult Census Income](https://archive.ics.uci.edu/dataset/2/adult) (`adult.data`) |
| 4 | Outliers | Diamonds (carregado pelo `seaborn`) |
| 5 | Projeto integrado de limpeza | [Dirty E-Commerce Data — Shein](https://www.kaggle.com/datasets/oleksiimartusiuk/e-commerce-data-shein) |

Cada exercício tem o diagnóstico dos dados, o tratamento aplicado, uma comparação entre estratégias e as respostas às perguntas de reflexão.

## Bibliotecas

`pandas`, `numpy`, `matplotlib`, `seaborn`, `missingno`, `scikit-learn` e `rapidfuzz`.

## Como rodar

1. Abra o arquivo `.ipynb` no [Google Colab](https://colab.research.google.com/).
2. Baixe os datasets pelos links acima e coloque no seu Google Drive.
3. Ajuste os caminhos dos arquivos nas células de carregamento.
4. Rode tudo em **Ambiente de execução → Executar tudo**.

Os datasets não estão neste repositório por causa do tamanho. O do exercício 4 não precisa ser baixado, porque o próprio `seaborn` carrega.
