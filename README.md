# Classificação de Notícias (20 Newsgroups)

Este repositório contém o desenvolvimento de um pipeline de Processamento de Linguagem Natural (NLP) para classificar mensagens de fóruns em quatro categorias. 

---

## Visão Geral e Resultados

O projeto utiliza o dataset `20newsgroups` para treinar modelos capazes de identificar textos sobre: **Computação, Medicina, Ateísmo e Cristianismo**.

### Performance dos Modelos
| Algoritmo | Acurácia Final |
| :--- | :--- |
| Logistic Regression | ~82% |
| Linear SVC          | ~79% |
| Naive Bayes         | ~77% |

---

## Pré-Requisitos

Este projeto utiliza o gerenciador de pacotes **uv** para garantir a máxima performance e reprodutibilidade do ambiente.

### Windows (PowerShell)
powershell -c "irm [https://astral.sh/uv/install.ps1](https://astral.sh/uv/install.ps1) | iex"

### Linux/MacOS
curl -LsSf [https://astral.sh/uv/install.sh](https://astral.sh/uv/install.sh) | sh

## Instalaçao e preparaçao
- Clona o repositorio

git clone [https://github.com/Thalles211/semana_nlp.git](https://github.com/Thalles211/semana_nlp.git)
cd semana_nlp

- Sincroniza o ambiente

uv sync

- Registra o Kernel do Jupyter

uv run python -m ipykernel install --user --name news-classifier --display-name "Python (News Classifier)"
