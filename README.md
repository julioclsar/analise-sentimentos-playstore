# 🧩 Análise de Sentimento e Correlação com Avaliações da Play Store

Este repositório contém um notebook em Python desenvolvido para analisar a relação entre **avaliações textuais de usuários** e **pontuações numéricas (1–5 estrelas)** de aplicativos da Google Play Store.  
O objetivo é investigar se há coerência entre o que os usuários escrevem nas reviews e as notas que atribuem.

---

## 📘 Descrição do Projeto

O notebook realiza:

- **Pré-processamento de texto** (remoção de stopwords, tokenização, normalização);
- **Extração de polaridade de sentimento** utilizando o módulo `SentimentIntensityAnalyzer` (NLTK);
- **Análise de correlação estatística** entre sentimentos e notas atribuídas;
- **Visualizações gráficas** das distribuições de notas e polaridades.

O projeto foi implementado em ambiente **Google Colab** e pode ser facilmente reproduzido localmente.

---

## 🧰 Tecnologias Utilizadas

- **Linguagem:** Python 3.10  
- **Bibliotecas:** `pandas`, `numpy`, `scikit-learn`, `nltk`, `matplotlib`

---

## 📊 Dataset

- **Fonte:** [Google Play Store Reviews – Kaggle](https://www.kaggle.com/datasets/prakharrathi25/google-play-store-reviews)  
- **Autor:** Prakhar Rathi  
- **Licença:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
- **Descrição:** Contém mais de 12 mil avaliações textuais com suas respectivas notas e identificadores de aplicativos.

---

## 🚀 Execução

Para executar o notebook localmente:

```bash
pip install pandas numpy scikit-learn nltk matplotlib
