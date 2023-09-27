# Портфолио: инженер по тестированию

## Обо мне 

Привет! Меня зовут Денис, я начинающий тестировщик. <br>
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
``Jira``,``qase.io``,``SQL``,`` Postman``,``Swagger``, ``Trello``<br>
``Miro``, ``pgAdmin``, ``Mockoon``, ``Jmeter``, ``Sitechco``, ``Checkvist``, ``Confluence``<br>, ``Android Studio``, ``xCode``, ``Charles``, ``Git``, ``Chrome DevTools``.


## Проекты

<h3>Проект 1: тест веб-приложения для учителей от Skyeng</h3>
<p><i>Продукт</i>: Веб-приложение для учителей от Skyeng, вкладка «Расписание»<br>
<i>Заказчик</i>: "Skyeng"<br>
<i>Основные требования (главная user-story)</i>: предоставить возможность учителям использовать личные события в расписании, которые служат напоминанием, что что-то запланировано на это время.</p>
<p>Что нужно было сделать: 
<ol>
  <li>Для тестирования веб-приложения для учителей Skyeng были составлены и проведены следующие виды тестирования:</li>
    <ul> 
  <li>Тестирование требований (проводилось для того, чтобы требования были понятны и однозначны для всех, полными и не противоречивыми);</li>
  <li>Приемочное тестирование;</li>
  <li>Smoke-тестирование. Проверка критически важных функций и стабильности системы в целом перед более тщательное тестированием;</li>
  <li>Функциональное (система+компоненты+интеграция);</li>
  <li>UX/UI;</li>
  <li>Нагрузочное;</li>
  <li>Тестирование безопасности;</li>
  <li>Проверка совместимости;</li> 
  <li>Регрессивное тестирование итогового проекта.</li>
    </ul>
  <li>Была создана декомпозиция веб-приложения для учителей от Skyeng, вкладка "Расписание";</li>
   <img src="https://github.com/salomio/my-works/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2026.09.23_01.11.46.png"><br>
  <li>Составлено расписание тестирования: кто из тестировщиков и когда будет проводить своё тестирование (в данном проекте тестировщик был один - я, поэтому составил таблицу с этапами проекта и когда с ними работал)</li>
  <li>При приемочном тестировании был выявлен серьезный баг. Также выявились баги по совместимости с мобильными устройствами, и некоторыми браузерами, но ниболее критичный баг был выявлен при регрессивном тестировании ;</li>
  <li>В завершении проекта был составлен отчёт о проведённом тестировании, где указали виды тестирования, сколько было затрачено время на проект, описаны баги и результаты по проекту.</li>
</ol></p>
<p>В данном проекте были использованы такие инструменты  "Confluence", "Miro", "qase.io", "Sitechco", "Jira".</p>
<p>Как решал: <a href="https://mifune.atlassian.net/wiki/spaces/1/overview">Ссылка на проект</a></p> 

<p>Логин: rc88@mail.ru
<p>Пароль: Takezo2022

 <p>Выводы (итоги):<br>
<ol>
  <li>Составил тест-план;</li>
  <li>Подготовил тестовую документацию;</li>
  <li>Провел несколько видов тестирования (приёмочное, функциональное, smoke-tetting и регрессивное);</li>
  <li>Написал подробный отчёт о проведённых результатах тестирования, c выводами и рекомендациями.</li>
</ol></p>

