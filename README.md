# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Маркин Алексей`

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*

---

### Решение 1

Медленная загрузка медиа-файлов: При кешировании медиа-файлов, таких как изображения, видео или аудио, пользователи могут получать быстрый доступ к этим файлам, без необходимости загружать их с сервера каждый раз.

Долгие запросы к базе данных: Кеширование запросов к базе данных может значительно уменьшить нагрузку на сервер и сократить время, необходимое для обработки запросов от пользователей.

Медленная загрузка веб-страницы: Кеширование веб-страниц может ускорить загрузку сайта для пользователей, так как они будут получать содержимое из кеша, а не каждый раз запрашивать его с сервера.

---


### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

---

### Решение 2

Я использовал докер

![Задание 2-1](https://github.com/Markin-AI/11-2/blob/main/img/2-1.png)

---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

---

### Решение 3

![Задание 3-1](https://github.com/Markin-AI/11-2/blob/main/img/3-1.png)

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

---

### Решение 4

![Задание 4-1](https://github.com/Markin-AI/11-2/blob/main/img/4-1.png)

---

### Задание 5*. Работа с числами 

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.  

*Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.*

---

### Решение 5*

![Задание 5-1](https://github.com/Markin-AI/11-2/blob/main/img/5-1.png)

---

