# Task01 — Исходные данные

## Структура файлов данных

| Файл | Описание | Формат |
|------|----------|--------|
| `genres.txt` | Список жанров фильмов | По одному жанру на строку |
| `movies.csv` | Информация о фильмах | `movieId,title,genres` (жанры через `\|`) |
| `occupation.txt` | Список профессий пользователей | По одной профессии на строку |
| `ratings.csv` | Оценки пользователей фильмам | `userId,movieId,rating,timestamp` |
| `tags.csv` | Теги пользователей к фильмам | `userId,movieId,tag,timestamp` |
| `users.txt` | Информация о пользователях | `userId\|name\|email\|gender\|birthdate\|occupation` |

## Служебные файлы

| Файл | Описание |
|------|----------|
| `ratings_count.txt` | Минимальный и максимальный `userId` из `ratings.csv` и число строк с ними |
| `sqlite.txt` | Версия установленного SQLite и список режимов вывода `.mode` |