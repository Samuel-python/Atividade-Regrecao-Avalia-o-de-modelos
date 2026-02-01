# Atividade-Regrecao-Avalia-o-de-modelos
Projeto de análise de dados desenvolvido durante o curso de Ciência de Dados da Mentorama.
# 📊 Atividade – Módulo 9 | Regressão e Avaliação de Modelos

Este repositório contém uma atividade prática desenvolvida durante o **Módulo 9 do curso de Python / Ciência de Dados**, com foco em **pré-processamento de dados, modelagem preditiva e avaliação de modelos de regressão** utilizando a biblioteca **scikit-learn**.

O objetivo principal é **prever a nota final (G3)** de estudantes a partir de variáveis socioeconômicas, comportamentais e acadêmicas.

---

## 🧠 O que é feito neste projeto

Ao longo do notebook, são executadas as seguintes etapas:

1. **Importação de bibliotecas**

   * pandas, numpy
   * matplotlib
   * scikit-learn

2. **Carregamento e exploração dos dados**

   * Leitura do arquivo CSV
   * Visualização inicial do DataFrame
   * Análise de correlação com a variável alvo (G3)

3. **Análise exploratória (EDA)**

   * Gráficos de dispersão
   * Avaliação da relação entre faltas e nota final

4. **Tratamento de variáveis categóricas**

   * Conversão de variáveis binárias (yes/no → 1/0)
   * Uso de OneHotEncoder para variáveis categóricas

5. **Divisão dos dados**

   * Separação em conjunto de treino e teste
   * 75% treino e 25% teste

6. **Normalização dos dados**

   * Padronização das variáveis numéricas com StandardScaler

7. **Pipeline de pré-processamento**

   * Função personalizada para:

     * Codificação de variáveis categóricas
     * Normalização
     * Separação entre X (features) e y (target)

8. **Treinamento de modelos**

   * Regressão Linear
   * KNN Regressor
   * Árvore de Decisão

9. **Avaliação dos modelos**

   * Métrica RMSE
   * Métrica R²
   * Validação cruzada (Cross Validation)

10. **Seleção do modelo final**

    * KNN com 10 vizinhos
    * Avaliação final no conjunto de teste

11. **Visualização dos resultados**

    * Gráfico de valores reais vs previstos

---

## 📁 Estrutura do repositório

```
📂 projeto-modulo-9
 ├── atividade modulo 9.ipynb
 ├── dataframe_exercicio_modulo_9.csv
 └── README.md
```

---

## 📦 Bibliotecas utilizadas

* pandas
* numpy
* matplotlib
* scikit-learn

---

## ▶️ Como executar o projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Instale as dependências:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Abra o notebook:

   ```bash
   jupyter notebook
   ```

4. Execute as células em ordem.

---

## 🎯 Resultado

O modelo final selecionado foi o **KNN Regressor (k = 10)**, apresentando bom desempenho em termos de **RMSE** e **R²**, demonstrando a eficácia do pré-processamento e da validação cruzada aplicada.

---

## 👤 Autor

Projeto desenvolvido por **Samuel Lopes**
Estudante de Ciência de Dados | Python | SQL | Machine Learning

---

📌 *Este projeto faz parte de atividades educacionais e tem como objetivo aprendizado e prática em Ciência de Dados.*
