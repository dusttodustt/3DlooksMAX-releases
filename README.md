# 3DlooksMAX

Плагин для 3ds Max 2025 (Corona, архвиз): быстрые действия с камерами и сплайнами, вкладка на ribbon, обновление изнутри плагина. Здесь лежат только готовые релизы.

## Установка

1. Скачайте **[3DlooksMAX.mzp](https://github.com/dusttodustt/3DlooksMAX-releases/releases/latest/download/3DlooksMAX.mzp)** (последняя версия).
2. Перетащите файл в окно 3ds Max 2025 (во вьюпорт). Или: Scripting → Run Script → выбрать файл.
3. В окне установщика нажмите **Install**. Если найдутся старые скрипты с теми же командами (`#KolyaGTP`), установщик предложит перенести их в резервную папку.
4. Перезапустите 3ds Max. Появится вкладка **3DlooksMAX** на ribbon.

Дальше обновления приходят сами: вкладка 3DlooksMAX → **Check Updates**. Новая версия ставится при закрытии Max, **Roll Back** возвращает предыдущую.

## Удаление

Закройте Max и удалите папку `%APPDATA%\Autodesk\ApplicationPlugins\3DlooksMAX`. Настройки лежат в `%APPDATA%\KolyaGTP\looksmax`, их можно удалить тоже.

## Файлы релиза

- `3DlooksMAX.mzp` — установщик (перетащить в Max).
- `3DlooksMAX-X.Y.Z.zip` — пакет для обновления из плагина.
- `manifest.json` — список версий и изменений для Check Updates.
