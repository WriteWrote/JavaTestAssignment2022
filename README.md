# Java + Spring + PostgreSQL + Gradle

### 1. Создать RESTful API сервисы для работы с документами, среди возможностей:
 * создавать документы (регистрационный номер документа присваивается в момент записи, генерируется по любому алгоритму, обеспечивающему уникальный номер среди документов этого же типа);
 * удалять документы по первичному ключу или регистрационному номеру;
 * изменять документы;
 * создавать связь между документами по первичным ключам или регистрационному номеру.

### 2. Документ -- набор обязательных значений хранящихся в базе данных, его атрибутный состав:
 * первичный ключ;
 * тип документа (входящий, исходящий, внутренний);
 * заголовок документа строкового типа;
 * содержание документа строкового типа;
 * регистрационный номер тип на усмотрение разработчика;
 * связь с любым количеством других документов, возможные связи: входящий-исходящий, исходящий-входящий, внутренний-внутренний.

### 3. Данные должны сохраняться в Postgresql/SQLite.

### 4. Каждое вызов сервиса должен логироваться.


5. Не требуется создавать никакого графического интерфейса.
6. Можно использовать любые python библиотеки.
7. Код оформить в репозиторий на Github/Bitbucket.

### Схема бд:
![pythonwebtestassignmentdb drawio](https://user-images.githubusercontent.com/45429218/204267014-7126e012-4643-417c-af77-7f7254c3a68d.png)
