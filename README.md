# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Громов Андрей`

---

### Задание 1

`Приведите примеры проблем, которые может решить кеширование.`

1. `Значительное количество обращений к базе данных: кеширование может уменьшить количество запросов к базе данных, сохраняя результаты предыдущих запросов в кэше. Это помогает минимизировать задержки и снизить нагрузку на сервер.`
2. `Медленные операции сети: если приложение часто обращается к удаленным API или сервисам, кеширование может уменьшить задержки, храня копии ответов в кэше. Это особенно полезно в случае медленного или ненадежного соединения.`
3. `Вычисления с высокой сложностью: если вычисления занимают много времени и ресурсов, и результаты этих вычислений не меняются часто, то можно сохранить результаты в кэше и использовать их вместо повторного выполнения вычислений. Это может быть полезно для ускорения работы сложных алгоритмов.`
4. `Доступ к ресурсам с высокими накладными расходами: если операции чтения/записи больших объемов данных занимают значительное время, то кеширование может увеличить производительность, храня копии данных в памяти или на более быстрых носителях, таких как SSD.`
5. `Динамически создаваемые данные: если данные, получаемые приложением, создаются динамически и их обновление требует значительных ресурсов, то кеширование может уменьшить нагрузку на систему, сохраняя копии данных в кэше и обновляя их по необходимости.`
6. `Частые запросы на подобные данные: если приложение часто запрашивает одну и ту же информацию, то кеширование может значительно сократить время доступа к данным, ускоряя работу приложения и улучшая пользовательский опыт.`

---

### Задание 2

`Установите и запустите memcached.`

![Скриншот 1](https://github.com/GromDrn/memcached-redis/blob/main/Screenshots/2mstat.jpg)


---

### Задание 3

`Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.`

![Скриншот 1](https://github.com/GromDrn/memcached-redis/blob/main/Screenshots/3mkey.jpg)

### Задание 4

`Запишите в Redis несколько ключей с любыми именами и значениями.`


![Скриншот 1](https://github.com/GromDrn/memcached-redis/blob/main/Screenshots/4redis.jpg)

---
## Дополнительные задания (со звездочкой*)

### Задание 5

`Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.`


![Скриншот 1](https://github.com/GromDrn/memcached-redis/blob/main/Screenshots/5incr.jpg)
