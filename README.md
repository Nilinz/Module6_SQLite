# SQLite University DB

Цей проект створює базу даних для університету з використанням SQLite і наповнює її випадковими даними. База даних містить інформацію про студентів, групи, викладачів, предмети та оцінки студентів з цих предметів. Для наповнення бази даних випадковими даними було використано пакет Faker. Було задано 30-50 студентів, 3 групи, 5-8 предметів, 3-5 викладачів та до 20 оцінок у кожного студента з усіх предметів.


### Отримані вибірки із БД

- 5 студентів із найбільшим середнім балом з усіх предметів.
- студент із найвищим середнім балом з певного предмета.
- середній бал у групах з певного предмета.
- середній бал на потоці (по всій таблиці оцінок).
- які курси читає певний викладач.
- список студентів у певній групі.
- оцінки студентів у окремій групі з певного предмета.
- середній бал, який ставить певний викладач зі своїх предметів.
- список курсів, які відвідує студент.
- список курсів, які певному студенту читає певний викладач.

### Використання

- Запустіть ``university_db.py`` . Відповідно створиться база даних ``university.db`` .

- Використовуйте SQL-запити з файлів ``query_(number).sql`` для отримання потрібних вибірок з бази даних. Номер відповідає номеру у списку вибірок.
