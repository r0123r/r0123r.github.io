# r0123r.github.io
История проектов

HTTP-server
  
    github.com/r0123r/go-cgiserver - подключение php-cgi
    
    github.com/r0123r/rpc-json - настройка ExtDirect на базе rpc-json

    github.com/r0123r/rewrite - замена модуля apache rewrite
    
    github.com/r0123r/fastcgi-serve - подключение fastcgi php (windows)  и fpmphp (linux)
    
    github.com/r0123r/beego-session-hredis - модуль сохранения сессии в redis в формате json для совместного использования в php

FTP-server

    - github.com/r0123r/ftp-server
    - github.com/r0123r/ftp-ledis-driver
    - github.com/r0123r/ftp-file-driver
    - медленный сервер (файлы закачиваются в одном соединении) и модули к нему
    
    - github.com/r0123r/ftpserver
    - быстрый сервер (соединения создаются в параллельных потоках) + поддержка символических ссылок
    
Redis-server

    github.com/r0123r/go-redis-server - сервер с "нуля" мало функций, скорость не оптимальная, stor - только память
    
    github.com/r0123r/vredis - сервер на базе ledis, stor - память и goleveldb, http-интерфейс
    - добавлен ftp-интерфейс для работы с файлами 
    - pub/sub сообщения
    - set-event(publish) при обновлении ключа типа KV
