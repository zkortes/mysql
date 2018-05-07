# mysql

1. Создание нового пользователя Mysql:

  CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
    где:
      - user - имя пользователя бд
      - password - пароль пользователя бд
      
2. Добавление полных привелегий пользователю user
  
  GRANT ALL PRIVILEGES ON * . * TO 'user'@'localhost';
  
  Обращаю Ваше внмиание, что эта команда позволяет пользователю 'user' читать, редактировать, выполнять любые действия над всеми базами данных и таблицами.
  
