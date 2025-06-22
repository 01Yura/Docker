Данный докер компоуз файл запускает Selenoid и SelenoidUI,
обрати внимание что в файле прописан volume, соответственно путь до конфиг файла для Selenoid должен совпадать

volumes:
      - "G:/Yura/Tests/config:/etc/selenoid" # путь до папки, где лежит browsers.json

После запуска команды docker-compose up -d поднимутся 2 контейнера

Проверить усешность запуска можно введя в браузере:
http://localhost:4444/
http://localhost:8080/