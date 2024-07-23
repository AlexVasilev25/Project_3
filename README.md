![](./images/Machine_Learning.jpg)
# <center> Прогнозирование рейтинга отеля на Booking </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Установка проекта](#Установка-проекта)
4. [Авторы](#Авторы)
5. [Выводы](#Выводы)

## Описание проекта

`Представим, что мы работаем датасаентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.`

`Нам поставлена задача создать такую модель.`


Проект состоит из пяти частей:
1. Загрузка библиотек и данных.
2. Знакомство с данными.
3. Очистка данных.
4. Разведывательный анализ и генерация новых фичей(основная часть нашего проекта).
5. Обучение модели.


Целью проекта является отработка различных методов разведывательного анализа, понимание насколько важен разведывательный анализ для точности модели.

Вся остальная информация о проекте представлена в jupyter-ноутбуке [PROJECT-3.IPYNB](./PROJECT-3.IPYNB).

**О структуре проекта:**
* [images](./images) - папка с изображениями, необходимыми для проекта 
* [predict_submission.csv](./predict_submission.csv) - итоговый файл с предсказанными рейтингами
* [PROJECT-3.IPYNB](./PROJECT-3.IPYNB) - jupyter-ноутбук, содержащий основной код проекта.
* [requirements.txt](./requirements.txt) - текстовый файл, в котором указаны версии всех пакетов, используемых для создания проекта


## Описание данных
В нашем распоряжении есть три файла, они были взяты с соревнования на [Kaggle](https://www.kaggle.com/competitions/sf-booking/data).

* hotels_train.csv - набор данных для обучения
* hotels_test.csv - набор данных для оценки качества
* submission.csv - файл сабмишна в нужном формате

## Установка проекта

```
git clone https://github.com/AlexVasilev25/Project_3
```
## Авторы

* [Александр Васильев](https://t.me/alex_vasilev13)

[К оглавлению](#Оглавление)

## Выводы

Главной целью этого учебного проекта было отработать различные методы разведывательного анализа данных и построить модель для прогнозирования рейтинга отелей.

Проект позволил успешно отработать навыки работы с данными, включающие их предобработку, разведывательный анализ и построение моделей машинного обучения, EDA позволил глубже понять структуру и особенности данных, выявить важные закономерности.

 Итоговая модель предсказывает рейтинг отеля с метрикой MAPE, равной 0.1224, что свидетельствует о хорошем качестве прогноза. 
 Эта модель может быть использована для автоматической проверки рейтингов отелей и выявления случаев возможных манипуляций.
