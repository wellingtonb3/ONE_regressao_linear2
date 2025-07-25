# ONE_regressao_linear2
Módulo do Curso #ONE Regressão Linear 2

### 📘 Regressão Linear para Precificação Imobiliária

**Curso: ONE - Oracle Next Education | Plataforma: Alura**
**Tema: Análise de preços de imóveis com Python e Ciência de Dados**

---

### 🎯 **Objetivo do Projeto**

Estimar o valor de imóveis no Rio de Janeiro com base em variáveis explicativas, por meio de regressão linear. O foco foi entender as relações entre as variáveis, aplicar transformação logarítmica para reduzir a assimetria e construir modelos preditivos avaliando sua performance estatística e visual.

---

### 🔍 **Etapas do Projeto**

#### **📂 Pré-Análise de Dados**

* Importação da biblioteca `pandas`
* Leitura e visualização do dataset
* Verificação do tamanho e estatísticas descritivas
* Geração da matriz de correlação

#### **📊 Visualizações Iniciais**

* Configuração da formatação dos gráficos
* Box-plot da variável dependente (preço)
* Distribuição de frequências
* Gráficos de dispersão entre variáveis

#### **🔁 Transformação de Dados**

* Aplicação de log na variável dependente
* Nova distribuição de frequências (dados transformados)
* Gráficos de dispersão após transformação
* Análise da linearidade entre variáveis

#### **📈 Modelagem e Interpretação**

* Separação dos dados em treino e teste
* Estimativa do modelo linear
* Cálculo e interpretação do R² nos dados de treino e teste
* Previsões pontuais com o modelo
* Reversão da transformação logarítmica para reais
* Criação de simulador simples
* Interpretação dos coeficientes (inclusive elasticidades)
* Análise gráfica dos resíduos e previsões

---

### 🧠 **Resumo Crítico do Projeto**

Durante o projeto:

* Identificamos problemas de **assimetria** na variável resposta.
* Aplicamos a **transformação logarítmica** para corrigir a distribuição.
* Verificamos que apenas após a transformação os dados apresentaram **relação linear mais clara**.
* Modelamos, estimamos e interpretamos os resultados, compreendendo tanto os **coeficientes** quanto o impacto prático no mercado imobiliário.

---

### 📌 **Ferramentas e Bibliotecas Utilizadas**

* Google Colab
* Python
* pandas, numpy
* matplotlib, seaborn, plotly
* statsmodels, sklearn

---

### 🧪 **Resultados**

* Modelo final interpretável
* R² razoável para o escopo do projeto educacional
* Simulador funcional de precificação
* Conhecimento prático de transformação e análise residual


