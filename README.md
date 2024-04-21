# Описание
Описание форматов игровых ресурсов и инструменты для их просмотра для игр от GFI/MiST Land/Играющие кошки.   

## Форматы  

**1. Истории войн: Наполеон (2000)**  

| № | Формат файла       | Шаблон (010Editor)     |   Описание |
| :--- | :--------- | :----------- |  :---------- | 
| 1 | .pak  | [PAK.bt](templates/010editor/PAK.bt) | Архив игровых ресурсов |

## Инструменты

### Quickbms

| № | Формат  | Инструмент |    Описание |
| :--- | :--------- | :----------- | :---------- | 
| 1 | .pak | [unpack_pak_napoleon.bms](scripts/quickbms/unpack_pak_napoleon.bms)  | Распаковка архива игровых ресурсов Истории войн: Наполеон (2000) |

    Как использовать quickbms скрипты
    1. Нужен quickbms https://aluigi.altervista.org/quickbms.htm
    2. Для запуска в репозитории лежит bat файл с настройками, нужно открыть его и задать свои пути: до места, где находится quickbms, папки с игрой и места куда нужно сохранить результат.
    3. Запустить процесс через bat файл или вручную (задав свои параметры для запуска quickbms, документация на английском есть здесь https://aluigi.altervista.org/papers/quickbms.txt ). 
