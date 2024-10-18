# Ansible Роль для Развертывания Веб-Приложения в Docker

Данная Ansible роль предназначена для автоматизации развертывания веб-приложения в Docker на Ubuntu. 

## Задачи роли

Роль выполняет следующие ключевые задачи:

- Устанавливает **Docker** и **Docker Compose** на сервер.
- Настраивает и генерирует конфигурационный файл для **Nginx**.
- Создает и организует необходимые директории для сервисов **web** и **PHP**.
- Развертывает веб-приложение с помощью **Docker Compose**, включая сервисы **Nginx**, **PHP** и **MySQL**.

## Структура файлов

- Файл `docker-compose.yml` расположен по пути: `webapp/files/docker-compose.yml`
- Файл `Dockerfile` расположен по пути: `webapp/files/php/Dockerfile`

<br>
<br>

### Вывод выполнения роли в командной строке

<img src="https://i.imgur.com/ERmZPuv.jpeg" alt="Вывод выполнения роли в командной строке" width="350"/>

### Docker

<img src="https://i.imgur.com/hLyqDCp.png" alt="Контейнеры в Docker"/>
