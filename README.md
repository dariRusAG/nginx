# NGINX
## Получить практические навыки конфигурирования NGINX.

*Задача* Реализовать два приложения, располагающиеся на файловой системе в `/var/www/html/app1/index.html` и `/var/www/html/app2/index.html`, доступные по адресам http://ip/ и http://ip:7777/docs/ соответственно с помощью конфигурирования NGINX.

### Порядок выполнения
1. Анализ задачи.
2. Исследование источников.
https://nginx.org/ru/docs/
3. Реализация двух приложений с использованием html.
4. Конфигурирование NGINX.

**Форма отчета:** репозиторий на GitHub с файлами приложений и конфигурационным файлом NGINX и скриншотами подтверждающими работу приложений.

### Доступ по ссылке:
1. [app1](http://143.198.70.213/)
2. [app2](http://143.198.70.213:7777/docs/)

### Скриншот app1
![image](https://user-images.githubusercontent.com/91362737/175779440-5ed8b3b7-23a9-40c3-8cc0-a154dc70ca1d.png)

### Скриншот app2
![image](https://user-images.githubusercontent.com/91362737/175779462-d561a955-0d9c-41c9-b7d4-951c21008455.png)

#### Команды перезапуска nginx
`systemctl restart nginx`
`sudo nginx -t`
`sudo nginx -s reload`

#### Путь изменения config
1. `cd /etc/nginx/sites-enabled`
2. `sudo nano config`
3. `cd /etc/nginx/sites-avialable`
4. `sudo nano default`
