# beatGT-project
Проект BeatGT представляет из себя приложение, где пользователь может зарегистрироваться и авторизоваться, чтобы собрать сборку для ПК, а также просматривать сборки других пользователей.
Данное приложение создано в рамках учебного проекта в группе из 3 человек.
# Стек технологий
Django, PostgreSQL, React, SCSS, AXIOS
# Как начать использовать?
--Подготовка БД
 * Скачать PostgreSQL
 * Скачать DBeaver для удобства
 * Импортировать схему, которая лежит в beatGT_database
   
--Подготовка Бэкенда
 * Скачать VScode для удобства
 * Установить фреймворк django
 * Перейти в папку cd beatgt_backend
 * В settings.py прописать своего пользователя и бд, которой хотите подсоединиться
 * Запустить сервер командой py manage.py runserver
 * Чтобы воспользоваться панелью администратора необходимо создать суперюзера командой py manage.py createsuperuser
   
--Подготовка фронтенда
 * Скачать VScode для удобства
 * Перейти в папку beatGT_frontend
 * В терминале прописать npm i -f
 * Запустить npm start
