# #  Домашнее задание к лекции «Docker»

 # Задание 1

Создание образа: docker build -t file_html .


Запуск контейнера: docker run -v "${PWD}:/usr/share/nginx/html" -p 8090:80 -d html
