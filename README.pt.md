[Leia em inglês](README.md)

# 🍦 Quando o Sol Sobe, as Vendas Disparam: Uma Análise Preditiva

Todos nós sabemos por intuição: dias quentes e sorvete são uma combinação perfeita. Mas e se pudéssemos ir além da intuição? E se pudéssemos usar dados para criar uma verdadeira "bola de cristal" capaz de prever exatamente o quanto a receita de uma sorveteria pode aumentar a cada grau que a temperatura sobe?

Este projeto faz exatamente isso. Mergulhamos em um conjunto de dados de vendas para transformar o senso comum em um modelo matemático preciso. Usando **Regressão Linear**, deciframos a relação entre a temperatura e a receita, criando uma ferramenta para prever o sucesso de vendas antes mesmo de o sol atingir seu pico.

[![Looker Studio Dashboard](https://img.shields.io/badge/Looker%20Studio-Dashboard-blue?style=for-the-badge&logo=looker)](https://lookerstudio.google.com/reporting/312a8405-a3f1-4d25-ba32-d7b3fb73eee7/page/WYKUF)

---

## 🔮 O Oráculo Interativo: Explore os Dados

Para tornar a análise acessível a todos, criamos um oráculo visual no **Looker Studio**. Neste dashboard interativo, você pode manipular a temperatura com um slider e observar em tempo real como a previsão da receita responde. Não é apenas um gráfico, é a sua chance de prever o futuro das vendas.

**[>> Consulte o Oráculo Interativo aqui <<](https://lookerstudio.google.com/reporting/312a8405-a3f1-4d25-ba32-d7b3fb73eee7/page/WYKUF)**

![Dashboard Screenshot](dashboard.jpg)

---

## 📈 A Revelação: A Fórmula Mágica das Vendas

Nossa análise confirmou o que suspeitávamos: existe uma forte e clara conexão linear entre a temperatura e a receita. Usando a biblioteca **Scikit-learn**, ensinamos um modelo a "aprender" essa relação e a traduzi-la em uma poderosa fórmula preditiva.

### A Equação da Profecia

O modelo revelou a seguinte equação para prever a receita:

$$ \text{Receita} = 21.44 \times \text{Temperatura} + 44.27 $$

* **Coeficiente (m):** `21.44`
* **Intercepto (c):** `44.27`

**O que isso significa?** A revelação é simples e poderosa: o modelo prevê que, para cada **aumento de 1°C na temperatura**, a receita da sorveteria tende a **aumentar em aproximadamente $21.44**.

### Testando a Profecia
Para validar nosso modelo, fizemos uma previsão:
* Para um dia com **25°C**, a receita prevista é de **$580.31**.

### Visualizando a Conexão
O gráfico de dispersão abaixo não deixa dúvidas. A linha vermelha, que representa as previsões do nosso modelo, se ajusta perfeitamente aos dados reais, confirmando visualmente a forte correlação positiva.

![Gráfico de Regressão Linear](linear_regression.png)

---

## 📜 Os Manuscritos Antigos: O Dataset

Nossa jornada não seria possível sem os manuscritos que continham os segredos das vendas passadas. Utilizamos o "Ice Cream Sales Dataset", originalmente disponibilizado no Kaggle.

* **Fonte Original:** [Ice Cream Sales Dataset on Kaggle](https://www.kaggle.com/datasets/sakshisatre/ice-cream-sales-dataset)
* **Autor:** Sakshi Satre

O arquivo `df_final_ice_cream.csv` neste repositório é a versão já limpa e preparada, contendo as duas colunas essenciais para nossa magia: `Temperature` (°C) e `Revenue` ($).

---

## 🛠️ O Caldeirão do Alquimista: Ferramentas e Bibliotecas

Para transformar dados brutos em ouro preditivo, utilizamos as seguintes ferramentas:

* **Linguagem:** Python
* **Bibliotecas Mágicas:**
    * Pandas (para organizar e manipular os dados)
    * Matplotlib & Seaborn (para as visualizações e gráficos)
    * Scikit-learn (para conjurar o modelo de Regressão Linear)
* **Ambiente de Feitiçaria:** Jupyter Notebook
* **Ferramenta de BI:** Looker Studio (para o nosso oráculo interativo)

---

## 🚀 Recrie a Magia: Como Executar o Projeto

Siga estes passos para executar a análise e fazer suas próprias previsões:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/OYanEnrique/ice-cream-revenue-prediction.git](https://github.com/OYanEnrique/ice-cream-revenue-prediction.git)
    cd ice-cream-revenue-prediction
    ```
2.  **Instale os ingredientes necessários:**
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyterlab
    ```

3.  **Inicie o laboratório:**
    ```bash
    jupyter lab
    ```

4.  Abra e execute o notebook `ice_cream_data.ipynb` para testemunhar toda a análise.

## 👨‍💻 O Arquiteto da Análise

* **Yan Enrique**
* **LinkedIn:** [https://www.linkedin.com/in/yanenrique/](https://www.linkedin.com/in/yanenrique/)
* **GitHub:** [https://github.com/OYanEnrique](https://github.com/OYanEnrique)
* **Landing page:** [https://yanenrique.carrd.co](https://yanenrique.carrd.co)
---
