# THE-MARKET-testing-end-to-end

1. Для выполнения данных тестов на своей машине, вам необходимо установить Katalon Studio.
Инструкции по установке: https://docs.katalon.com/display/KD/Getting+Started
2. Необходимо выполнить интеграцию с Git: https://docs.katalon.com/display/KD/Git+Integration -> пункт "Configuration".
3. Клонировать данный проект в соответствии с инструкцией: https://docs.katalon.com/display/KD/Git+Integration -> пункт "Clone Project".
Далее запускать либо выборочные тесты из директории "Test Cases", либо группы тестов из директории "Test Suites". По умолчанию можно выбрать браузер Chrome либо Firefoх, при условии, что браузеры установлены.

Перечень имеющихся тестов:
- Authentication:
  - Negative
    - Incorrect login
    - Incorrect password
    - Password mismatch
  - Positive
    - Valid login
- Shopping
    - Browsing products
    - Filling shopping cart
    - Searching for products

