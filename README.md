Цифровой прорыв

Чемпионат республики Карелия

«Прогнозирование оттока пользователей провайдера
телекоммуникационных услуг»

Условие задачи

Участникам чемпионата предстоит создать свое решение по
прогнозированию оттока с использованием данных о клиентах. В вашем
доступе находится информация о запросах пользователей к сайтам
конкурентов и история обращений в компанию.

Описание входных значений

train.csv — файл содержащий данные пользователей для тренировки. Где:
○ 1 - клиент ушел,
○ 0 - остался.
log.csv — содержит данные обращения пользователей.;
named.csv — лог днс-запросов к доменам конкурентов (rt.ru и sampo.ru).
type contract.csv - тип списания у пользователей, где:
○ 1 - посуточная,
○ 0 - помесячная.
submission.csv — пример файла для отправки.

Метрика

В качестве метрики выступает Recall по столбцу blocked.

P.S. Результаты получились посредственные, т.к. работа делалась за 1,5 дня, многое не успела сделать, что хотела (создание признаков).
