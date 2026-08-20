# Building-the-best-classifier-for-sentiment-analysis
Machine learning project for classifying reviews by sentiment.
# Sentiment Analysis of Reviews

## О проекте

В этом проекте мы анализируем отзывы и определяем их тональность.

Есть 3 класса отзывов:
- позитивные
- нейтральные
- негативные

Всего в датасете 8 999 отзывов.

## Цель

Найти лучший вариант модели для определения тональности отзывов.

## Гипотеза

Мы предполагаем, что TF-IDF + Logistic Regression покажет лучший результат среди протестированных вариантов.

## Что мы сравнивали

Мы сравнили 3 варианта:

- TF-IDF + Logistic Regression
- Count + Logistic Regression
- TF-IDF + предобработка + Logistic Regression

Для сравнения использовали метрику Macro-F1.

## Результаты

Лучший результат показал:

**TF-IDF + Logistic Regression — Macro-F1: 0.684**

Другие результаты:

- Count + Logistic Regression — 0.674
- TF-IDF + предобработка + Logistic Regression — 0.662

Также для лучшей модели:

- Accuracy — 0.683
- Recall для позитивных отзывов — 0.835

Таким образом, наша гипотеза подтвердилась.

## Google Colab

Код и результаты находятся в Google Colab:

[Открыть Google Colab](https://colab.research.google.com/drive/1O_N1c8qdj8f2ZdPy4X27jGGcwf3bIEQi?usp=sharing)

## Вывод

Лучшим вариантом для нашего датасета оказался **TF-IDF + Logistic Regression**.

В дальнейшем можно попробовать другие модели и способы обработки текста.
