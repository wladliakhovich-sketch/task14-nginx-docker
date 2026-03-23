# Task 14 - NGINX Docker Project

## 📌 Описание проекта
Данный проект демонстрирует работу веб-сервера NGINX внутри Docker-контейнера.

Контейнер настроен для:
- отдачи HTML страницы
- раздачи изображений
- раздачи музыкальных файлов
- выполнения редиректа
- проксирования запросов на другой контейнер (backend)

Проект реализован с использованием:
- Dockerfile
- Docker Compose
- конфигурации NGINX
- Docker Hub

---

## 📁 Структура проекта

```text
task14-nginx-docker/
├── Dockerfile
├── docker-compose.yml
├── README.md
├── nginx/
│   └── default.conf
├── html/
│   └── index.html
├── images/
│   ├── grogu.jpg
│   ├── hyperjump.jpg
│   └── trooper.jpg
├── music/
│   └── Star_Wars_Cantina_Theme_Song.mp3
└── app/
    ├── Dockerfile
    └── index.html




# 🚀 NGINX Docker Project (Task 14)

---

## 🇬🇧 English version

### 📌 Project Description
This project demonstrates running NGINX inside a Docker container.

The container is configured to:
- serve a custom HTML page
- serve images
- serve music files
- perform redirects
- proxy requests to another container (backend)

Technologies used:
- Docker
- Docker Compose
- NGINX
- Docker Hub

---

### 📁 Project Structure

```text
task14-nginx-docker/
├── Dockerfile
├── docker-compose.yml
├── README.md
├── nginx/
│   └── default.conf
├── html/
│   └── index.html
├── images/
├── music/
└── app/
    ├── Dockerfile
    └── index.html