<h3>Проект 2: тест кабинета учителя в приложении Skyeng</h3>
<p>Проект 2 является продолжением Проекта 1, только тут мы в тестирование добавляем API.</p>
<p><i>Продукт</i>: Веб-приложение для учителей от Skyeng, вкладка "Расписание"<br>
<i>Заказчик</i>: "Skyeng"<br>
<i>Основные требования (главная user-story)</i>: предоставить возможность учителям использовать личные события в расписании, которые служат напоминанием, что что-то запланировано на это время.</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>К ранее созданным тест-кейсам Проекта 1 добавил тест-кейсы для API;</li>
  <li>Коллекция для проведения тестирование API содержала:  <a href="https://docs.google.com/document/d/1W-jerOugJnkTJw5iQtUTG7WHK4fAcO5pgjayGdlrkiE/edit?usp=sharing">Ссылка на коллекцию API</a></p>

  <ul>
    <li>Метод POST, так как в документации к проекту был указан только этот метод;</li>
    <li>11 различных проверок как позитивные, так и негативные:</li>
    <ul>
      <li>Открыть "Расписание" на портале учителя;</li>
      <li>Проверка кнопки + и появление формы создания события;</li>
      <li>Нажатие на пустой слот и появление формы создания событий;</li>
      <li>Создание личного события сегодня с пустым полем в описании;</li>
      <li>Создание личного события в прошлом с японскими иероглифами и юникодом в названии;</li>
      <li>Создание личного события в будущем с маркдаунами в поле описании;</li>
      <li>Изменение названия личного события, даты, времени и описания;</li>
      <li>Изменение цвета события на не валидный (оранжевый);</li>
      <li>Перенести событие на один год вперед;</li>
      <li>Перенести событие на два года назад;</li>
      <li>Удаление личного события;</li>
      
  <li>В "Variables" были занесены такие данные как ссылка на веб-приложение, версия и токен и заменены на свои значения "BaseUrl", "token";</li>
  <img src="https://github.com/salomio/my-works/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2025.09.23_23.35.43.png"><br>
  <img src="https://github.com/salomio/my-works/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2026.09.23_00.37.49.png"><br>
  <li>Использовались скрипты для запоминания id, статуса и времени ответа:<br> 
    
 <img src="https://github.com/salomio/my-works/blob/main/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2026.09.23_01.03.12.png"><br>

<li>В завершении тестирования Проекта 2 был дополнен отчёт об тест-ране API-коллекции в результатах тестирования Проекта 1.</li>
</ol>
<p>В данном проекте были использованы такие инструменты "qase.io", "Confluence", "Postman".</p>
<p>Как решал: <a href="https://app.qase.io/project/K1?case=2&suite=6">Тест кейс в qase.io</a><br>

<p>Логин: rc88@mail.ru
  
<p>Пароль: TAKEZO2022
<ol>
  <li>Дополнил тест-план из 1 проекта;</li>
  <li>Создал коллекцию в Postman;</li>
  <li>Провел тест-ран;</li>
  <li>На основе полученных результатов тест-рана дополнил отчёт о тестировании.</li>
</ol></p>

<h3> Проект 3: тест мобильного приложения Skyeng для изучения английского языка</h3>
<p><i>Продукт</i>: мобильное приложение для учеников от Skyeng, разделы «Ситуации» и «Видеопрактика» (приложение App version: Skyeng 9.71.0._skyeng/rc/9.71.0_08/11_14:31(576); SDK 6.4)<br>
<i>Заказчик</i>: "Skyeng"<br>
<i>Основные требования (главная user-story)</i>: Корректная работа разделов «Ситуации» и «Видеопрактика» мобильного приложения Skyeng для изучения английского языка .</p>
<p>Что нужно было сделать: 
<ol>
<li>Для тестирования веб-приложения для учителей Skyeng были составлены и проведены следующие виды тестирования:</li>
<ul> 
<li>Тестирование требований (проводилось для того, чтобы требования были понятны и однозначны для всех, полными и не противоречивыми);</li>
<li>Функциональное (система+компоненты+интеграция);</li>
<li>Инсталляционное тестирование;</li>
<li>Тестирование локализации и глобализации;</li>
<li>Тестирование производительности;</li>
<li>Тестирование совместимости.</li>
    </ul>
 
<li>Составлено расписание тестирования: кто из тестировщиков и когда будет проводить своё тестирование (в данном проекте тестировщик был один - я, поэтому составил таблицу с этапами проекта и когда с ними работал)</li>
<li>Было протестировано 2 тест-сюита, всего 18 тест-кейсов для разделов «Ситуации» и «Видеопрактика» приложения Skyeng и было выявлено 10 багов, из которых у 5 серьезность  - Critical.;</li>
<li>В завершении проекта был составлен отчёт о проведённом тестировании, где указали виды тестирования, сколько было затрачено время на проект, описаны баги и результаты по проекту.</li>
<ol>
<p>тест ран раздела «Ситуации»:<p>
<ol>
<p>тест ран раздела «Видеопрактика»:<p>
</ol></p>
<p>В данном проекте были использованы такие инструменты "Confluence", "qase.io", "Jira", "Charles".</p>
<p>Как решал: <a href="https://mifune.atlassian.net/wiki/spaces/~636416647d4645af4f0442fb/pages/19791873">Ссылка на проект</a></p> 

