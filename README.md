## 1. Перечень автоматизируемых сценариев

**Предусловия к сценариям тестирования UI:**

1. Навигация с [главной страницы](https://netology.ru/) на [страницу формы](https://netology.ru/programs/qa) заявки на курс "Тестировщик" через каталог курсов раздел ["Программирование"](https://netology.ru/development) с проверкой фильтрации по курсам

![1](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/4d25d829-985a-4ba1-aacb-6d9c23e93a71)
![2](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/3172457b-4448-4970-8b9c-13659d3818fd)

2. Навигация с [главной страницы](https://netology.ru/) на [страницу формы](https://netology.ru/programs/qa) заявки на курс "Тестировщик" через ["Каталог курсов"](https://netology.ru/navigation) с проверкой фильтрации по курсам

![3](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/e837d88f-54a6-4a1d-a15d-97aa5c0b3f28)
![4](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/8a7194ce-94cb-40c9-aef6-eba2165a0260)

3. Навигация с главной страницы на страницу каталога курсов раздела ["Программирование"](https://netology.ru/development) через раздел "Направления обучения"

![5](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/3785736c-1873-4f74-a294-f9eecd90a9f5)

4. Навигация с футера [главной страницы](https://netology.ru/) на страницу ["Каталог курсов"](https://netology.ru/navigation)

![5_1](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/f81c591c-a3d9-4a0d-8c68-8c478f453679)

5. Навигация с футера [главной страницы](https://netology.ru/) на страницу ["Популярные курсы"](https://netology.ru/popular)

![5_2](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/1f46fb6e-a442-4786-b540-60a77d074718)


6. Навигация с футера [главной страницы](https://netology.ru/) на страницу каталога курсов раздела ["Программирование"](https://netology.ru/development)

![5_3](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/648826d4-6623-49b3-a505-ef5075b10786)


7. Навигация с [главной страницы](https://netology.ru/) на [страницу формы](https://netology.ru/programs/qa) заявки на курс "Тестировщик" через [рекламное предложение](https://netology.ru/navigation?filter=paid) на нижнем поле страницы с проверкой фильтрации по курсам

![6](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/56d098c6-b8ba-4f89-9c7c-21d4ce72673f)

![7](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/1a4ba5f0-6239-40e0-ac51-4270cc838634)

8. Переход со страницы курса ["Тестировщик ПО"](https://netology.ru/programs/qa#/) к [форме записи](https://netology.ru/programs/qa#/order) на курс

![8](https://github.com/andykucherenko/SummaryAutomationJava/assets/122628604/ac32beea-c0d4-472f-abda-fb5f8d378d6a)

**Сценарии тестирования UI:**

1. Успешная отправка валидно заполненной [формы записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО", включая проверку ввода действующего промокода (с изменением стоимости курса) и перехода на страницы с условиями [политики](https://netology.ru/legal/11) и [пользовательского соглашения](https://netology.ru/legal/6)
1. Появление сообщения "Должно состоять из букв" у поля "Имя" при заполнение его спецсимволами в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Должно состоять из букв" у поля "Имя" при заполнение его цифрами в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Должно быть не короче 2 символов" у поля "Имя" при заполнение его одной буквой в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Обязательное поле" у поля "Имя" при оставление поля пустым в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Номер в формате +9 (999) 999-99-99" у поля "Телефон" при заполнение поля 8 цифрами в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Номер в формате +9 (999) 999-99-99" у поля "Телефон" при заполнение поля 15 цифрами в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Обязательное поле" у поля "Телефон" при оставление поля пустым в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Появление сообщения "Устаревший промокод" у поля "Промокод" при вводе устаревшего валидного промокода в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО" 
1. Появление сообщения "Промокод не найден" у поля "Промокод" при вводе не валидного промокода в [формe записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"

**Сценарии тестирования API:**

1. Проверка статуса 200 и совпадения валидных* данных отправленных через UI [формы записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО" с данными в body POST-запроса к серверу и новыми данными из БД.
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого body в POST-запросе отправки [формы записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого значения у атрибута phone в body в POST-запросе отправки [формы записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"
1. Проверка статуса 500 и отсутствие новых записей в БД при отправке пустого значения у атрибута name в body в POST-запросе отправки [формы записи](https://netology.ru/programs/qa#/order) на курс "Тестировщик ПО"

**Примечание:*** Валидными значениями для полей являются:

* обязательное поле "Имя": латиница, кириллица, пробел и дефис/тире, заполненный минимум двумя буквами
* обязательное поле "Телефон": цифры, круглые скобки, пробел и дефис/тире в формате +9 (999) 999-99-99, от 9 до 14 символов включительно
* не обязательное поле "Промокод": латиница, кириллица, цифры и спецсимволы, кроме пробела

## 2. Перечень используемых инструментов с обоснованием выбора

1. **IDE:** IntelliJ IDEA
1. **Язык программирования:** Java
1. **Система сборки:** Gradle (легче настраивать зависимости)
1. **Тестовая среда:** TestNG (имеет, по сравнению с JUnit, больше аннотаций для управления состоянием SUT (например @BeforeSuite, @AfterSuite), может разбивать тесты на наборы тестов (suite) и имеет больше возможностей по параметризации тестов)
1. **Система репортинга:** Allure (более сложные системы репортинга будут излишни)
1. **Фреймворк для UI тестирования:** Selenide (популярный и простой инструмент)
1. **Фреймворк для API тестирования:** REST Assured вместе с JSON Schema Validator (для отправки необходимых запросов и валидации JSON схемы)
1. **Фреймворки для управления данными:** Java Faker (для генерации данных), необходимый драйвер (в зависимости от диалекта) для подключения к БД и DBUtils (для чтения записей с БД), Gson (для генерации body запросов при API тестирования)

## 3. Перечень необходимых разрешений/данных/доступов

1. Разрешение на проведение автотестирования
1. Доступ на чтения БД
1. Доступ к существующим тестовым данным (если они есть)

## 4. Перечень и описание возможных рисков при автоматизации

1. Появление "мусорных" записей в БД
1. "Ложные" запросы к менеджерам на обратный звонок
1. Дополнительная нагрузка на сервер
1. Потеря актуальности тестов при изменение UI сайта, особенно это касается переход к записи на курс через рекламный баннер

## 5. Перечень необходимых специалистов для автоматизации

Данный проект не сложный, поэтому будет достаточно junior инженера по автоматизации, который знаком с основами необходимого инструментария, основами UI и API тестирования и базовыми навыками написания автотестов с использованием паттерна Page Object.

## 6. Интервальная оценка с учётом рисков (в часах)

После согласования всех необходимых соглашений и доступов, у juniar специалиста написание тестов займет 16 - 24 часа.






