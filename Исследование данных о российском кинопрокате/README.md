# Описание проекта
Заказчик этого исследования — Министерство культуры Российской Федерации. Нужно изучить рынок российского кинопроката и выявить текущие тренды. На насколько фильмы, которые снимаются с государственной поддержкой интересны зрителю.
### Инструменты
Python, Pandas
# Описание данных 
Таблица mkrf_movies содержит информацию из реестра прокатных удостоверений. У одного фильма может быть несколько прокатных удостоверений.

 - title — название фильма;
 - puNumber — номер прокатного удостоверения;
 - show_start_date — дата премьеры фильма;
 - type — тип фильма;
 - film_studio — студия-производитель;
 - production_country — страна-производитель;
 - director — режиссёр;
 - producer — продюсер;
 - age_restriction — возрастная категория;
 - refundable_support — объём возвратных средств государственной поддержки;
 - nonrefundable_support — объём невозвратных средств государственной поддержки;
 - financing_source — источник государственного финансирования;
 - budget — общий бюджет фильма;
 - ratings — рейтинг фильма на КиноПоиске;
 - genres — жанр фильма.

Столбец budget уже включает в себя полный объём государственной поддержки. Данные в этом столбце указаны только для тех фильмов, которые получили государственную поддержку.
