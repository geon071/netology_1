# Задание №2 - Описание жизненного цикла задачи (разработки нового функционала)

1. (Менеджер) Сбор требований по задаче от заказчика
1. (Менеджер/Разработчик/Аналитик) Декомпозиция задачи на подзадачи, определение приоритета по реализации (от важных, 
до минорных)
1. (Разработчик) Написание кода
1. (Разработчик/Devops) Сборка/компиляция выкладка дистрибутива
1. (Разработчик/Devops) Деплой на тестовую среду
1. (Тестировщик/Devops) Запуск автотестов, прохождение ручных тест-кейсов
1. (Менеджер/аналитик) Проверка промежуточных результатов, сбор обратной связи от заказчика
1. (Разработчик/Тестировщик/Devops) При необходимости, корректировка, по результатам обратной связи заказчика, деплой 
на тест, прохождение тестов
1. (Разработчик/Devops) выкладка на prod по результатм успешных тестов и обратной связи заказчика

Как DevOps-инженер:
На всех этапах выше участие на уровне поддержки, при условии реализованных пайпов:
1. Компиляции/сборка кода, выкладка в Nexus
1. Пайп по деплою выложенного дистрибутива на тестовую среду (также и в prod), как часть деплоя, запуск автотестов по 
результату успешного разворачиванию дистрибутива (smoke тесты), отправка результата разработчику
1. Пайп запуска автотестов