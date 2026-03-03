# 📉 Previsão de Evasão de Clientes (Churn Prediction) - Telecom

## 📖 Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo preditivo de Machine Learning para identificar clientes com alta probabilidade de cancelar seus serviços (Churn) em uma empresa de telecomunicações. A partir da análise exploratória e modelagem de dados, o projeto também extrai os principais fatores de risco e retenção para embasar a tomada de decisão estratégica do negócio.

## 🎯 O Problema de Negócio
A evasão de clientes é um dos maiores ralos de receita no setor de telecomunicações. Identificar preventivamente quais clientes estão insatisfeitos permite que a equipe de retenção atue de forma proativa, oferecendo descontos, novos combos ou suporte especializado antes que o cancelamento seja efetivado.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python
* **Ambiente de Desenvolvimento:** Google Colab
* **Manipulação e Limpeza de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Regressão Logística, Random Forest)
* **Tratamento de Dados Desbalanceados:** `imblearn` (SMOTE)

## ⚙️ Estrutura e Etapas do Projeto
1. **Coleta e Limpeza de Dados:** Tratamento de valores nulos e conversão de tipos.
2. **Engenharia de Recursos (Feature Engineering):** Transformação de variáveis categóricas em numéricas utilizando One-Hot Encoding (`pd.get_dummies`).
3. **Análise Exploratória (EDA):** Identificação de padrões através de Boxplots, Gráficos de Dispersão e Matriz de Correlação.
4. **Pré-processamento:**
   * Divisão dos dados em Treino (80%) e Teste (20%) com estratificação.
   * Balanceamento da classe minoritária nos dados de treino utilizando **SMOTE**.
   * Padronização de variáveis contínuas com **StandardScaler**.
5. **Modelagem e Avaliação:** Treinamento e comparação entre Regressão Logística e Random Forest focando em métricas de negócio (Recall, F1-Score e Matriz de Confusão).

## 🚀 Como Executar o Projeto

1. Faça o clone deste repositório:
   bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)



2. Acesse o Google Colab (https://colab.research.google.com/).
3. Faça o upload do arquivo `.ipynb` presente neste repositório.
4. Certifique-se de fazer o upload do dataset (`base_dados_telecom.csv` ou similar) para o ambiente do Colab.
5. Execute as células sequencialmente (Shift + Enter). *Nota: O Google Colab já possui a maioria das bibliotecas instaladas nativamente.*

## 📊 Principais Resultados e Conclusões

* **Modelo Vencedor:** A **Regressão Logística** apresentou o melhor desempenho para o contexto do negócio, alcançando um **Recall de 64%** na detecção de churn (superando os 59% do Random Forest, que apresentou forte *overfitting*).
* **Fatores de Risco:** Cobranças mensais/totais elevadas e contratos sem serviço de internet são os maiores causadores de cancelamento.
* **Fatores de Retenção:** Serviços integrados como Suporte Técnico, Segurança Online e Backup Online funcionam como grandes barreiras contra a evasão, fidelizando o cliente.

## ✒️ Autor

**Mateus Rodrigues de Oliveira 🦖​**