<p>Логин: rc88@mail.ru
<p>Пароль: Takezo2022

 <p>Выводы (итоги):<br>
<ol>
<li>Составил тест-план;</li>
<li>Подготовил тестовую документацию;</li>
<li>Провел несколько видов тестирования (Тестирование требований, Функциональное (система+компоненты+интеграция), Инсталляционное тестирование, Тестирование локализации и глобализации, Тестирование производительности, Тестирование совместимости);</li>
  <li>Написал подробный отчёт о проведённых результатах тестирования, c выводами и рекомендациями.</li>
</ol></p>


<h3> Проект 4: тест веб-приложения для учителей и мобильного приложения для учеников от Skyeng</h3>
<p><i>Продукт</i>: Веб-приложение для учителей от Skyeng и мобильное приложение для учеников (App version: Skyeng 9.87.0(654); SDK 6.4) раздел "Видеопрактика" <br>
<i>Заказчик</i>: "Skyeng"<br>
<i>Основные требования (главная user-story)</i>: Учитель пользуется только веб-приложением, в разных операционных системах и браузерах. Ученик  использует только мобильное приложение, на разных операционных системах.
.</p>
<p>Что нужно было сделать: 
<ol>
<li>Для тестирования веб-приложения для учителей Skyeng были составлены и проведены следующие виды тестирования:</li>
<ul> 
<li>Инсталляционное тестирование (установки);</li>
<li>Функциональное (система+компоненты+интеграция);</li>
<li>Тестирование совместимости;</li>
<li>Тестирование локализации и глобализации;</li>
<li>Тестирование производительности;</li>
<li>Тестирование прерываний;</li>
<li>Тестирование API.</li>
    </ul>
 
<li>Составлено расписание тестирования: кто из тестировщиков и когда будет проводить своё тестирование (в данном проекте тестировщик был один - я, поэтому составил таблицу с этапами проекта и когда с ними работал)</li>
<li> Был протестирован 1 чек-лист для мобильного приложения ученика, 3 чек-листа для веб-приложения П, создана 1 коллекция в postman  для веб-приложения П. Всего для было выявлено 15 багов, из которых у 1 серьезность - Critical ("Сбой видеоурока при случайном выходе из мобильного приложения на главный экран телефона") и 1 серьезность - Blocked ("Не отображается видео во время видеоурока в веб-комнате с П.") 
  <li>В завершении проекта был составлен отчёт о проведённом тестировании, где указали виды тестирования, сколько было затрачено время на проект, описаны баги и результаты по проекту.</li>
</ol></p>
<p>В данном проекте были использованы такие инструменты "Confluence", "qase.io", "Jira", "Postman".</p>
<p>Как решал: <a href="https://mifune.atlassian.net/wiki/spaces/~636416647d4645af4f0442fb/pages/edit-v2/21790721">Ссылка на проект</a></p> 

<p>Логин: rc88@mail.ru
<p>Пароль: Takezo2022

 <p>Выводы (итоги):<br>
<ol>
 <li>Составил тест-план;</li>
 <li>Подготовил тестовую документацию;</li>
 <li>Провел несколько видов тестирования (Инсталляционное тестирование (установки), Функциональное (система+компоненты+интеграция), Тестирование совместимости, 
 Тестирование локализации и глобализации, Тестирование производительности, Тестирование прерываний, Тестирование API.);</li>
 <li>Написал подробный отчёт о проведённых результатах тестирования, c выводами и рекомендациями.</li>
</ol></p>
 


## Контактная информация
- Email: rc88@mail.ru
- Telegram: https://t.me/+79147901136
- WhatsApp: +79147901136
