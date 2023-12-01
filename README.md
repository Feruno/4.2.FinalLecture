---
название: Тест план для записи на консультацию
дата: 22.11.2023
Тест план составил: Александр Бондаренко
---

# Перечень автоматизируемых сценариев.

### Тесты через навигацию

#### Предусловие для тестов
  1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
  1. Нажать "Каталог курсов"
  1. Выбрать и нажать "Программирование"
  1. Проскролить до "Тестировщика ПО"
  1. Выбрать "Тестировщика ПО"
  1. Проскролить страницу до конца 
  
  <br>

  1. Валидные данные для записи на консультацию
     1. Заполнить поля "Имя"
     1. Заполнить поля "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат успешное отправление формы.
    
  1. Невалидный телефон для записи на консультацию
     1. Заполнить поля "Имя"
     1. Заполнить поля "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы.
        
  1. Невалидное имя для запииси на консультацию
     1. Заполнить поля "Имя" (Ввести имя содержащие спец символы "@$^&" т тд.)  и "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы.

  ### Тесты с навигацией через блок "Направления обучения"

  #### Предусловие для тестов
  1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
  1. Нажать "Программирование" в блоке "Направления обучения".
  1. Выбрать и нажать "Программирование"
  1. Проскролить до "Тестировщика ПО"
  1. Выбрать "Тестировщика ПО"
  1. Проскролить страницу до конца
  
  <br>
  
  1. Валидные данные для записи на консультацию
     1. Заполнить поля "Имя" и "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат успешное отправление формы.
        
  1. Невалидный телефон для записи на консультацию
     1. Заполнить поля "Имя" и "Телефон" (Телефон в формате +7 999)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы
      
  1. Невалидное имя для запииси на консультацию
     1. Заполнить поля "Имя" (Ввести имя содержащие спец символы "@$^&" т тд.)  и "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы.

  ### Тесты через поисковую строку.
  
  1. Валидные данные для записи на консультацию
     1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
     1. Нажать "Каталог курсов"
     1. В поисковой строке набрать "тестировщик по"
     1. Нажать Enter 
     1. Проскролить до "Тестировщика ПО"
     1. Выбрать "Тестировщика ПО"
     1. Проскролить страницу до конца
     1. Заполнить поля "Имя" и "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат успешное отправление формы.
        
  1. Невалидный телефон для записи на консультацию
     1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
     1. Нажать "Каталог курсов"
     1. В поисковой строке набрать "тестировщик по"
     1. Нажать Enter 
     1. Проскролить до "Тестировщика ПО"
     1. Выбрать "Тестировщика ПО"
     1. Проскролить страницу до конца
     1. Заполнить поля "Имя" и "Телефон" (Телефон в формате +7 999)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы
      
  1. Невалидное имя для запииси на консультацию
     1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
     1. Нажать "Каталог курсов"
     1. В поисковой строке набрать "тестировщик по"
     1. Нажать Enter  
     1. Проскролить до "Тестировщика ПО"
     1. Выбрать "Тестировщика ПО"
     1. Проскролить страницу до конца
     1. Заполнить поля "Имя" (Ввести имя содержащие спец символы "@$^&" т тд.)  и "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
     1. Ожидаемый результат ошибка отправление формы.

  
# Перечень используемых инструментов

  1. Язык программирование Java, 11 версии.
  1. Idea - IntelliJ IDEA.
  1. Selenide
  1. Система сборки Gradle.
  1. Библиотека lombok - для упрощение написания кода тестов.
  1. Библиотека faker - для генерации тестовых данных.
  1. Git - для контроля изменений в тестах.
  1. GitHub - для облачного хранения тестов.

# Перечень необходимых разрешений, данных и доступов

  1. Разрешение на тестирование сервиса.
  1. Уточнить какие данные разрешены, например разрешено ли имя на другом языке.
  1. Доступ к API сервиса 

# Возможные риски при автоматизации

  1. Риск выйти за рамки срока.
  1. Риск в необходимости дополнительных инструментов и их внедрении.
  1. Риск в необходимости дополнительной связи с разработчиками. 
  1. Изменения сервиса записи на консультацию. В связи с чем нужно будет переделывать тесты. 

# Перечень необходимых специалистов для автоматизации

  1. Один тестировщик.
  1. Разработчик или возможность с ним связаться. 

# Интервальная оценка с учётом рисков
  
  1. В случае если сервис не будет меняться от 1 дня до 3 дней.
  1. В случае если у сервиса будут изменения ~ от недели, зависит от изменений.
