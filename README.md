# Краткое описание тем домашних заданий

## HW_03 - ML-EDA
В этом домашнем задании вы получите опыт подготовки данных и EDA (Exploratory Data Analysis), приблизившись к реальной работе с данными с помощью уже знакомых вам инструментов: `numpy`, `pandas`, `matplotlib` и `seaborn`.

Вы будет работать с задачей кредитного скоринга (оценка надёжности клиента). Предоставляются данные о 1000 клиентов, про которых известно около 20 признаков и положительная или отрицательная оценка в качестве кредитуемого. Эти данные нужно будет подготовить, исследовать (в том числе с помощью средств визуализации) и даже попробовать предложить какую-нибудь формулу для условной оценки надёжности клиентов исходя из предоставленных данных. Описание данных: https://www.rdocumentation.org/packages/evtree/versions/1.0-8/topics/GermanCredit


## HW_04 - ML-knn-linreg

### KNN

В первой части ноутбука мы изобразим решающую поверхность для классификатора kNN, чтобы наглядно увидеть, как классификатор принимает решения для новых объектов. Для простоты будем работать со встроенным в sklearn набором данных wine, содержащим информацию о характеристиках трёх видов вина. Описание набора можно найти [здесь](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html#sklearn.datasets.load_wine) и [здесь](https://rdrr.io/cran/rattle.data/man/wine.html).

### Linear Regression

В этом задании мы рассмотрим различные аспекты построения линейной модели. Мы будем работать с одним из классических наборов данных в статистике, содержащим информацию о бриллиантах. Описание можно посмотреть [здесь](https://www.kaggle.com/datasets/shivam2503/diamonds).


## HW_05 - ML-gradient-descent

### Gradient descent
В этом домашнем задании вы напишете градиентный спуск для линейной регрессии, а так же посмотрите, как он ведёт себя с разными параметрами и разными функциями потерь.

### Алгоритм имитации отжига

Градиентный спуск — далеко не единственный метод оптимизации. Другой очень известный метод называется ["Алгоритм имитации отжига"](https://ru.wikipedia.org/wiki/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_%D0%B8%D0%BC%D0%B8%D1%82%D0%B0%D1%86%D0%B8%D0%B8_%D0%BE%D1%82%D0%B6%D0%B8%D0%B3%D0%B0). Он не так часто используется для оптимизации моделей машинного обучения, но у вас есть уникальная возможность попробовать применить его к нашей любимой линейной регрессии.


## HW_06 - Классификатор текстов (твитов)

Данные мы будем использовать из Kaggle соревнования: https://www.kaggle.com/competitions/nlp-getting-started/data

Оттуда надо скачать файл train.csv.

Нам предстоит решать задачу бинарной классификации - определять содержатся ли в твитте информация о настоящей катастрофе/инциденте или нет.

## HW_07 - Деревья. Случайный лес.

### Деревья
 
В перой части ноутбука необходимо запрограммировать функцию нахождения наилучшего порога для вершины решающего дерева и реализовать функцию предсказания рещающего дерева.

### Random Forest

Во второй части ноутбука необходимо построить модели с использованием бэггинга, модель случайного леса и модель решающего дерева, и сравнить результаты всех трёх моделей.

## HW_08 - Градиентный бустинг

В этой работы мы будем учиться предсказывать зарплату data scientist-ов в зависимочти от ряда факторов с помощью градиентоного бустинга
