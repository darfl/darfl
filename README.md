<div id="header" align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeWFkYTQ0N3RweGw1ZmR3MzU5dmNveXF6aHZoZGUweGl4eGlpZnNuYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gw3IWyGkC0rsazTi/giphy.gif" width="100"/>
</div>

<img src="images/banner2.png" alt="Диана — QA Engineer (Automation)" width="100%"/>

<table align="center">
<tr><td bgcolor="#8d92d8" align="center" style="padding: 12px 24px; border-radius: 8px;">
<b>Автоматизирую тестирование на Java: UI (Selenide) и REST API (RestAssured). Пишу поддерживаемые тесты с читаемыми отчётами Allure и запуском в CI.</b>
</td></tr>
</table>


<img src="images/icons/java.svg" width="32" alt="Java"/> <img src="images/icons/Intelij_IDEA.svg" width="32" alt="IntelliJ IDEA"/> <img src="images/icons/visual-studio-code.svg" width="32" alt="VS Code"/> <img src="images/icons/Selenide.svg" width="32" alt="Selenide"/> <img src="images/icons/JUnit5.svg" width="32" alt="JUnit 5"/> <img src="images/icons/Allure.svg" width="32" alt="Allure"/> <img src="images/icons/Gradle.svg" width="32" alt="Gradle"/> <img src="images/icons/Selenoid.svg" width="32" alt="Selenoid"/> <img src="images/icons/Jenkins.svg" width="32" alt="Jenkins"/> <img src="images/icons/jira.svg" width="32" alt="Jira"/> <img src="images/icons/GitHub.svg" width="32" alt="GitHub"/> <img src="images/icons/Telegram.svg" width="32" alt="Telegram"/> <img src="images/icons/AllureTestOps.svg" width="32" alt="Allure TestOps"/>

## 🛠️ Мой стек технологий

| Область | Инструменты |
|---------|-------------|
| Язык | <img src="images/icons/java.svg" width="16"/> Java 17+ |
| UI-тесты | <img src="images/icons/Selenide.svg" width="16"/> Selenide, Page Object Model |
| API-тесты | <img src="images/icons/Rest-Assured.png" width="16"/> RestAssured, Lombok POJO |
| Фреймворк | <img src="images/icons/JUnit5.svg" width="16"/> JUnit Jupiter 5 |
| Отчёты | <img src="images/icons/Allure.svg" width="16"/> Allure (свои HTML-шаблоны с curl и подсветкой JSON, @Step, скриншоты, логи, видео) |
| Сборка | <img src="images/icons/Gradle.svg" width="16"/> Gradle |
| Инфраструктура | <img src="images/icons/Selenoid.svg" width="16"/> Selenoid (Docker, VNC, видео) |
| Данные | JavaFaker, кастомные фабрики |

## 📂 Примеры моих работ

### [REST API Test Suite](https://github.com/darfl/rest-api-tests) — автотесты для API

Проверяю авторизацию, создание и обновление пользователей, получение ресурсов на тестовом сервисе Reqres.in. В каждом тесте спецификации запросов и ответов вынесены в отдельный слой, описаны модели через Lombok и настроены Allure-отчёты с HTML-шаблонами, подсветкой JSON и curl-командами для каждого запроса. Упавший тест можно воспроизвести сразу, не заглядывая в код.

### [DEMOQA](https://github.com/darfl/demoqa) — автотесты для UI

Тестирую форму регистрации на demoqa.com: полное заполнение, только обязательные поля, невалидный телефон. Использую Page Object Model — поля формы, календарь и таблица результатов расположены в отдельных классах, тесты читаются легко, как инструкция. Тесты гоняются в Selenoid (браузеры в Docker), после каждого — скриншот, логи и видео в Allure-отчёте. Специально сохранила исходный тест без Page Object, чтобы показать «до» и «после» рефакторинга.

### [Fair Split](https://github.com/darfl/test-project) — фулстек-приложение

Сплиттер совместных расходов на Spring Boot и React. Написала с нуля под свою потребность — считать, кто кому сколько должен после поездок с друзьями. REST API считает долги, фронтенд отображает результат.

## 💡 Что я умею

- **Пишу аккуратные тесты.** Отсутствуют захардкоженные URL и заголовки. Всё вынесено в спецификации и фабрики. Если в API что-то меняется, можно исправить только в одном месте, а не в десяти тестах.
- **Делаю отчёты, по которым видно, что упало.** Allure с шагами на русском, скриншотами, логами браузера и видео прогона.
- **Работаю с Selenoid.** Браузеры в Docker, VNC для отладки, запись видео. Всё настраивается через переменные, а не через код.
- **Генерирую данные, вникая в контекст.** Например: город зависит от штата, email и телефон — случайные, но валидные. Используется JavaFaker в комбинации с кастомной логикой.
- **Умею в CI-готовность.** Теги, фильтры, системные свойства. Все тесты готовы к запуску в пайплайне.
- **Понимаю, что тестирую.** Fair Split написан с нуля — знаю, как выглядит приложение с обратной стороны.

## 📫 Контакты

<a href="https://github.com/darfl"><img src="images/icons/GitHub.svg" width="20"/> github.com/darfl</a>  
<a href="https://t.me/darrrfl"><img src="images/icons/Telegram.svg" width="20"/> @darrrfl</a>