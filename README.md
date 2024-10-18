# Ansible роль для развертывания веб-приложения в Docker на Ubuntu

Данная Ansible роль предназначена для автоматизации развертывания веб-приложения в Docker на Ubuntu. Роль выполняет следующие задачи:

- Устанавливает Docker и Docker Compose на сервер.
- Настраивает и генерирует конфигурационный файл для Nginx.
- Создает и организует необходимые директории для сервисов web и PHP.
- Развертывает веб-приложение с помощью Docker Compose, включая сервисы Nginx, PHP и MySQL.

Файл 'docker-compose.yml' расположен по пути webapp/files/docker-compose.yml
Файл 'Dockerfile' расположен по пути webapp/files/php/Dockerfile
