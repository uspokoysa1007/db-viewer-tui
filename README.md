# db-viewer-tui

TUI-просмотрщик баз данных на Rust (ratatui): SQLite и PostgreSQL прямо в терминале.

## Возможности (план)

- подключение к SQLite и PostgreSQL;
- список таблиц и их схем;
- просмотр строк с пагинацией;
- произвольные SQL-запросы;
- экспорт результата в CSV;
- история запросов.

## Стек

- Язык: Rust
- Планируемые библиотеки: `ratatui`, `crossterm`, `rusqlite`, `tokio-postgres` / `sqlx`

## Сборка и запуск

```bash
cargo build --release
cargo run --release -- db.sqlite
```

## Лицензия

MIT
