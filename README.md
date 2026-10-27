# LAB — Bagging e Boosting com Iris

Projeto da disciplina de Inteligência Artificial da PUC-SP.

**Alunos:** Patrick Barreira (RA00334687) e Nicolas Mariano (RA00333111).

O notebook [`LAB_Bagging_Boosting_Iris_Patrick_Nicolas.ipynb`](LAB_Bagging_Boosting_Iris_Patrick_Nicolas.ipynb) classifica as espécies do dataset Iris, carregado com `vega_datasets`, e compara dois modelos do scikit-learn:

- `BaggingClassifier` com árvores de decisão;
- `GradientBoostingClassifier`.

Ele apresenta inspeção dos dados, divisão estratificada de treino e teste, acurácia, F1 macro, relatórios de classificação, matrizes de confusão e interpretação dos resultados. As células já foram executadas e os resultados estão salvos no arquivo.

## Como executar

Abra o notebook no [Google Colab](https://colab.research.google.com/) e use **Ambiente de execução → Executar tudo**. A primeira célula instala `vega_datasets` caso o pacote não esteja disponível; as demais bibliotecas são as usadas normalmente no ambiente Python do Colab.

> Antes de enviar a atividade, confirmar que nenhum outro grupo escolheu o dataset Iris, conforme a orientação do LAB.
