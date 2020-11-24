Перед запуском контейнера с БД необходимо устаноить Docke по инструкции:
https://github.com/netology-code/aqa-homeworks/blob/aqa4/docker/installation.md

Запуск контейнера и проверка БД: 
1) В директории проекта запустить команду docker-compose up
2) Дождаться появления в логе записи "listening on IPv4 address "0.0.0.0", port 5432"
3) В новом терминале запустить команду java -jar db-api.jar
4) Запустить браузер и открыть ссылку http://localhost:9999/api/cards
5) Убедиться что на открывшейся странице браузера отображается json с карточками