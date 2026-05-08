# Database Schema

## Suggested tables

- `users`
- `stocks`
- `stock_prices`
- `stock_news`
- `watchlists`
- `watchlist_items`
- `watchlist_history`
- `chat_sessions`
- `chat_messages`

## Soft delete strategy

- Use `is_deleted BOOLEAN` or `deleted_at TIMESTAMP` instead of removing rows.
- Keep history for audit and undo.
