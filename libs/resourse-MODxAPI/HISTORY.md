## 1.0.0 (24.05.2013)
* Вынесена MODX логика в абстрактный вспомогательный класс
* Возможность создание классов с произвольной логикой и для любых таблиц
* Портирован код resource.php в modResource.php
* Вспомогитаельные методы вынесены в отдельный класс APIhelpers, который наследуется для абстрактного класса MODxAPI

## 0.4.1 (23.05.2013)
* Перечислены все основные поля документа
* Исправлена проверка псевдонимов на дубликаты
* Изменен метод генерации псевдонимов у дубликатов
* Переименован метод clear_chache() в clearCache()

## 0.4.0 (22.05.2013)
* Установка шаблона по имени
* Пропуск системных документов из удаляемых методом delete()
* Новые методы fromJson() и toJson() с поддержкой callback функций
* Корректные аргументы при вызове плагинов на событии OnDocFormSave
* Поддержка новых событий OnBeforeDocFormSave, OnEmptyTrash, OnBeforeEmptyTrash
* Массовое удаление документов через WHERE IN

## 0.3.0 (22.05.2013)
* Поддержка короткого синтаксиса
* Метод dublicate переименован в edit()
* Новые параметры у метода save()
* Проверки в методах set() и get()
* Добавлен метод clearLog()
* $modx передается как аргумент, а не global
* Замена PREFIX на $modx->getFullTableName()
* Продвинутый генератор алиасов с проверкой на дубликаты
* Внутренний рефакторинг с заменой на методы set и get
* Корректировка публичных и приватных методов
* Добавлены методы fromArray() и toArray()
* Массовое удаление документов

## 0.2.0 (21.05.2013)
* Добавлены метод dublicate(), get(), delete()
* Добавлена поддрежка плагинов OnSiteRefresh и OnDocFormSave
* Возможность отключить срабатывание плагинов при помощи параметров у метода save()

## 0.1.0 (20.05.2013)
* Создание проекта
