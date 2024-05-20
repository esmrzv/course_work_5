В рамках проекта мы получаем данные о 10 выбранных компаниях и вакансиях с сайта hh.ru, создаем таблицы в БД PostgreSQL и загружаем полученные данные в созданные таблицы. Создан класс DBManager, который будет подключаться к БД PostgreSQL и иметь следующие методы:

получать список всех компаний и количество вакансий у каждой компании.
получать список всех вакансий с указанием названия компании, названия вакансии и зарплаты и ссылки на вакансию.
получать среднюю зарплату по вакансиям.
получать список всех вакансий, у которых зарплата выше средней по всем вакансиям.
получать список всех вакансий, в названии которых содержатся переданные в метод слово.