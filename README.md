# 🧠 Análise Exploratória de Dados — Traços de Personalidade

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clebermarcolino/AnaliseExploratoriadeDados/blob/main/A2_IA.ipynb)

## 📘 Descrição do Projeto

Este projeto tem como objetivo realizar uma **Análise Exploratória de Dados (EDA)** sobre um **dataset sintético de personalidade**, composto por 20.000 registros e 30 variáveis.
O estudo busca compreender padrões e correlações entre características comportamentais, explorando estatísticas descritivas e visualizações gráficas.

## 📊 Estrutura do Dataset

* **Total de linhas:** 20.000
* **Total de colunas:** 30
* **Variável alvo:** `personality_type` (categórica)
* **Demais variáveis:** 29 atributos numéricos representando traços e hábitos comportamentais (ex: *talkativeness*, *party_liking*, *responsibility*, etc.)

## 🧩 Objetivos da Análise

1. Explorar a estrutura e a qualidade dos dados.
2. Identificar possíveis inconsistências ou valores ausentes.
3. Obter estatísticas descritivas das variáveis numéricas.
4. Visualizar distribuições e correlações entre atributos.
5. Entender o comportamento da variável `personality_type` e suas relações com os demais traços.

## 🛠️ Tecnologias Utilizadas

| Biblioteca     | Função                                             |
| -------------- | -------------------------------------------------- |
| **Pandas**     | Manipulação e limpeza dos dados                    |
| **NumPy**      | Operações numéricas e vetorização                  |
| **Matplotlib** | Criação de gráficos e visualizações                |
| **Seaborn**    | Visualizações estatísticas e estéticas aprimoradas |

## ⚙️ Etapas do Notebook

1. **Importação das bibliotecas**
2. **Carregamento da base de dados** (`personality_synthetic_dataset.csv`)
3. **Análise estrutural e estatísticas descritivas**
4. **Visualização de distribuições e correlações**
5. **Discussão dos resultados e insights preliminares**

## 📈 Principais Resultados

* Os atributos numéricos possuem valores entre **0 e 10**, com médias próximas a **5**, indicando distribuição centrada.
* A base é **consistente**, sem valores nulos.
* Algumas variáveis apresentam maior variabilidade, o que pode indicar padrões interessantes para futuras análises preditivas.

## 🚀 Como Executar

1. Abra o projeto no [Google Colab](https://colab.research.google.com/github/clebermarcolino/AnaliseExploratoriadeDados/blob/main/A2_IA.ipynb).
2. Carregue o arquivo `personality_synthetic_dataset.csv` no ambiente Colab (obs: o dataset está presente no repositório).
3. Execute as células sequencialmente para reproduzir a análise.
