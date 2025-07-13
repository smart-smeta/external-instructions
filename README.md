# QRDocManager - Система управления документацией через QR-коды

![QRDocManager Demo](demo-screenshot.png)

Автономное решение для создания, управления и печати QR-кодов для документации с функциями безопасности и аналитики.

## 🔑 Основные возможности

- **📁 Централизованное хранилище** документов с версионированием
- **🛠️ Генерация кастомизированных QR-кодов** с логотипами
- **🖨️ Умная печать** на обычных принтерах и принтерах этикеток
- **🔐 Гибкие политики безопасности** с ограничениями доступа
- **📊 Аналитика сканирований** в реальном времени
- **👥 Мультиролевая система** (Администратор, Редактор, Гость)

## ⚙️ Технологии

### Бэкенд
- PHP 8.2 + Laravel 10
- SQLite/MySQL
- Endroid QR-Code + DomPDF

### Фронтенд
- Vue.js 3 + Pinia
- Tailwind CSS + Chart.js
- Print.js

### Упаковка
- **Windows**: EXE-установщик (Inno Setup)
- **Linux**: DEB-пакет + bash-скрипт
- **Docker**: Готовый образ

## 🚀 Установка

### Windows
1. Скачайте [QRDocManager_Setup.exe](https://example.com/QRDocManager.exe)
2. Запустите установщик
3. Откройте `http://localhost:8080`

### Linux (Debian/Ubuntu)
```bash
# Скачать и запустить инсталлятор
wget https://install.qrdocmanager.com/linux-install.sh
chmod +x linux-install.sh
sudo ./linux-install.sh
