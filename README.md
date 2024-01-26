# Classificação de vinhos baseado em suas características (Multiclass classification of wine based on its features)
Exercício proposto durante o curso: Classificação: resolvendo problemas multiclasse da Alura
Estudo: Criar um modelo de predição da qualidade de vinhos, usando como variável explicativa as características químicas do vinho, enquanto que a variável explicada é categórica e representa a qualidade dos vinhos segundo um painel de especialistas.

## Método
* Bibliotecas: pandas, seaborn, scikit-learn, imbalance-learn.
* Para o treino do modelo, utilizei principalmente a Random Forest Classifier, mas também foi testado os modelos de Gradient Boosting Classifier e KNeighbors Classifier.
* Notei que foi preciso balancear os dados.
* As métricas de avaliação utilizadas foram: a Matriz de confusão e o recall (para multiclasse weighted recall).

## Modelo final
![image](https://github.com/MotiMortal/Multiclass-classification-case-wine/assets/126615931/37bdf3cc-1a21-4ec8-add2-ed5d23a1a67b)
