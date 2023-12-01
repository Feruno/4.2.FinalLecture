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

##### Данные для заполнения
Имя - ```Василий```
<br>
Номер телефона - ```7 999-111-11-11```
  
  <br>

  1. Валидные данные для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон", (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - успешное отправление формы.
    
  1. Невалидный телефон для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99) тестовые данные - ```7 999-999-99-9```
     1. Нажать кнопку "Получить консультацию"
           <br>
    *Ожидаемый результат* - ошибка отправление формы.
        
  1. Невалидное имя для запииси на консультацию
     1. Заполнить поле "Имя" (Ввести имя содержащие спец символы "@$^&") тестовые данные - ```@Василий@```
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - ошибка отправление формы.
        

  ### Тесты с навигацией через блок "Направления обучения"

  #### Предусловие для тестов
  1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
  1. Нажать "Программирование" в блоке "Направления обучения".
  1. Выбрать и нажать "Программирование"
  1. Проскролить до "Тестировщика ПО"
  1. Выбрать "Тестировщика ПО"
  1. Проскролить страницу до конца

##### Данные для заполнения
Имя - ```Василий```
<br>
Номер телефона - ```7 999-111-11-11```
  
  <br>
  
  1. Валидные данные для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - успешное отправление формы.
        
  1. Невалидный телефон для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99) тестовые данные - ```7 999-999-99-9```
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - ошибка отправление формы.
      
  1. Невалидное имя для запииси на консультацию
     1. Заполнить поля "Имя" (Ввести имя содержащие спец символы "@$^&") тестовые данные - ```@Василий@```
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - ошибка отправление формы.

  ### Тесты через поисковую строку.
  
  #### Предусловие для тестов
  1. Перейти на страницу [нетологоии](https://netology.ru/#/) для записи на консультацию
  1. Нажать "Каталог курсов"
  1. В поисковой строке набрать "тестировщик по"
  1. Нажать Enter 
  1. Проскролить до "Тестировщика ПО"
  1. Выбрать "Тестировщика ПО"
  1. Проскролить страницу до конца

##### Данные для заполнения
Имя - ```Василий```
<br>
Номер телефона - ```7 999-111-11-11```
  
  <br>
  
  1. Валидные данные для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - успешное отправление формы.
        
  1. Невалидный телефон для записи на консультацию
     1. Заполнить поле "Имя"
     1. Заполнить поле "Телефон" (Телефон в формате +7 999) тестовые данные - ```7 999-999-99-9```
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - ошибка отправление формы.
      
  1. Невалидное имя для запииси на консультацию
     1. Заполнить поле "Имя" (Ввести имя содержащие спец символы "@$^&") тестовые данные - ```@Василий@```
     1. Заполнить поле "Телефон" (Телефон в формате +7 999-999-99-99)
     1. Нажать кнопку "Получить консультацию"
        <br>
    *Ожидаемый результат* - ошибка отправление формы.

  
# Перечень используемых инструментов

  1. Язык программирование Java, 11 версии.
  1. Idea - IntelliJ IDEA так как она быстрее таких Idea как Eclipse IDE, NetBeans. Больше встроенных инструментов.
  1. Selenide - позволяет писать более компактный код на Java в сравнении с Selenium, предоставляет API для использования Selenium WebDriver в UI-тестах
  1. Система сборки Gradle - настройка зависимостей в Gradle удобнее чем в Maven, Gradle использует domain-specific language (DSL) что является более гибким чем XML.
  1. Библиотека lombok - для генерации повторяющегося и/или шаблонного кода тестов, это ускорит написание тестов.
  1. Библиотека faker - для генерации тестовых данных.
  1. Git - для контроля изменений в тестах.
  1. GitHub - для облачного хранения тестов, GitHub ориентирован на общедоступный код. Как плюс в нём есть редактор кода, возможность обсуждение кода, многофакторная авторизация.

# Перечень необходимых разрешений, данных и доступов

  1. Разрешение на тестирование сервиса.
  1. Уточнить какие данные разрешены, например разрешено ли имя на другом языке.
  1. Доступ к API сервиса
  1. Доступ к базе данных, для проверки изменений в ней.
  1. Разрешение на отправку SQL запросов, для получения данных о записавшихся пользователях.

# Возможные риски при автоматизации

  1. Дополнительное время на реализацию проекта.
  1. Риск в необходимости дополнительных инструментов и их внедрении.
  1. Риск в необходимости дополнительной связи с разработчиками. 
  1. Изменения сервиса записи на консультацию. В связи с чем нужно будет переделывать тесты. 

# Перечень необходимых специалистов для автоматизации

  1. Один тестировщик.
  1. Разработчик или возможность с ним связаться. 

# Интервальная оценка с учётом рисков
  
  1. В случае если сервис не будет меняться от 1 дня до 3 дней.
  1. В случае если у сервиса будут изменения ~ от недели, зависит от изменений.
