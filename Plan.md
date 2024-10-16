# **План тестирования приложения "Мобильный хоспис"**

## 1. Введение.

Тест-план разработан для организации проверки мобильного приложения "Мобильный хоспис", с целью выявить возможные ошибки и несоответствие требованиям.

## 2. Объект тестирования.

Мобильное приложение «Мобильный хоспис».
Приложение имеет функционал по работе с новостями хосписа и включает в себя:

- информацию о новостях и функционал для работы с ними;
- тематические цитаты;
- информацию о приложении.

### 2.1 «Границы» приложения

В приложении есть:

- Экран загрузки.

- Форма авторизации.
- Навигационная панель приложения.

  - В навигационную панель входят:

1. Меню.

   1.1. Main (главная страница).

   1.2. News (новости).

   1.3. About (о приложение).

2. Цитаты.
3. Log out (выход из приложения).

## 3. Тестируемый функционал приложения включает в себя:

- Авторизация в приложении.

- На вкладке Main - просмотр новостей и переход на вкладку News.

- На вкладке News - Refresh (обновление страницы новостей); фильтрация новостей по категориям и датам; переход на Control panel; публикация, редактирование и удаление новостей.
- На вкладке About - просмотр информации о приложении; ссылки на политику конфиденциальности и условия использования.

- Просмотр цитат на вкладке Цитаты.

- Выход из приложения.

## 4. Автоматизация сценариев проверки приложения:

- Раздел Авторизация:

  1. Проверка видимости форм экрана Авторизации.
  2. Авторизация с валидными данными.
  3. Авторизация с невалидными данными.
  4. Авторизация с пустыми полями.

- Раздел Главное меню:

  1. Проверка видимости форм экрана Меню.
  2. Открытие/скрытие всех новостей на вкладке.
  3. Переход с вкладки Меню на вкладку Новости.

- Раздел Новости:

  1. Проверка видимости форм экрана Новости.
  2. Открытие/скрытие содержания новостей.
  3. Фильтрация новостей.
  4. Переход назад на Главное меню.

- Раздел Новости - Панель управления:

  1. Проверка видимости форм экрана Панель управления.
  2. Открытие/скрытие содержания новостей.
  3. Редактирование новости.
  4. Удаление новости.
  5. Добавление новости с валидными данными.
  6. Добавление новости с пустыми полями.
  7. Переход назад на вкладку Новости.

- Раздел О приложении:

  1. Проверка видимости форм экрана О приложении.
  2. Переход по ссылке Политика конфеденциальности.
  3. Переход по ссылке Пользовательское соглашение.
  4. Переход назад.

- Раздел Цитаты:

  1. Проверка видимости форм экрана.
  2. Открытие описания цитат.

- Выход из учетной записи приложения.

## 5. Виды тестирования используемые при проверке приложения «Мобильный хоспис»:

- Функциональное тестирование (проверка работоспособности; юзабилити-тестирование).

- Нефункциональное тестирование (тестирование отказоустойчивости).

## 6. Интервальная оценка, с учётом рисков (в часах):

- Ознакомление с проектом и документацией - 3;
- Составление плана тестирования - 3;
- Составление чек-листа - 5;
- Составление тест-кейсов - 8;

- Проведение ручного тестирования - 2;
- Настройка окружения проекта - 10;

- Написание автоматизированных тестов - 24;
- Проведение автоматизированного тестирования - 0.5;
- Формирование отчета о тестировании - 1.

## 7. Перечень используемых инструментов для автоматизации тестирования:

1. Android Studio Jellyfish 2023.3.1 - среда разработки для работы с платформой Android;

2. Gradle 7.2 - система для автоматизации сборки приложений;
3. Java 8 - многоплатформенный, объектно-ориентированный язык программирования;

4. JUnit 4.13.2 - фреймворк для модульного тестирования программного обеспечения;

5. Espresso 3.4.0 - фреймворк для тестирования приложений и автоматизации тестирования;
6. Allure 2.4.0 - фреймворк для создания отчетов о результатах тестирования в автоматизированных тестовых сценариях.

## Окружение

Ryzen 7-5700u; 32GB RAM; Windows 11 Pro 22631.4169.

Тестирование: 6.67" Xiaomi Redmi Note 9 Pro, Android 10, MIUI Global 12.03, 6GB RAM.

Эмулятор: Pixel 7a API 29.

## Документация

- [Чек-лист](https://github.com/EugenPotapov/QAMID-Diplom/blob/main/Cases.xlsx)
- [Тест-кейсы](https://github.com/EugenPotapov/QAMID-Diplom/blob/main/Check.xlsx)
