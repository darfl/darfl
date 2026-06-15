<div id="header" align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeWFkYTQ0N3RweGw1ZmR3MzU5dmNveXF6aHZoZGUweGl4eGlpZnNuYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gw3IWyGkC0rsazTi/giphy.gif" width="100"/>
</div>

<img src="images/banner.png" alt="Диана — QA Engineer (Automation)" width="100%"/>

<img src="images/icons/java.svg" width="32" alt="Java"/> <img src="images/icons/Selenide.svg" width="32" alt="Selenide"/> <img src="images/icons/JUnit5.svg" width="32" alt="JUnit 5"/> <img src="images/icons/Allure.svg" width="32" alt="Allure"/> <img src="images/icons/Gradle.svg" width="32" alt="Gradle"/> <img src="images/icons/Selenoid.svg" width="32" alt="Selenoid"/> <img src="images/icons/Jenkins.svg" width="32" alt="Jenkins"/> <img src="images/icons/Telegram.svg" width="32" alt="Telegram"/>

<table align="center">
<tr><td bgcolor="#bd5aaf" align="center" style="padding: 12px 24px; border-radius: 8px;">
<b>Автоматизирую тестирование на Java: UI (Selenide) и REST API (RestAssured). Пишу поддерживаемые тесты с читаемыми отчётами Allure и запуском в CI.</b>
</td></tr>
</table>

## 🛠️ Стек

| Область | Инструменты |
|---------|-------------|
| Язык | <img src="images/icons/java.svg" width="16"/> Java 17+ |
| UI-тесты | <img src="images/icons/Selenide.svg" width="16"/> Selenide, Selenium, Page Object Model |
| API-тесты | RestAssured, Lombok POJO |
| Фреймворк | <img src="images/icons/JUnit5.svg" width="16"/> JUnit Jupiter 5 |
| Отчёты | <img src="images/icons/Allure.svg" width="16"/> Allure (кастомные шаблоны, @Step, аттачменты) |
| Сборка | <img src="images/icons/Gradle.svg" width="16"/> Gradle, Maven |
| Инфраструктура | <img src="images/icons/Selenoid.svg" width="16"/> Selenoid (Docker, VNC, видео) |
| Данные | JavaFaker, кастомные фабрики |

## 📂 Проекты

### [REST API Test Suite](https://github.com/darfl/rest-api-tests) — автотесты для API

Проверяю авторизацию, создание и обновление пользователей, получение ресурсов на тестовом сервисе Reqres.in. Вместо копипасты `given().header(...)` в каждом тесте — вынесла спецификации запросов и ответов в отдельный слой, описала модели через Lombok и настроила кастомные Allure-отчёты с curl-командами для каждого запроса. Упавший тест можно воспроизвести за секунду, не заглядывая в код.

### [DEMOQA](https://github.com/darfl/demoqa) — автотесты для UI

Тестирую форму регистрации на demoqa.com: полное заполнение, только обязательные поля, невалидный телефон. Использую Page Object Model — поля формы, календарь и таблица результатов живут в отдельных классах, тесты читаются как инструкция. Тесты гоняются в Selenoid (браузеры в Docker), после каждого — скриншот, логи и видео в Allure-отчёте. Специально сохранила исходный тест без Page Object, чтобы показать «до» и «после» рефакторинга.

### [Fair Split](https://github.com/darfl/test-project) — фулстек-приложение

Сплиттер совместных расходов на Spring Boot и React. Написала с нуля под свою потребность — считать, кто кому сколько должен после поездок с друзьями. REST API считает долги, фронтенд отображает результат.

## 💡 Что я умею

- **Пишу аккуратные тесты.** Никакой магии с захардкоженными URL и заголовками. Всё вынесено в спецификации и фабрики — если что-то меняется в API, правлю в одном месте, а не в десяти тестах.
- **Делаю отчёты, по которым видно, что упало.** Allure с шагами на русском, скриншотами, логами браузера и видео прогона. Никаких «красный крестик, гадайте сами».
- **Работаю с Selenoid.** Браузеры в Docker, VNC для отладки, запись видео — всё настраивается через переменные, не через код.
- **Генерирую данные с умом.** Город зависит от штата, email и телефон — случайные, но валидные. JavaFaker + кастомная логика.
- **Умею в CI-готовность.** Теги, фильтры, системные свойства — тесты готовы к запуску в пайплайне.
- **Понимаю, что тестирую.** Fair Split написан с нуля — знаю, как выглядит приложение с обратной стороны.

## 📫 Контакты

<a href="https://github.com/darfl"><img src="images/icons/GitHub.svg" width="20"/> github.com/darfl</a>  
<a href="https://t.me/darrrfl"><img src="images/icons/Telegram.svg" width="20"/> @darrrfl</a>
