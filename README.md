# 1. Тема и целевая аудитория

Тема - Tinder. Один из самых популярных сервисов знакомств. 

Аудитория - 

75 млн

Из них 

30 млн - США и Северная Америка

30 млн - Европа

12 млн - Остальной мир

3 млн - Россия (тк большую часть на себя берет Badoo)

# 2. Расчет нагрузки

## Продуктовые метрики

### Месячная аудитория

Tinder не раскрывает дневную аудиторию, но мы можем посмотреть примерные значения

![https://user-images.githubusercontent.com/33177954/135096543-9e4b5b9e-bb0c-41d8-8525-d57a68e96af1.png](https://user-images.githubusercontent.com/33177954/135096543-9e4b5b9e-bb0c-41d8-8525-d57a68e96af1.png)

### Дневная аудитория

Из месячной следует, что это около 1.5 млн пользователей в день.

### Средний размер хранилища пользователя
![image](https://user-images.githubusercontent.com/33177954/135312481-f13aa43d-a41d-4569-a267-e08f45758037.png)

### Среднее количество действий пользователей по типам в день
![image](https://user-images.githubusercontent.com/33177954/135312511-94ddbd7e-7ce0-4f3d-93e2-2afd8e301149.png)


## Технические метрики

### Размер хранения в разбивке по типам данных (в Тб)
![image](https://user-images.githubusercontent.com/33177954/135312566-01b42a8b-1937-4919-a389-ef61341993c4.png)

### Сетевой трафик

Из расчета, что в день происходит 8'500'000'000 запросов на фотографии, а размер одной фотографии - 500Кб, то общий дневной трафик - 4 150 400 Гбайт, т.е. 33 203 200 Гбит в день - 385 Гбит/c. Допустим, что 40 процентов трафика приходится на вечерние часы, с 18:00 до 22:00, из этого пиковая нагрузка - около 1000 ГБит/c. 

Свайп - около 2Кбайт, следовательно  на них уходит меньше 1 Гбит/c в среднем и до 1 Гбит/c на пике. 

Сообщение - 3 Кбайт, следовательно на них уходит меньше 1 Гбит/c в среднем и меньше 1 Гбит/с в пике
![image](https://user-images.githubusercontent.com/33177954/135312595-b6a71e1a-3950-4dfc-88aa-61e3dfbe32fe.png)

### RPS в разбивке по типам запросов
![image](https://user-images.githubusercontent.com/33177954/136426682-c4b3d7dd-2234-411e-89fa-dea551df62cd.png)

# Источники

1. [https://www.businessofapps.com/data/tinder-statistics/](https://www.businessofapps.com/data/tinder-statistics/)
2. [https://www.semrush.com/analytics/traffic/overview/tinder.com?searchType=domain](https://www.semrush.com/analytics/traffic/overview/tinder.com?searchType=domain)
