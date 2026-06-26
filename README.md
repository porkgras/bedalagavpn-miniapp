cat > README.md << 'EOF'
# BedalagaVPN - Mini App

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python](https://img.shields.io/badge/Python-3.9+-yellow.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green.svg)](https://fastapi.tiangolo.com/)

**Telegram Mini App для управления VPN-бизнесом на базе YadrenoVPN**

## 🌐 Языки / Languages
- [Русский](README.ru.md) (основной)
- [English](README.en.md)
- [Türkçe](README.tr.md)

## ✨ Возможности

### 👑 Admin Paneli (v1.0)
- 📊 Dashboard - статистика и графики
- 👥 Управление пользователями
- 📦 Управление пакетами
- 🖥️ Управление серверами (3x-ui)
- 💰 Финансы и отчеты
- 📨 Уведомления и рассылки
- ⚙️ Настройки системы

## 🚀 Быстрый старт

```bash
# Клонирование
git clone https://github.com/yourusername/bedalagavpn-miniapp.git
cd bedalagavpn-miniapp

# Установка
python -m venv venv
source venv/bin/activate
pip install -r backend/requirements.txt

# Настройка
cp .env.example .env
# Отредактируйте .env

# Запуск
cd backend
python -m src.main
