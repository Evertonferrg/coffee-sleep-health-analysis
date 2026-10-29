# ☕ Café, Sono e Saúde — Checkpoint Cientista de Dados (Nível 1)

Projeto de análise de dados da empresa fictícia **Health & Life Analytics**, que investiga como o consumo de café se relaciona com hábitos de sono e condições de saúde, e treina modelos para **prever a qualidade do sono (`Sleep_Quality`)**.

## Objetivo
1. **EDA:** entender estrutura, qualidade e distribuição dos dados.
2. **Visualização e insights:** comparar grupos (gênero, idade, estresse, consumo de café) e documentar as principais descobertas.
3. **Modelo preditivo:** classificar `Sleep_Quality` com pelo menos dois modelos e recomendar ações de negócio.

## Estrutura do repositório
```
├── analise_cafe_sono_saude.ipynb      # notebook principal (as 3 partes)
├── synthetic_coffee_health_10000(in).csv  # dataset original
├── dataset_processado.csv             # dataset final após pré-processamento
├── melhor_modelo.joblib               # melhor modelo treinado
└── README.md
```

## Dataset
- Arquivo: `synthetic_coffee_health_10000(in).csv` (10.000 registros, 16 colunas).
- Fonte original: [Global Coffee Health Dataset (Kaggle)](https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset).

## Como executar

### Google Colab (recomendado)
1. Acesse [colab.research.google.com](https://colab.research.google.com) → **Arquivo → Fazer upload de notebook** e escolha `analise_cafe_sono_saude.ipynb`.
2. Execute as células em ordem (**Ambiente de execução → Executar tudo**).
3. Quando a célula de carregamento pedir, faça upload do CSV do dataset.

### Jupyter Notebook local
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib notebook
jupyter notebook analise_cafe_sono_saude.ipynb
```
Coloque o CSV na mesma pasta do notebook.

## Requisitos
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

## Resultados
> Preencha após executar o notebook: melhor modelo, acurácia no teste, principais descobertas e recomendações.

## Autor
Seu nome — [LinkedIn/GitHub]
