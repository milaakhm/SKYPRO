# Портфолио: Инженер по тестированию 
# Обо мне
Привет! Меня зовут Миля, я - начинающий инженер-тестировщик. В далеком прошлом - учитель английского и немецкого языков. Так что искать несоответствия - профессиональная привычка.
В этом репозитории вы можете найти некоторые из моих проектов, выполненных за время моего обучения и практики.
# Навыки и технологии
Jira, qase.io, Sitechko, SQL, Postman, Swagger, Trello,
Soap UI, Chrome DevTools.
# Проекты
1. Тестирование веб-приложения для учителей Skyeng. Необходимо было проверить программный продукт данной компании на предмет возможности создавать в расписании личные события в настоящем, будущем и за прошлый месяц, а также события разной продолжительности по времени.

 Что нужно было сделать:
   - сделать тест-план;
   - подготовить тестовую документацию;
   - провести тестирование;
   - написать отчет о результатах тестирования.
   
     Оценив Документацию к проекту, было решено провести для начала тестирование требований, а затем приступить к функциональному тестированию: smoke тестирование, создание редактирование/удаление Личных событий. Все необходимые тест-кейсы и тест-сьюты оформила в  **Qase.io**. В **Miro** составила декомпозицию для функционала "Личное событие" со следующими критериями: *минимум 3 уровня вложенности*, *все элементы присутствуют*, *карта читаема и понятна, отражает реальную структуру функционала*. Также по заданию необходимо было расписать функциональные чек-листы с позитивными и негативными проверками, соблюдая такие требования: *чек-лист покрывает все функциональные требования*, *чек-лист низкоуровневый*. Они были составлены в **Гугл таблице**. На Найденные баги составила баг-репорты в **Jira**.
   Следующим этапом нужно было провести **регрессионное тестирование** и написать верхнеуровневые чек-листы для функционала Урок. На данном этапе пришлось работать без тестовой документации и требований к данному Функционалу.
   По итогу нужно было написать вывод о том, готово ли данное приложение к работе, обосновать свои рассуждения. В отчете для наглядности были приложены таблицы и круговые диаграммы по приоритетности багов и по тестовому покрытию функционала.
  
 Ссылка на проект: https://mila02101973.atlassian.net/wiki/spaces/~63639879c97f5473af723ca1/pages/5242881

Логин  mila.7373@mail.ru 

Пароль mamit2022

 2. Протестировать кабинет учителя Skyeng через API.
 
  Что нужно было сделать:
   - дополнить тест-план;
   - создать коллекцию в Postman;
   - провести тест-ран;
   - на основе результатов тест-рана дополнить отчет о тестировании.

     Данная курсовая являлась продолжением моей 1 курсовой работы. Для 2 курсовой работы мне пригодились тест-кейсы и чек листы, составленные раннее. Изучив Документацию к проекту и предоставленные скриншоты, стало понятно, какие запросы нужно составлять в **Postman**. А именно: получение расписания, создание персонального события, редактирование персонального события, удаление персонального события. В Postman создала новое пространство и новую коллекцию, создала запросы, соответствующие тест-кейсам функционального тестирования. Запросы были составлены методом POST ведь он более безопасен, введены переменные для "token", "id", "startAt", "URL". После создания всех запросов запустила test-run коллекции. Всю коллекцию сохранила и прикрепила файл к курсовой работе. Дополнила курсовую выводами по API.
    
 Ссылка на проект: https://mila02101973.atlassian.net/wiki/spaces/~63639879c97f5473af723ca1/pages/5242881/1+2

  Логин  mila.7373@mail.ru
  
  Пароль mamit2022
  
  3. Мобильное тестирование разделов "Ситуации" и "Видеопрактика" приложения для изучения английского языка Skyeng.
     
     Что нужно было сделать:
     - тест-план;
     - анализ требований (вопросы к требованиям);
     - тестовая документация к ситуациям и видеопрактике (чек-листы или тест-кейсы);
     - анализ выбора устройства;
     - отчет о тестировании (со ссылками на баг-репорты, если они найдены).
       
     Ознакомившись с требованиями к данным разделам, оформила таблицу с тестированием требований. На основании требований составила функциональные чек-листы к разделу "Ситуация" и "Видеопрактика". Плюс к этому еще чек-листы для мобильного тестирования - тестирование совместимости, тестирование локализации и глобализации, тестирование удобства использования,
тестирование производительности. Провела анализ выбора устройства на основании представленного макета. Провела функциональное и мобильное тестирование, на найденные баги составила баг-репорты. Сделала подмену запроса с помощью инструмента Charles( приложен скрин). По итогу оформила отчет по тестированию, для наглядности добавила круговые диаграммы и таблицы. Написала выводы и рекомендации. Проверяемый продукт не был готов к релизу. 

Ссылка на проект: https://skyengpublic.notion.site/baf9be1f58194ee684c3cb58db73e1a2

  Логин  mila.7373@mail.ru
  
  Пароль mamit2022
 
4. Дипломная работа
   Что нужно было сделать:
   - сделать тест-план;
   - подготовить тестовую документацию;
   - провести тестирование;
   - написать отчет о результатах тестирования.

    Для начала  нужно было авторизоваться на главной странице Skyeng в кабинете учителя  браузере Chrom или Яндекс. Установить мобильное приложение Skyeng на телефон и авторизоваться в лисном кабинете ученика.  Как всегда познакомилась с требованиями к функционалу "Видеопрактика" и к разделу "Ситуация". Прописала чек-листы к функционалу обоих кабинетов и на интеграцию, мобильное тестирование и тестирование совместимости. Главная задача данной работы - соединить ученикаи учителя в одной веб-комнате и протестировать взаимодействие данных кабинетов.В Confluence составила тест-план, провела проверку по чек-листам. Итоги проверок и ссылки на баги отразила в отчете. Там же оформила выводы и рекомендации, для наглядности использовала диаграммы.

Ссылка на проект: https://mila02101973.atlassian.net/wiki/spaces/~63639879c97f5473af723ca1/pages/21921793

  Логин  mila.7373@mail.ru
  
  Пароль mamit2022
  
 # Контактная информация:
   Email: Mila.7373@mail.ru
   Tel: 89178689591
