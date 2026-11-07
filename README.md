# Fieldwatch — Ukrainian language pack (uk)

Ukrainian translation of the [Fieldwatch](https://github.com/OffGridPete/Fieldwatch) app interface, written for **Fieldwatch 1.1.42** following the official [language pack author guide](https://github.com/OffGridPete/Fieldwatch/blob/main/docs/language-pack-author-guide.md).

Український переклад інтерфейсу застосунку [Fieldwatch](https://github.com/OffGridPete/Fieldwatch) для **версії 1.1.42**, зроблений за офіційним [гайдом для авторів мовних пакетів](https://github.com/OffGridPete/Fieldwatch/blob/main/docs/language-pack-author-guide.md).

## Встановлення

1. Завантажте [`fieldwatch-language-uk.json`](fieldwatch-language-uk.json) на телефон.
2. У Fieldwatch: **Settings → Language → Import language pack** і виберіть файл.
3. Підтвердьте імпорт.

Повернути англійську: **Налаштування → Мова → Видалити мовний пакет**.

## Що всередині

- 1768 з 1768 рядків шаблону 1.1.42.
- Ключі й плейсхолдери (`{n}`, `{name}` …) такі самі, як в англійському шаблоні. Кожен рядок вкладається у свій ліміт довжини (`max`), переноси рядків є лише там, де вони є в англійському тексті.
- Wi-Fi, Bluetooth, GPS, GNSS, MAC, RSSI, OUI, SSID, ATAK, CSV, PDF лишаються як є. Терміни Fieldwatch перекладено простими словами: sit → «сеанс», signature → «сигнатура», Extra attention → «Підвищена увага».
- Форм множини немає, бо формат їх не підтримує, тому лічильники записано як «пристроїв: {n}».
- Назви сигнатур, нотатки каталогу та Extra attention застосунок завжди показує англійською. Цей пакет їх не змінює.

## Після оновлення Fieldwatch

Нові рядки показуватимуться англійською, доки пакет не оновлять. Якщо знайдете помилку чи невдалий переклад, відкрийте issue в **цьому** репозиторії, а не в Fieldwatch.

## Note

Language packs are made by other people. This pack is not reviewed or certified by Off Grid Pete LLC. English source strings © Off Grid Pete LLC (MIT). Translation released under the MIT License.
