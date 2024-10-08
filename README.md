# To-Do List

## Описание

Это десктопное приложение для управления списком задач, разработанное с использованием
фреймворка [Wails](https://wails.io). 

## Основные функции

1. **Создание задач**: Пользователь может добавлять новые задачи в список.
2. **Отображение задач**: Все задачи отображаются на экране.
3. **Удаление задач**: Пользователь может удалять задачи из списка.
4. **Отметка задач как выполненных**: Пользователь может отмечать задачи как выполненные.
5. **Сохранение состояния**: Состояние задач сохраняется между запусками приложения.

## Установка и запуск

1. Установите [Wails CLI](https://wails.io/docs/gettingstarted/installation) (если ещё не установлен):
   ```bash
   go install github.com/wailsapp/wails/v2/cmd/wails@latest
2. Для запуска приложения:

```
wails build && wails dev