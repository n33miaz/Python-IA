# Projeto Python IA: Inteligência Artificial e Previsões

## 📍 Problemática:
### Score de Crédito dos Clientes

Você foi contratado por um banco para conseguir definir o score de crédito dos clientes. 
Você precisa analisar todos os clientes do banco e, com base nessa análise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de crédito dele: Ruim, Ok, Bom

**Fiz esse projeto com a ajuda do canal [Hashtag Programação](https://youtube.com/@HashtagProgramacao), no evento "Python Power Up".**

## 🔧 Como desenvolvi?

Importar o arquivo "cliente.csv" para meu código Python no Jupyter Notebook, converti as colunas textuais para números, usando a ferramenta do scikit-learn "LabelEncoder".
Fiz isso por conta que a Inteligência Artificial só compreende números.

Feito isso, treinei dois modelos de IA, sendo eles: **Árvore de Decisão** ([RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html))
e **Knn** ([KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)), após o treinamento,
comparei o quão bom estava a precisão das duas, e escolhi a melhor (Árvore de Decisão) para a minha situação.

Por fim, apenas apliquei a IA treinada ao arquivo "novo_clientes.csv" para ela prever o score dos clientes.

- IDE: [Visual Studio Code](https://code.visualstudio.com/download)
- Extensões Necessárias: [Jupyter](https://jupyter.org/install) - [Jupyter Notebook Renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers)

## 📖 Instalando as Bibliotecas:

| [pandas](https://pandas.pydata.org/docs/) | ^2.1.1 | [numpy](https://numpy.org/doc/stable/) | ^1.26 | [scikit-learn](https://scikit-learn.org/stable/user_guide.html) | ^1.3.1 |
|----------------|---------------|--------------|---------------|----------------|---------------|


**Terminal Linux:**

```bash
  sudo install pandas numpy scikit-learn
```
**Jupiter:**

```bash
  pip install pandas numpy scikit-learn
```
