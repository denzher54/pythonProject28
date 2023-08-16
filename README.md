# pythonProject28
Rostelecom website testing, testing object https://b2c.passport.rt.ru page.

Итоговая практическая работа по автоматизации тестирования. Руководствуясь техническими требованиями по проекту https://docs.yandex.ru/docs/view?url=ya-browser%3A%2F%2F4DT1uXEPRrJRXlUFoewruNAfoCDy4Jpwdj-ED-hzSvm6D2WVFKxRHhIhy6pIz-GJ_c-i83l2TLc2XYoViPbYkv0v_Ho8m7psQMuIg18dTDr4iGxTQlm_CPFxslymWahYAJvxFqd2Wl9SXpovq1U0bA%3D%3D%3Fsign%3Diqs6DPPArAsMwYVgGlDzITBn1tpP6yNQOeJeQTWVaaQ%3D&name=Требования_SSO_для_тестирования_last.doc) были составлены тест-кейсы [https://docs.google.com/spreadsheets/d/1tF0XLn_2vE-LU_PY2cfypHhjdP_pQ_CoJrsiaIx0ylI/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1R8A8ZQAbobbD31vC417WaHruKUZQCfcy8VDVCSfxdAA/edit?usp=sharing) и баг-репорты с использованием автотестирования на тест-кейсы проверяющие основной функционал тестируемого раздела сайта.

Задания по тестированию раздела:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)
Применялось тестирование по позитивному и негативному сценарию. Применялась техника тест-дизайна "Анализ граничных значений" в проверке поля ввода "Имя" формы регистрации.

В файле settings необходимо указать действующий логин, пароль зарегистрированного пользователя.

Назначение тестов приведено в комментариях.

Запуск тестов при помощи команд в консоли: python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests/test.py

Для правильной работы тестов необходимо установить библиотеки в Python 3:

pytest

pytest-selenium

selenium

urllib3
