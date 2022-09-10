# Отчёт по MongoDB

1. В контесте **CAP** MongoDB относится к CP-системам.
2. *По умолчанию MongoDB работает в режиме приоритета консистентности:*

> MongoDB is strongly consistent by default - if you do a write and then do a read, 
> assuming the write was successful you will always be able to read the result of 
> the write you just read. This is because MongoDB is a single-master system and all 
> reads go to the primary by default. If you optionally enable reading from the 
> secondaries then MongoDB becomes eventually consistent where it's possible to read 
> out-of-date results.

