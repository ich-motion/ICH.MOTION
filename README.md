# ICH.MOTION CEP Panel for After Effects

![Version](https://img.shields.io/badge/version-3.2.1-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

[🇷🇺 Читать на русском (Russian Version)](#ichmotion-cep-панель-для-after-effects-ru)

Working as a motion designer in marketing taught me many things, but the main one is that After Effects is your best friend. However, it's the kind of friend that has a lot of problems.

To solve these problems, I created **ICH.MOTION**. This is a free and open-source CEP plugin that was initially conceived as a convenient tool for creating subtitles, but eventually evolved from a simple JSX script into a full-fledged plugin.

## ✨ Key Features
1. **Safe Zones:** Creates a safe zone for 9x16 (1080x1920) compositions with approximate guidelines for modern content platforms, plus optional guidelines for further cropping to 4x5.
2. **Smart Naming:** Convenient naming and renaming of compositions.
3. **Smart Subtitles:** A professional subtitle editor with transcription capabilities via Whisper.
4. **Presets Manager:** Conveniently search for your own animation presets, apply basic animations for subtitles, and apply custom presets starting from the in-point of text layers.
5. **ASK AI:** Chat with Gemini directly inside AE (supports free-tier accounts), plus the "AE Terminator" role that can understand and edit compositions.

## 🚀 Installation
1. Download the latest `.zxp` release.
2. Use a ZXP installer like [ZXPInstaller](https://zxpinstaller.com/) or [Anastasiy's Extension Manager](https://install.anastasiy.com/) to install it into After Effects.
3. Restart After Effects and open the panel via `Window -> Extensions -> ICH.MOTION`.

## 🤖 AI Setup
To use the **ASK AI** feature, you need a free API key from Google:
1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Create an API Key.
3. Paste it into the `Enter Google AI Studio Key...` field in the **ASK AI** tab and click **SAVE**.

## 🎙️ Auto SRT Setup
To use local transcription:
1. Go to the **SUBS** tab and click **Auto SRT**.
2. The plugin will prompt you to download `faster-whisper-xxl.exe`.
3. Select the folder containing the downloaded file. All transcription runs locally on your PC!

---

## 📝 License
This project is distributed under the **MIT** License. You are free to use, modify, and distribute it. See the [LICENSE](LICENSE) file for details.

<br><br><br>

---

# ICH.MOTION CEP Панель для After Effects (RU)

Работа моушн-дизайнером в маркетинге научила меня многим вещам, но главное: After Effects — твой лучший друг. Однако это такой друг, у которого есть много проблем.

Для решения этих проблем я и создал **ICH.MOTION**. Это бесплатный и общедоступный CEP-плагин, который изначально задумывался как удобный инструмент для создания субтитров, а в итоге превратился из простого JSX-скрипта в полноценный плагин.

## ✨ Ключевые возможности
1. **Safe Zones:** Создание сейвзоны для композиции 9x16 (1080x1920) с примерным учетом всех современных контент-платформ + опциональное добавление гайдлайнов для дальнейшего кропа в 4x5.
2. **Smart Naming:** Удобный нейминг и ренейминг композиций.
3. **Smart Subtitles:** Профессиональный редактор субтитров с возможностью транскрибации через Whisper.
4. **Presets Manager:** Удобный поиск своих пресетов анимации, базовые анимации для субтитров и возможность применения своих пресетов с начала текстовых слоев.
5. **ASK AI:** Чат с Gemini (для free-tier аккаунтов) прямо в AE + роль «AE Терминатор», который умеет понимать и править композиции.

## 🚀 Установка
1. Скачайте последний `.zxp` файл из релизов.
2. Установите его с помощью [ZXPInstaller](https://zxpinstaller.com/) или [Anastasiy's Extension Manager](https://install.anastasiy.com/).
3. Перезапустите After Effects и откройте панель через `Window -> Extensions -> ICH.MOTION`.

## 🤖 Настройка AI
Для работы вкладки **ASK AI** потребуется бесплатный ключ от Google:
1. Перейдите в [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Создайте API ключ.
3. Вставьте его в поле `Enter Google AI Studio Key...` во вкладке **ASK AI** и нажмите **SAVE**.

## 🎙️ Настройка Auto SRT (Whisper)
Для локальной генерации субтитров:
1. Перейдите во вкладку **SUBS** и нажмите **Auto SRT**.
2. Плагин предложит скачать файл `faster-whisper-xxl.exe`.
3. Укажите папку со скачанным файлом. Вся транскрибация будет проходить полностью локально на вашей видеокарте или процессоре!

---

## 📝 Лицензия
Этот проект распространяется под лицензией **MIT**. Вы можете свободно использовать, модифицировать и распространять его. Подробности в файле [LICENSE](LICENSE).
