# cult-navi
Это веб-приложение - путеводитель по музеям с использованием искусственного интеллекта  

## Цель проекта: 
Разработка Web-приложения "Умный городской гид" для улучшения опыта посещения музеев и исследования городов.
## Задачи: 
Создание интерактивного и интуитивно понятного интерфейса для легкой навигации и предоставления информации о достопримечательностях.
## Анализ проблемы
## Проблема: 
Посетители часто испытывают трудности с навигацией и не получают достаточно информации, что снижает качество их опыта.
##  Влияние: 
Недостаток информации и сложность ориентирования уменьшают интерес и удовлетворенность от посещения.
#   Описание решения
##  IT-решение: 
Интеграция чат-бота на базе Mistral AI для предоставления персонализированной информации и помощи в навигации. Пользователь открывает приложение, видит выпадающее меню, из которого может выбрать музей, в котором он сейчас. Этот выбор формирует контекст будущего запроса к нейросети. Далее пользователь отправляет свой запрос. Нейросеть обрабатывает с учетом контекста его и возвращает ответ. 

#### Кроме того, приложение отдельным скриптом run_schedule.py обновляет контест по расписанию, чтобы поддерживать его в актуальном состоянии.

##  План: 
Разработка прототипа, тестирование, запуск и поддержка приложения.
#    Практическая ценность и применимость
##  Влияние: 
Улучшение информированности посетителей, обогащение их опыта и упрощение навигации.
##  Решаемые проблемы: 
Устранение информационного дефицита и проблем с ориентацией.
#    Команда и план действий
##  Команда: 
Дмитрий (Frontend, взаимодействие клиент-сервер), Павел (парсинг данных), Алексей (парсинг данных), Александр (подключение и установка нейросети). Сроки - в рамках 3-х спринтов.
##  Распределение задач: 
Разработка функционала, дизайн интерфейса, тестирование.
#    Заключение
##  Достижения: 
Создание инновационного решения для повышения качества туристического опыта.
##  Практическая ценность: 
Предоставление доступной и удобной информационной поддержки посетителям.
