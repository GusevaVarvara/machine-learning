# Weather Prediction on the Rain in Australia Dataset

Репозиторий содержит практические работы по курсу «Машинное обучение», выполненные на основе одного общего набора данных, что позволяет сравнивать различные методы машинного обучения на одной задаче.

## Dataset

Для исследования был выбран датасет Rain in Australia:
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

Набор данных содержит ежедневные метеорологические наблюдения за 10 лет из различных регионов Австралии. Целевая переменная — *RainTomorrow*, определяющая, будет ли дождь на следующий день (*Yes* / *No*). Задача бинарной классификации.

## Содержание репозитория

В ходе выполнения практических работ были рассмотрены основные этапы построения моделей машинного обучения:

* первичный анализ и исследование данных;
* обработка пропусков, выбросов и некорректных типов данных;
* кодирование категориальных признаков;
* масштабирование данных и разделение выборки на обучающую, валидационную и тестовую;
* анализ распределений, корреляций и дисбаланса классов;
* обучение и сравнение различных моделей машинного обучения;
* подбор гиперпараметров, в том числе с использованием Optuna;
* оценка качества моделей по различным метрикам;
* исследование архитектур глубокого обучения и анализ их устойчивости.

В рамках проекта были реализованы и исследованы следующие методы:

* Logistic Regression,
* Support Vector Machine (SVM),
* Linear / Quadratic Discriminant Analysis (LDA/QDA),
* Decision Tree,
* Random Forest,
* Gradient Boosting и его современные реализации,
* нейронные сети различных архитектур,
* архитектуры глубокого обучения с подбором гиперпараметров.

Цель работы — сравнить эффективность различных алгоритмов классификации при прогнозировании выпадения осадков на следующий день и изучить полный цикл построения моделей машинного обучения: от подготовки данных до анализа качества полученных результатов.

| Файл | Colab |
|---|---|
| [1_data_preprocessing_and_eda.ipynb](./1_data_preprocessing_and_eda.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/18Q3VaG4-zlDW4fyuT2ItsGs8L6pHxBzd?usp=sharing) |
| [2_logistic_regression_and_svm.ipynb](./2_logistic_regression_and_svm.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1algfim5Y3TlsqJqn_ifBY8ySZ0SsYaLF?usp=sharing) |
| [3_discriminant_analysis_and_plsa.ipynb](./3_discriminant_analysis_and_plsa.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1Tp_Z5O5z-6BTpsFmROEtMQTqCh4wM-_t?usp=sharing) |
| [4_decision_trees_and_random_forest.ipynb](./4_decision_trees_and_random_forest.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1DMmDpml-Xi_nRJ-cjqb0yCya8KiSRmF8?usp=sharing) |
| [5_gradient_boosting_models.ipynb](./5_gradient_boosting_models.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1Hbg1-JCTUC-fv7j7ETT5RaakWam0Uo4a?usp=sharing) |
| [6_neural_networks_comparison.ipynb](./6_neural_networks_comparison.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1HJrsDQXb7DyknI-lKSmBBN_5nmspCZR-?usp=sharing) |
| [7_deep_learning_architectures.ipynb](./7_deep_learning_architectures.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/17Y7FD1htHEQAn9L2g5K5QkJBzgQb43-i?usp=sharing) |
