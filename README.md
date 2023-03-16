### План автоматизации тестирования сценария перехода к форме записи на курс «Тестировщик ПО» и заполнения этой формы:



1. Перечень автоматизируемых сценариев:
   
 - Проверка перехода на страницу курса «Тестировщик ПО» с главной страницы сайта Нетологии.

- Проверка наличия кнопки «Записаться» на странице курса «Тестировщик ПО».
- Проверка открытия формы записи на курс после нажатия на кнопку «Записаться».
- Проверка корректности заполнения формы (поля ФИО, телефон, email).
2. Перечень используемых инструментов с обоснованием выбора:
   

- Selenide – инструмент для автоматизации веб-приложений, позволяющий воспроизводить действия пользователя на странице.
- JUnit5 – фреймворк для написания и запуска автоматизированных тестов, позволяющий группировать тесты и проводить их параллельно.
- AppVeyor - для автоматической сборки проекта и запуска тестов в рамках CI/CD-процесса.
- Git - для хранения и управления версиями кода автотестов.
- Allure – инструмент для генерации отчетов о прогоне автоматизированных тестов, позволяющий визуально оценить результаты тестирования.


3. Перечень необходимых разрешений, данных и доступов:


- Доступ к сайту Нетологии и курсу «Тестировщик ПО».
- Данные для заполнения формы записи на курс (ФИО, телефон, email).


4. Перечень и описание возможных рисков при автоматизации:


- Изменение веб-сайта Нетологии без уведомления, что может повлечь за собой изменение локаторов элементов на страницах.
- Изменение валидации полей в форме записи на курс, что может привести к некорректной работе автоматизированных тестов.
- Риск блокировки IP-адреса автоматизированного тестирования из-за частых запросов к серверу Нетологии.


5. Перечень необходимых специалистов для автоматизации:


- QA инженер -  ответственный за разработку и реализацию тест-кейсов, сценариев тестирования и написание автотестов;
- Автоматизатор - специалист, отвечающий за выбор инструментов для автоматизации тестирования и реализацию автотестов.
  
1. Интервальная оценка с учетом рисков в часах:

- Разработка тест-кейсов и сценариев тестирования: 50-70 часов
- Написание автотестов: 100-150 часов
- Риски и неожиданные препятствия: 10-20 часов

**Итого:** 160-240 часов.