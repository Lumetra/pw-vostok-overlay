# PW Восток — Оверлей координат / Coordinates Overlay

---

## Русский

Оверлей для игры **Perfect World (RU)** — помогает искать сундуки и отблески на Восточных землях.

### Что умеет
- Висит поверх игрового окна
- Все координаты сундуков и отблесков для **Города Покоя** и **Города Тяньюй**
- Клик на координаты — копирует в буфер (вставляй в игру сам/сама)
- Две галочки на каждую точку: скопировано и пройдено
- Прогресс сохраняется между сессиями
- Навигация по локациям и страницам

### Запуск
Скачай `overlay.exe` из раздела [Releases](../../releases) и запусти двойным кликом. Ничего устанавливать не нужно.

### ⚠️ Windows говорит что файл опасный?
Это нормально. Windows показывает предупреждение на все `.exe` без цифровой подписи, а подпись стоит ~$200 в год — я слишком жадная чтобы за это платить.

Чтобы запустить: нажми **"Подробнее"** → **"Выполнить в любом случае"**.

Не доверяешь? Код полностью открыт — можешь прочитать `overlay.py` и убедиться что там нет ничего кроме координат и чекбоксов.

### Прогресс
Галочки сохраняются в `%APPDATA%\PWOverlay\progress.json`


---

## English

An overlay tool for **Perfect World (RU server)** to help find chests and glimmers in the Eastern Lands.

### Features
- Always-on-top window over the game
- All chest and glimmer coordinates for **City of Serenity** and **City of Tianyü**
- Click a coordinate to copy it to clipboard (paste into the game manually)
- Two checkboxes per point: copied and completed
- Progress is saved between sessions
- Navigate by location and page

### Usage
Download `overlay.exe` from the [Releases](../../releases) section and double-click to run. No installation required.

### ⚠️ Windows says the file is dangerous?
That's normal. Windows flags any unsigned `.exe`, and a code signing certificate costs ~$200/year — I'm too cheap to pay for that.

To run anyway: click **"More info"** → **"Run anyway"**.

Don't trust it? The source code is fully open — read `overlay.py` and see for yourself that it's nothing but coordinates and checkboxes.

### Progress file
Saved to `%APPDATA%\PWOverlay\progress.json`

