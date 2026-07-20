# SIRCA — Modelo de Machine Learning

Este repositório contém o código-fonte, scripts de pré-processamento, engenharia de recursos (feature engineering) e os artefatos de treinamento do modelo de Machine Learning utilizado pelo sistema **SIRCA** (*Sistema Inteligente de Recomendação de Culturas Agrícolas*).

---

## 📌 Sobre o Modelo

O objetivo principal deste modelo é auxiliar produtores rurais na tomada de decisão sobre quais culturas agrícolas plantar, levando em consideração variáveis ambientais, solo, clima e restrições específicas da propriedade.

* **Algoritmo utilizado:** Scikit-Learn (Random Forest / Decision Tree / etc.)
* **Linguagem:** Python 3.10+
* **Formato do artefato exportado:** `.pkl` / `.joblib`


## 📊 Distribuição das culturas:
![01](imgs/distribui%C3%A7%C3%A3o_culturas.png)

## 📊 Importâncias das variáveis utilizadas para geração da recomendação:
![02](imgs/import%C3%A2ncia_vari%C3%A1veis_culturas.png)

## 📊 Matriz de confusão do modelo (para identificar os erros e acertos):
![03](imgs/matriz_confus%C3%A3o.png)
