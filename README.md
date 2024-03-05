# Проект: Анализ резюме из HeadHunter


## Описание проекта

Проблематика: часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме. Это является помехой для рекомендательной системы HeadHunter, которая подбирает соискателям список наиболее подходящих вакансий, а работодателям — список наиболее подходящих специалистов.

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Однако прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и заключается цель данного проекта!


## Этапы проекта

* Базовый анализ структуры данных
* Преобразование данных
* Разведывательный анализ
* Очистка данных


## Исследование структур данных

Ознакомление с предоставленной базой данных и проверка данных на целостность.


## Преобразование данных

 Преобразование признаков, создание новых признаков и принципы их заполнения, очистка от "лишней информации" в признаках, измнение размерности данных в признаках и изменение типа признака, удаление неинформативных признаков, создание "признаков-мигалок" (one hot encoding), нормализация в рамках одного признака.


## Исследование зависимостей в данных

Исследование зависимостей в данных методом визуализации. Рассмотрено 10 визуализаций для сравнения, распределения и взаимосвязи признаков. Для каждого случая проведен анализ и представлен в тестовой форме.


## Очистка данных

Работа с дубликатами, ликвидация пропусков (удаление записей, заполнение константами) и решение проблемы выбросов и аномалий (ручная чистка и использование метода 3-х сигм).


## Итог:

В результате проведенной работы (преобразования, анализа, очистки), получена база данных 
подходящая для построения модели.


## Использованные инструменты и библиотеки
* matplotlib (3.8.2)
* numpy (1.26.1)
* pandas (2.1.3)
* plotly (5.18.0)
* seaborn (0.13.0)


## Ссылки на данные:

* Ссылка на базу данных с HH https://drive.google.com/file/d/1ISvntGLVxH0R0VCF4SPFmfGW_VxoLKZ8/view?usp=drive_link

* Для просмотра графиков пользуйтесь [nbviewer](https://nbviewer.org/).

* Ссылка на [проект](https://github.com/AlKirV/SF-HH-resume-analysis).




