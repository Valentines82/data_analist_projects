# Описание проекта
Коронавирус застал мир врасплох, изменив привычный порядок вещей. В свободное время жители городов больше не выходят на улицу, не посещают кафе и торговые центры. Зато стало больше времени для книг. Это заметили стартаперы — и бросились создавать приложения для тех, кто любит читать. Наша компания решила быть на волне и купила крупный сервис для чтения книг по подписке. Наша первая задача как аналитика — проанализировать базу данных.
### Инструменты
Python, Pandas, SQLAlchemy, SQL
# Описание данных
Таблица books - данные о книгах:
 - book_id — идентификатор книги;
 - author_id — идентификатор автора;
 - title — название книги;
 - num_pages — количество страниц;
 - publication_date — дата публикации книги;
 - publisher_id — идентификатор издателя.

Таблица authors - данные об авторах:
 - author_id — идентификатор автора;
 - author — имя автора.

Таблица publishers - данные об издательствах:
 - publisher_id — идентификатор издательства;
 - publisher — название издательства;

Таблица ratings - данные о пользовательских оценках книг:
 - rating_id — идентификатор оценки;
 - book_id — идентификатор книги;
 - username — имя пользователя, оставившего оценку;
 - rating — оценка книги.

Таблица reviews - данные о пользовательских обзорах:
 - review_id — идентификатор обзора;
 - book_id — идентификатор книги;
 - username — имя автора обзора;
 - text — текст обзора.
