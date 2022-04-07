# Парсер документации Python

Включает в себя следующие возможности:
- Проверка обновлений Python
- Загрузка документации
- Проверка статусов PEP

## Как пользоваться
- Скачать проект:
```
https://github.com/K3llar/bs4_parser_pep.git
```
- Перейти в директорию проекта:
```
cd bs4_parser_pep
```
- Создать виртуальное окружение:
```
python -m venv venv
```
- Установить зависимости:
```
pip install -r requirements.txt
```

## Доступны следующие команды
Ссылки на статьи с последними обновлениями для каждой версии Python:
```
whats-new
```
Статус последних версий Python:
```
latest-versions
```
Количество PEP'ов по статусам и общее количество:
```
pep
```
Загрузка документации последней версии Python в формате .zip
```
download
```

### Дополнительные аргументы
Показать доступные команды:
```
-h, --help
```
Очистить кэш:
```
-c, --clear-cache
```
Вывод в терминал в виде таблицы/сохранить в файл .csv:
```
-o {pretty,file}, --output {pretty,file}
```
