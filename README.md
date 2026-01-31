# 🧠 Treinamento e Seleção de Modelos: Análise de Sentimentos Twitter

## 📖 Descrição do Módulo

Este repositório é o coração científico do projeto. Após a extração dos dados, o desafio foi lidar com a natureza desequilibrada das opiniões nas redes sociais. Para isso, estruturei três cenários experimentais para testar a performance de 5 algoritmos de classificação, buscando o equilíbrio ideal entre precisão e sensibilidade (Recall).

## 🧪 Estrutura dos Experimentos

O projeto foi dividido em três abordagens técnicas para comparação:

1. [Cenário Padrão](https://github.com/alan-vieira/treina_analise_de_sentimento_do_twitter/blob/main/treinando_mdl_padrao_reduz.ipynb): Utiliza a distribuição original dos dados. Funciona como nossa Baseline para entender o comportamento real dos algoritmos sem interferências.

2. [Cenário Oversampling](https://github.com/alan-vieira/treina_analise_de_sentimento_do_twitter/blob/main/treinando_mdl_over_reduz.ipynb): Aplica técnicas de superamostragem para equilibrar as classes, garantindo que o modelo aprenda a identificar sentimentos minoritários com maior eficácia.

3. [Cenário Undersampling](https://github.com/alan-vieira/treina_analise_de_sentimento_do_twitter/blob/main/treinando_mdl_under_reduz.ipynb): Reduz a classe majoritária para criar um dataset perfeitamente equilibrado, focando na qualidade e distinção das amostras.

## 🛠️ Pipeline de Data Science

Em todos os notebooks, o fluxo segue o rigor técnico de:

- **Pré-processamento**: Limpeza, Tokenização e Lematização.

- **Feature Engineering**: Transformação de texto em vetores numéricos via CountVectorizer e TfidfVectorizer.

- **Modelagem**: Comparativo entre classificadores (Naive Bayes, Logistic Regression, entre outros).

- **Métricas**: Análise via Matriz de Confusão e Relatório de Classificação.

# 🚀 Como Utilizar

1. Clone o repositório.

2. Instale as bibliotecas necessárias:

```
pip install pandas scikit-learn nltk
```

3. Explore os notebooks para visualizar os gráficos comparativos de cada estratégia de balanceamento.

## 📺 Explicação em Vídeo

Confira a análise dos resultados e a lógica por trás da escolha das técnicas:

🔗 Vídeo: [Treinamento e Performance de Modelos](https://www.youtube.com/watch?v=4lE9CmW3mk8)

## 👤 Autor

**Alan Vieira** - *Engenheiro de Telecomunicações & Especialista em Dados*

- [LinkedIn](https://www.linkedin.com/in/alansilvavieira)

- [GitHub Portfólio](https://github.com/alan-vieira)
