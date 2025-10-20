# Projeto 9 — Otimização de Classificadores com XGBoost e SVM

---

## 📚 Explicação do Curso
Este projeto foi desenvolvido como parte do curso de Cientista de Dados da EBAC, focando no domínio de dois dos algoritmos de classificação mais poderosos e essenciais para o mercado: o modelo de *Ensemble* **XGBoost (Extreme Gradient Boosting)** e a máquina de separação de dados **Support Vector Machine (SVM)**. O objetivo é aplicar e comparar esses modelos em uma base de dados de propensão à compra de carros.

---

## 🎯 Objetivos
O principal objetivo deste projeto é a consolidação de técnicas avançadas de classificação:

* **Implementação do XGBoost:** Aplicar o algoritmo XGBoost para obter alta performance na classificação de clientes.
* **Implementação do SVM:** Utilizar o Support Vector Machine (SVM), explorando a aplicação de diferentes *kernels* (como Linear e Polinomial) para encontrar o melhor hiperplano de separação de classes.
* **Comparação de Modelos:** Comparar o desempenho e os resultados de XGBoost e SVM para determinar qual modelo é mais robusto e eficaz para o *dataset* de propensão à compra.
* **Consolidação de Modelos Avançados:** Consolidar o entendimento sobre a aplicação de modelos de *Ensemble* e modelos baseados em *Kernel*.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Algoritmos Principais:** XGBoost e Support Vector Classifier (SVC/SVM).
* **Bibliotecas Principais:** Pandas, Scikit-learn (SVC), XGBoost.
* **Pré-processamento:** `LabelEncoder` (para variáveis categóricas como "Gender").
* **Ambiente:** Jupyter Notebook.

---

## 📈 Principais Análises Realizadas
O projeto focou nas seguintes etapas de preparação, modelagem e comparação:

* **Pré-processamento de Dados:** Tratamento da base de dados (Propensão à Compra de Carros), incluindo o *drop* da coluna 'User ID' e aplicação do `Label Encoder` na coluna 'Gender'.
* **Modelagem XGBoost:** Treinamento do modelo **XGBoost** para classificar clientes com alta e baixa probabilidade de conversão, buscando uma das maiores acurácias possíveis.
* **Modelagem SVM:** Implementação do **SVM** com o *kernel* Polinomial e o *kernel* Linear, comparando qual gerou as melhores métricas (Acurácia, Recall).
* **Análise de Métricas:** Avaliação dos modelos através das métricas de classificação, com foco na análise comparativa do **Recall** e **Precision** para a classe minoritária.

---

## ✨ Insights Chave (Conclusão)

O exercício demonstrou o domínio das técnicas avançadas de classificação, provando a capacidade de ir além dos modelos de *baseline*:

* **Superioridade do XGBoost:** A análise comparativa confirmou a **superioridade do XGBoost** em relação ao SVM na maioria das métricas para este problema, estabelecendo-o como o modelo mais eficaz para a previsão de propensão à compra de carros.
* **Validação de Baseline:** O exercício também validou a Regressão Logística como um excelente modelo de *baseline*, reforçando que os modelos mais complexos (XGBoost) devem justificar seu uso com um ganho significativo de performance.
* **Domínio Técnico:** O projeto reforçou a habilidade de implementar e comparar modelos de ponta, essenciais para a área de Ciência de Dados.