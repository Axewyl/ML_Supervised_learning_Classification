# Проект-4. Прогнозирование оттока клиентов банка с помщью ML. Решение задачи классификации.

## Оглавлелние

[1. Описание проекта](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Описание-проекта)

[2. Какой кейс решаем?](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Какой-кейс-решаем)

[3. Краткая информация о данных](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Краткая-информация-о-данных)

[4. Этапы работы над проектом](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Этапы-работы-над-проектом)

[5. Результат](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Результаты)

[6. Авторы](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Авторы)

[7. Выводы](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Выводы)

### Описание проекта

Некоторый банк обратился к нам за помощью: он хочет разработать кампанию лояльности по удержанию клиентов. Для этого он хочет прогнозировать вероятности оттока клиентов и определять, уйдёт ли клиент в ближайшее время.

### Какой кейс решаем

Построить классификатор, который позволит своевременно определять уходящих клиентов банка, оценить качество построенных моделей и проинтерпретировать результаты.

**Описание задачи:**
Задачу, которая стоит перед нами, можно разбить на две части:

I.Часть (модель логистической регрессии) - Подготовим данные для моделирования; - Строим модель логистической регрессии; - Оценим её качество и проанализируем результаты её работы;

2.Часть (модель дерева решений и случайный лес) - построением моделей дерева решений; - построением моделей случайного леса; - сравнение результатов; - финальный вывод (пример работы)

**Метрика качества**

- Построенная модель оцениваются по метрике _f1_score_(оценка F1).

f1_score: чем она больше, тем лучше.

**Что практикуем**

- учимся использовать модель логистической регрессии;
- учимся использовать модель дерева решений;
- учимся использовать модель случайного леса;
- применяем простые способы поиска гиперпараметров;
- сравниваем выводы на основе метрики _f1_score_;
- делаем финальное решение.

### Краткая информация о данных

Значения столбцов таблицы:

- _RowNumber_ — номер строки таблицы;
- _CustomerId_ — идентификатор клиента;
- _Surname_ — фамилия клиента;
- _CreditScore_ — кредитный рейтинг клиента (чем он выше, тем больше клиент брал кредитов и возвращал их);
- _Geography_ — страна проживания клиента (банк межнациональный);
- _Gender_ — пол клиента;
- _Age_ — возраст клиента;
- _Tenure_ — сколько лет клиент пользуется банком;
- _Balance_ — сколько у клиента денег на счетах в банке;
- _NumOfProduct_ — число услуг банка, которыми воспользовался клиент;
- _HasCrCard_ — есть ли у клиента кредитная карта (1 — да, 0 — нет);
- _IsActiveMember_ — есть ли у клиента статус «активный клиент» (1 — да, 0 — нет);
- _EstimatedSalary_ — предполагаемая заработная плата клиента;
- _Exited_ — статус ушедшего (1 — ушедший клиент, 0 — лояльный клиент).

### Этапы работы над проектом

1. Постановка задачи;
2. Логистическая регрессия;
3. Деревья ршений и случайный лес;
4. Финальное решение.

### Результаты

Результатом служит значения показателя _f1_score_. На его основе мы можем сказать лучше или хуже предсказывает значение модель.

### Авторы

- [Andrey](https://t.me/Axewyl)

### Выводы

**Основное исследование:**

Благодаря данному проект мы смогли:

- научились применять модель логистической регрессии, дерева решений и случайного леса;
- примнять способы поиска подбора гиперпараметров;
- Искать графически наилучшее пороговое значения _threshold_ для повышений качества модели;
- давать оценку по метрике качества _f1_score_;

**Дополнительтное исследование:**

Для повышения качества модели можно:

- добавить новые признаки;
- использовать методы по сбалансированию воборок;
- применить кросвалидацию;
- использовать библиотеку _OPTUNA_ для поиска гиперпараметров;

:arrow_up:[к оглавлнию](https://github.com/Axewyl/ML_Supervised_learning_Classification/blob/master/README.md#Оглавлелние)
