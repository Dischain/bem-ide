# BEM IDE — прототип редактора БЭМ проектов

## Что это?

Прототип редактора кода, удовлетворяющий потребностям БЭМ разработчика.

## Использование

* git clone https://github.com/belyanskii/bem-ide.git (клонируем)
* cd bem-ide
* npm i
* bem make
* npm start (запускаем сервер на 7777 порту)

После запуска на [http://localhost:7777/](http://localhost:7777/) - будет доступен прототип редактора.

## Что реализовано в данный момент?

* Построение списка блоков из заданных уровней (уровни задаются в блоке `data-provider`, метод `getLevelsList`)
* Отображение единого редактора для БЭМ сущности
  * Получение реализации блока со всех уровней и отображение в редакторе
  * Сохранение при нажатии на `cmd + s` или `ctrl + s`
* Фильтр по технологиям

## Планы на ближайшее будущее

* Добавить возможность создавать новые БЭМ сущности (на данный момент возможна только работа с существующими)
* Реализовать табы (для работы с несколькими блоками сразу)
