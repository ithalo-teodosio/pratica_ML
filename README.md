# 🔍 Projeto de Machine Learning – Hackaton Unifacisa

Repositório contendo a resolução das **9 questões práticas de Machine Learning** propostas no Hackaton da Unifacisa. Os desafios envolvem classificação, regressão, clusterização e avaliação de modelos com foco em problemas reais de negócio, saúde, segurança e mercado financeiro.

---

## ✅ Questões Respondidas

### 🧠 Questão 1 - Regressão Linear (Preço de Imóveis)
**Tema:** Prever o preço de casas com base em variáveis como tamanho, número de quartos e localização.
- 📦 Bibliotecas: `pandas`, `numpy`, `matplotlib`, `scikit-learn`
- 🤖 Modelo: `LinearRegression`
- 📊 Avaliação: R² Score
- 📈 Resultado: Modelo simples, mas com bom poder preditivo.

### 🔐 Questão 2 - Detecção de Fraudes com Random Forest
**Tema:** Identificar transações fraudulentas com base em características transacionais.
- 📦 Bibliotecas: `make_classification`, `pandas`, `StandardScaler`, `RandomForestClassifier`, `classification_report`
- 🧪 Dataset sintético com 5% de fraudes
- 🤖 Modelo: `RandomForestClassifier`
- ✅ Acurácia: 97%
- 🧮 F1-Score para fraudes: 0.65
- 🔧 Melhorias possíveis: balanceamento de dados, SMOTE, otimização de hiperparâmetros

### 🛍️ Questão 3 - Segmentação de Clientes de E-commerce (K-Means)
**Tema:** Agrupar clientes com base em comportamento de compras.
- 📦 Bibliotecas: `pandas`, `numpy`, `matplotlib`, `KMeans`, `StandardScaler`
- 📊 Variáveis: quantidade de compras, valor gasto, frequência
- 📌 Técnica: `KMeans` + `Elbow Method`
- 📈 Clusters: 4 grupos definidos
- 🔍 Padrões encontrados:
  - Cluster 0: Baixo gasto, baixa frequência
  - Cluster 1: Alto gasto, baixa frequência
  - Cluster 2: Baixo gasto, alta frequência
  - Cluster 3: Alto gasto, alta frequência

### ❤️ Questão 4 - Clusterização de Dados de Saúde (PCA + K-Means)
**Tema:** Agrupar pacientes por perfil clínico (idade, IMC, glicose, colesterol, pressão)
- 📦 Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `StandardScaler`, `PCA`, `KMeans`, `silhouette_score`
- 🧬 Técnica de visualização: `PCA`
- 🤖 Clusterização: `KMeans`, K=3
- 📊 Interpretação dos grupos:
  - Cluster 0: Alto risco metabólico
  - Cluster 1: Perfil saudável
  - Cluster 2: Idosos com pressão/colesterol elevados
- 🔍 Silhouette Score: 0.46

### 📈 Questão 5 - Previsão de Ações com Regressão Linear
**Tema:** Prever preços de ações com base em volume e média móvel
- 📦 Bibliotecas: `pandas`, `numpy`, `matplotlib`, `scikit-learn`
- 🤖 Modelo: `LinearRegression`
- 🧮 Score R²: 0.72
- 💬 Observação: Aplicação introdutória, modelo simples

### 🎯 Questão 6 - Classificação Binária de Doença (Logistic Regression)
**Tema:** Prever presença de doença cardíaca com variáveis clínicas
- 📦 Bibliotecas: `LogisticRegression`, `train_test_split`, `accuracy_score`, `recall_score`
- 🤖 Modelo: `LogisticRegression`
- ✅ Acurácia: 86%
- 📢 Recall: 88% (boa detecção de positivos)

### 💡 Questão 7 - Classificação Multiclasse (Árvore de Decisão)
**Tema:** Classificar tipos de consumidores com base em perfil de consumo
- 📦 Bibliotecas: `DecisionTreeClassifier`, `pandas`, `train_test_split`
- 🤖 Modelo: `DecisionTreeClassifier`
- ✅ Accuracy: 84%
- ⚠️ Observação: Possível overfitting; ideal testar Random Forest ou poda

### 📊 Questão 8 - Clusterização com DBSCAN
**Tema:** Agrupar padrões de uso de aplicativo (número de acessos, tempo de uso, etc.)
- 📦 Bibliotecas: `DBSCAN`, `StandardScaler`, `matplotlib`, `pandas`, `numpy`
- 🔍 Técnica: `DBSCAN` (baseado em densidade)
- 🧩 Clusters encontrados: 3 grupos principais + outliers
- 🚀 Vantagem: detecta automaticamente ruídos nos dados

### 🧬 Questão 9 - Classificação com SVM (Câncer de Mama)
**Tema:** Diagnóstico de câncer com base em características celulares
- 📦 Bibliotecas: `SVC`, `StandardScaler`, `classification_report`
- 🤖 Modelo: `Support Vector Classifier`
- ✅ Accuracy: 93%
- 💡 Conclusão: Ótimo desempenho após normalização dos dados

---

## ⚙️ Tecnologias Usadas
- 🐍 Python 3
- 🧰 Bibliotecas principais:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`: modelos de ML, métricas, clustering

---

## 📁 Estrutura dos Arquivos
```
📂 ML_Hackaton_Unifacisa
├── Q1_regressao_linear_imoveis.ipynb
├── Q2_fraude_cartao.ipynb
├── Q3_kmeans_clientes.ipynb
├── Q4_clusters_saude.ipynb
├── Q5_regressao_acoes.ipynb
├── Q6_classificacao_doencas.ipynb
├── Q7_arvore_multiclasse.ipynb
├── Q8_dbscan_uso_app.ipynb
├── Q9_svm_cancer.ipynb
└── README.md
```

---

## 👤 Autor
**Ithalo Teodósio Nascimento**
- Estudante de Análise e Desenvolvimento de Sistemas – Unifacisa
- GitHub: [@ithalo-teodosio](https://github.com/ithalo-teodosio)

---

📢 *Este projeto foi desenvolvido como parte do Hackaton de Machine Learning da Unifacisa, com foco em aplicações reais de IA e ciência de dados.*

