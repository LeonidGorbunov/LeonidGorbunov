# Леонид Горбунов — QA Engineer (Automation & Manual)

QA Engineer (Java Automation & Manual). Разрабатываю фреймворки автоматизации на стеке Java + JUnit 4/5 + Selenium/Selenide + RestAssured, проектирую тестовую документацию и провожу сквозной тест-анализ Web, Mobile и API.

## Технологический стек и инструменты

* **Языки и сборка:** Java 11, SQL (PostgreSQL), JavaScript, Apache Maven
* **UI-автоматизация:** Selenide, Selenium WebDriver, WebDriverManager, Page Object
* **API-тестирование:** RestAssured, Postman (scripts, Chaining), Gson, Hamcrest
* **Тестирование и моки:** JUnit 4/5, Mockito, Datafaker, Lombok
* **Отчётность:** Allure Framework, JaCoCo
* **Инструменты:** Git / GitHub, Android Studio Emulator, Chrome DevTools

## Автоматизация тестирования (Java)

Ключевые проекты по автоматизации:

| № | Проект | Продукт и уровень | Стек | Отчёт |
| :--- | :--- | :--- | :--- | :--- |
| 1 | [java-ui-testing-burger-selenide-ju5](https://github.com/LeonidGorbunov/java-ui-testing-burger-selenide-ju5) | **Stellar Burgers** (E2E UI) | Java 11, JUnit 5, Selenide, RestAssured, Gson, Datafaker, Lombok, Allure |
| 2 | [java-ui-testing-burger-selenium-ju4](https://github.com/LeonidGorbunov/java-ui-testing-burger-selenium-ju4) | **Stellar Burgers** (E2E UI) | Java 11, JavaScript, JUnit 4, Selenium, RestAssured, Gson, Lombok, Allure |
| 3 | [java-api-testing-burger](https://github.com/LeonidGorbunov/java-api-testing-burger) | **Stellar Burgers** (REST API) | Java 11, JUnit 4, RestAssured, Gson, Lombok, Allure | [![Allure Report](https://img.shields.io/badge/Allure%20Report-Live-brightgreen)](https://leonidgorbunov.github.io/java-api-testing-burger/) |
| 4 | [java-api-testing-scooter](https://github.com/LeonidGorbunov/java-api-testing-scooter) | **Яндекс.Самокат** (REST API) | Java 11, JUnit 4, RestAssured, Gson, Lombok, Allure | [![Allure Report](https://img.shields.io/badge/Allure%20Report-Live-brightgreen)](https://leonidgorbunov.github.io/java-api-testing-scooter/) |
| 5 | [java-ui-testing-scooter](https://github.com/LeonidGorbunov/java-ui-testing-scooter) | **Яндекс.Самокат** (E2E UI) | Java 11, JUnit 4, Selenium, WebDriverManager |
| 6 | [java-unit-testing-burger](https://github.com/LeonidGorbunov/java-unit-testing-burger) | **Конструктор бургеров** (Unit) | Java 11, JUnit 4, Mockito, JaCoCo |
| 7 | [java-unit-testing-zoo](https://github.com/LeonidGorbunov/java-unit-testing-zoo) | **Учёт животных** (Unit) | Java 11, JUnit 4, Mockito, JaCoCo |

## Автоматизация API в Postman

* **[postman-api-testing-prilavok](https://github.com/LeonidGorbunov/postman-api-testing-prilavok)** — коллекция автотестов для сервиса **Яндекс.Прилавок (v3.1.1)** (317 запросов, включая сервисные/предусловия (202 фактические проверки), Chaining, Newman). См. документацию: [Чек-лист API и баг-репорты в Google Sheets](https://docs.google.com/spreadsheets/d/1DBqjCwPRBV2OShBDvjJS1uIe7LDJOKYIpPDlnzfm1vs/edit?gid=1667785858#gid=1667785858).

## Ручное тестирование и тест-анализ (Google Sheets)

* [Сервис проката Яндекс.Самокат — Комплексный тест-анализ Web, Mobile платформ и аудит СУБД — Тест-кейсы (для МП) & Баг-репорты](https://docs.google.com/spreadsheets/d/1JcFAjb3SilODrrkyZNkqmikOGgsVUKEoDeJt051woaE/edit?gid=1362767921#gid=1362767921) — матрица данных валидации, 47 тест-кейсов (МП), 326 кейсов в чек-листе с функциональными, сценарными кейсами и кейсами на верстку, SQL-аудит и 97 баг-репортов.
* [Сервис покупок и доставки Яндекс.Прилавок (REST API / XML) — Интеграционное тестирование, аутентификация/авторизация и стресс-валидация типов данных — Тест-комплект & Баг-репорты в Postman](https://docs.google.com/spreadsheets/d/1DBqjCwPRBV2OShBDvjJS1uIe7LDJOKYIpPDlnzfm1vs/edit?gid=1667785858#gid=1667785858) — 202 тест-кейса и 36 баг-репортов.
* [Мобильное приложение Яндекс.Метро (Android) — Тест-анализ логики состояний и системные регрессионные тесты — Комплект тест-кейсов & Баг-репорты](https://docs.google.com/spreadsheets/d/1k-7aqbYtUKSnAEElpyn3rfoewEdRBiXuEf89E7CEAPA/edit?gid=38436085#gid=38436085) — 55 функциональных тест-кейсов, 58 регрессионных тест-кейсов и 17 баг-репортов.
* [Мобильное приложение Яндекс.Метро (Android) — Высокоуровневое сценарное тестирование (End-to-End) и системные регрессионные тесты — Пользовательские Use Cases, комплект тест-кейсов & Баг-репорты](https://docs.google.com/spreadsheets/d/1bhdXsrb0DuTNdGMKL7lAfajD7eMh3i4XNB-buXaj6b4/edit?gid=1772884521#gid=1772884521) — 36 Use Cases, 56 регрессионных тест-кейсов и 15 баг-репортов.
* [Картографический сервис Яндекс.Маршруты (Web) — Комплексное тестирование UI/UX верстки и бизнес-логики в нескольких окружениях — Тест-комплект & Баг-репорты](https://docs.google.com/spreadsheets/d/1ZhRNV5yGj2tN5msqaGcSDGr5gzTej9T9uDVDkuR3E0k/edit?gid=140333562#gid=140333562) — 125 кейсов в чек-листе на верстку, 60 кейсов в чек-листе на логику и функционал модальных окон, 5 тест-кейсов логики кнопки и 39 баг-репортов.
* [Картографический сервис Яндекс.Маршруты (Web) — Тестирование логики расчета маршрутов и стоимости поездок — Тест-дизайн & Баг-репорты (С2)](https://docs.google.com/spreadsheets/d/172AmE-6J0KDrhJLbVFi8qepKj_CM3ScVAustkqNJom0/edit?gid=410519550#gid=410519550) — тест-анализ, матрица данных валидации, 70 тест-кейсов и 18 баг-репортов.
