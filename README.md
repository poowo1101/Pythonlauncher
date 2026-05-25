# 🎮 PythonLauncher

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![Platform](https://img.shields.io/badge/platform-Windows-orange)
![License](https://img.shields.io/badge/license-MIT-purple)

**Сучасний Minecraft лаунчер з автоматичним оновленням, встановленням модів та Forge**

[Функції](#-функції) • [Встановлення](#-встановлення) • [Використання](#-використання)

</div>

---

## ✨ Функції

🚀 **Основні можливості:**
- **Автоматичне завантаження** будь-якої версії Minecraft (включаючи снапшоти)
- **Auto-Set модів** — пошук і встановлення модів через Modrinth API
- **Встановлення Forge** прямо з лаунчера
- **Автооновлення** через GitHub Releases
- Зручний та сучасний інтерфейс на CustomTkinter
- Підтримка всіх версій Minecraft (від старих до найновіших)

---

## 📋 Системні вимоги

| Компонент | Вимоги |
|-----------|--------|
| **ОС** | Windows 10/11 |
| **Python** | 3.10 або новіше |
| **Java** | Java 17+ (рекомендовано) |
| **RAM** | Мінімум 2 GB вільно |
| **Інтернет** | Для завантаження версій та модів |

---

## 🔧 Встановлення

```bash
# Клонуємо репозиторій
git clone https://github.com/poowo1101/Pythonlauncher.git
cd Pythonlauncher

# Встановлюємо залежності
pip install customtkinter requests pillow

# Запускаємо
python launcher.py
