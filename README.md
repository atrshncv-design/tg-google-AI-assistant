# Telegram AI Assistant с интеграцией Google Calendar

Telegram-бот — личный AI-ассистент с задачами, напоминаниями и трекингом в Google Calendar.

## Проблема
Ручное планирование задач и напоминаний отнимало время, интеграция с календарем была неудобной.

## Решение
- LLM (Grok / Claude) для обработки естественного языка (запросы типа "добавь встречу завтра в 14:00")
- n8n для оркестрации: парсинг → создание события в Google Calendar → подтверждение в Telegram
- Tool-calling для действий (create_event, list_events)
- Simple Memory для контекста разговора

## Ключевые результаты
- Полная автоматизация планирования задач
- Сокращение времени на организацию дня на 50–70%
- Удобный self-service интерфейс в Telegram

## Стек
- Telegram Bot API
- n8n
- Google Calendar API
- LLM с tool-calling (Claude / Grok / GPT / Gemini )
