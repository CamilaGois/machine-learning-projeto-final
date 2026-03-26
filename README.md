# machine-learning-projeto-final
Projeto final de Machine Learning - CDIA

Descrição

Este projeto implementa um Pipeline Completo de Machine Learning para recomendar a graduação mais indicada para estudantes, com base em características pessoais e preferências acadêmicas.
O modelo foi desenvolvido seguindo as boas práticas do ciclo CRISP-DM, incluindo análise exploratória, tratamento dos dados, modelagem, otimização e avaliação.
O projeto atende aos requisitos da atividade final, que solicita pipeline completo com preparação, treinamento, comparação de modelos e documentação.


Objetivo

Criar um modelo de Machine Learning capaz de prever a graduação mais indicada para um estudante com base em:

Dados pessoais
Preferências acadêmicas
Interesses

DataSet Utilizado
O dataset contém informações pessoais e preferências dos estudantes, além da graduação recomendada.

Variáveis Pessoais
Idade
Curso_Tecnico
Anos_Para_Formar

Preferências (escala 1 a 5)

Gosta_Matematica
Gosta_Programacao
Gosta_Biologia
Gosta_Fisica
Gosta_Quimica
Gosta_Arte_Design
Gosta_Comunicacao
Gosta_Negocios
Gosta_Historia
Gosta_Geografia

Classe Alvo
Graduacao_Indicada

Metodologia CRISP-DM

1. Entendimento do Problema

Recomendar automaticamente a graduação mais adequada ao perfil do estudante.

2. Entendimento dos Dados
Análise exploratória
Distribuição das variáveis
Identificação de padrões

3. Preparação dos Dados
Tratamento de dados categóricos
Normalização
Remoção de outliers
Feature engineering
PCA

4. Modelagem

Random Forest
Gradient Boosting
Logisic Regression
XGBoost
SVM
KNN
CATBOOST
Extra Trees 
Decision Tree
LigthGBM
HistGradientBoosting


5. Otimização 

Cross Validation (5-Fold)
GridSearch
StratifiedKFold

6. Métricas

Accuracy
F1-score
Confusion Matrix
Classification Report
Balanced Accuracy

7. Balanceamento das Classes

SMOTE - oversampling
compute_sample_weiht: pesos das classes

8. Pipeline do Projeto

Carregamento do dataset
Análise exploratória
Tratamento de dados
Feature engineering
Treinamento do algoritmo
Comparação de modelos
Registro e rastreamento dos experimentos (ex.: MLflow).
Escolha e salvamento do melhor modelo.

9. Resultados 

Acurácia
Ranking Final
Modelos Comparados 

10. Deploy


Graduacao_Indicada

