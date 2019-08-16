# r0123r.github.io
История проектов

  - HTTP-server
    - [go-cgiserver](https://github.com/r0123r/go-cgiserver) - подключение php-cgi
    - [rpc-json](https://github.com/r0123r/rpc-json) - настройка ExtDirect на базе rpc-json
    - [rewrite](https://github.com/r0123r/rewrite) - замена модуля apache rewrite
    - [fastcgi-serve](https://github.com/r0123r/fastcgi-serve) - подключение fastcgi php (windows)  и fpmphp (linux)
    - [beego-session-hredis](https://github.com/r0123r/beego-session-hredis) - модуль сохранения сессии в redis в формате json для совместного использования в php

  - FTP-server
    - [ftp-server](https://github.com/r0123r/ftp-server) - медленный сервер (файлы закачиваются в одном соединении) и модули к нему
      - [ftp-ledis-driver](https://github.com/r0123r/ftp-ledis-driver)
      - [ftp-file-driver](https://github.com/r0123r/ftp-file-driver)
      
    - [ftpserver](https://github.com/r0123r/ftpserver) - быстрый сервер (соединения создаются в параллельных потоках, 1 соединение на 1 файл) 
      - поддержка символических ссылок
    
  - Redis-server
    - [go-redis-server](https://github.com/r0123r/go-redis-server) - сервер с "нуля" мало функций, скорость не оптимальная, stor - только память
    
    - [vredis](https://github.com/r0123r/vredis) - сервер на базе ledis, stor - память и goleveldb, http-интерфейс
      - добавлен ftp-интерфейс для работы с файлами ([ftpserver](https://github.com/r0123r/ftpserver))
      - pub/sub сообщения
      - set-event(publish) при обновлении ключа типа KV
  - [Полезные библиотеки](libs.md)
