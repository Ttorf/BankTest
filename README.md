Задание

1. Создать проект на языке Java с использованием фреймворка сборкми проектов maven.

2. В корневой pom добавить зависимости testng, selenium.

==========



Используя возможности данных инструментов написать тесты:



Тест 1

1) Открыть сайт rencredit.ru

2) Перейти на страницу "Вклад"

3) Выбрать чекбокс "В отделении банка"

4) Ввести сумму вклада

5) Передвинуть ползунок "На срок"

6) Выгрузить Печатную Форму "Общие условия по вкладам"



Дополнительное задание (по желанию и возможности). Необходима установка MSSQL EE

7) Записать все шаги в базу данных в столбцы "Дата и время начала шага", "Дата и время окончания шага", "Название шага"



Тест 2

1) Открыть сайт rencredit.ru

2) Перейти на страницу "Карта"

3) Ввести в поля "Фамилия", "Имя", "Мобильный телефон", "e-mail" значения

4) Выбрать чекбокс "Нет отчества"

5) Выбрать значение из выпадающего списка "Где вы желаете получить карту"



Дополнительное задание (по желанию и возможности). Необходимо скачать зависимости через pom файл Maven

https://habr.com/ru/company/sberbank/blog/358836/

https://github.com/allure-examples



6) Сформировать отчет allure. Дать описание всем шагам и название тесту.