# ⏱️ Time-to-Learn

<div align="center">

![Time-to-Learn](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-7F52FF?style=flat-square&logo=kotlin)
![Gemini API](https://img.shields.io/badge/AI-Google%20Gemini-4285F4?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

**Родительский контроль нового поколения**

Приложение для блокировки телефона ребёнка на заданное время с интуитивным интерфейсом и умными функциями.

[🌐 Посетить сайт](https://time-to-learn-pi.vercel.app) • [📱 Скачать](#установка) • [🐛 Сообщить об ошибке](#поддержка)

</div>

---

## 📋 Описание

**Time-to-Learn** — мобильное приложение для Android, которое помогает родителям контролировать время использования телефона детьми. 

### ✨ Основные возможности:

- ⏱️ **Таймер обратного отсчёта** — устанавливайте время в удобном формате
- 🎯 **Простой интерфейс** — интуитивный дизайн для всех возрастов
- 🔒 **Надёжная блокировка** — телефон остаётся заблокирован на всё время сеанса
- 🤖 **AI помощник** — интеграция Google Gemini для умных рекомендаций
- 📱 **Минималистичный дизайн** — лёгкое в использовании приложение
- 🌐 **Веб-версия** — управляйте с компьютера на Vercel

---

## 🎯 Как это работает

1. **Откройте приложение** и нажмите на иконку
2. **Установите время** обратным отсчётом (например, 2 часа)
3. **Нажмите "Запустить"** — телефон заблокируется на это время
4. **Используйте меню** для управления активным сеансом

---

## 📲 Быстрая установка

### Требования:
- 🤖 Android 5.0+ (API Level 21+)
- 🔧 Android Studio (последняя версия)
- ☕ Java Development Kit (JDK) 11+
- 🔑 Gemini API ключ от Google

### Шаг за шагом:

#### 1️⃣ Клонируйте репозиторий
```bash
git clone https://github.com/AlexTrader2278/Time-to-learn.git
cd Time-to-learn
```

#### 2️⃣ Откройте в Android Studio
```
File → Open → выберите папку Time-to-learn
```

#### 3️⃣ Получите Gemini API ключ
1. Перейдите на https://ai.google.dev/
2. Нажмите **"Get API Key"**
3. Создайте новый ключ
4. Скопируйте его

#### 4️⃣ Создайте файл `.env`
В корневой папке проекта создайте файл `.env`:
```
GEMINI_API_KEY=your_key_here
```

#### 5️⃣ Запустите приложение
```
Run → Run 'app' (Shift + F10)
```

---

## 🛠️ Структура проекта

```
Time-to-learn/
├── app/                          # 📱 Основное приложение
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/             # Исходный код Kotlin/Java
│   │   │   ├── res/              # Ресурсы (макеты, картинки)
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── gradle/                       # Gradle обёртка
├── assets/                       # Дополнительные ресурсы
├── .github/                      # GitHub Actions, шаблоны
├── build.gradle.kts              # Корневой Gradle
├── settings.gradle.kts
├── .env.example
├── .gitignore
├── README.md                     # Этот файл
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE
```

---

## 🚀 Разработка

### Сборка проекта
```bash
./gradlew build
```

### Установка на устройство
```bash
./gradlew installDebug
```

### Запуск тестов
```bash
./gradlew test
```

### Сборка для Play Store
```bash
./gradlew assembleRelease
```

### Проверка кода
```bash
./gradlew lint
```

---

## 🌐 Веб-дем��

Веб-версия доступна на **Vercel**: 
🔗 https://time-to-learn-pi.vercel.app

Обновляется автоматически с каждым commit в main ветку.

---

## 📚 Технологический стек

| Технология | Описание |
|---|---|
| **Kotlin** | Современный язык программирования для Android |
| **Android SDK** | Официальный фреймворк для разработки |
| **Google Gemini API** | AI функционал для умных рекомендаций |
| **Gradle** | Система сборки проекта |
| **Android Studio** | IDE для разработки приложений |
| **Vercel** | Хостинг веб-версии |

---

## 🤝 Как помочь проекту

Мы благодарны за любые вклады! Есть несколько способов помочь:

### 🐛 Нашли баг?
1. Откройте **Issues** → **New Issue**
2. Опишите проблему как можно подробнее
3. Приложите логи и скриншоты

### ✨ Хотите добавить функцию?
1. Создайте **Fork** репозитория
2. Создайте ветку: `git checkout -b feature/awesome-feature`
3. Внесите изменения и закоммитьте: `git commit -m "✨ Add awesome feature"`
4. Отправьте **Pull Request**

📖 Подробнее в [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📋 API и конфигурация

### Переменные окружения (`.env`)

```env
# Google Gemini API
GEMINI_API_KEY=your_api_key_here

# Опционально
DEBUG=true
```

### Пример `.env.example`
```env
GEMINI_API_KEY=sk-...
```

---

## 📊 Статистика проекта

[![GitHub Stars](https://img.shields.io/github/stars/AlexTrader2278/Time-to-learn?style=social)](https://github.com/AlexTrader2278/Time-to-learn)
[![GitHub Forks](https://img.shields.io/github/forks/AlexTrader2278/Time-to-learn?style=social)](https://github.com/AlexTrader2278/Time-to-learn)
[![GitHub Issues](https://img.shields.io/github/issues/AlexTrader2278/Time-to-learn)](https://github.com/AlexTrader2278/Time-to-learn/issues)

---

## 🆘 Поддержка

Если у вас возникли вопросы:

1. 📖 **Прочитайте документацию** — может ответ здесь
2. 💬 **Создайте Discussions** — обсудите с сообществом
3. 🐛 **Откройте Issue** — сообщите об ошибке
4. 📧 **Свяжитесь с автором** — alextrader2278@github.com

---

## 📚 Полезные ссылки

- 📖 [Android Developer Docs](https://developer.android.com/)
- 🤖 [Google Gemini API](https://ai.google.dev/)
- 🎓 [Kotlin Documentation](https://kotlinlang.org/docs/)
- 🔧 [Gradle Documentation](https://docs.gradle.org/)
- 📱 [Android Studio Guide](https://developer.android.com/studio)

---

## 📄 Лицензия

Этот проект лицензирован под **MIT License**. 
Смотрите [LICENSE](LICENSE) для полного текста.

---

## 👨‍💻 Автор

**AlexTrader2278**

- 🐙 GitHub: [@AlexTrader2278](https://github.com/AlexTrader2278)
- 🌐 Веб-сайт: [time-to-learn-pi.vercel.app](https://time-to-learn-pi.vercel.app)

---

<div align="center">

### ⭐ Если вам нравится проект — поставьте звезду!

**Сделано с ❤️ для родителей и детей**

![Made with love](https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square)

</div>
