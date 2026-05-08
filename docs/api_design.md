# API Design

## Suggested API endpoints

- `GET /api/stocks/history?symbol=&from=&to=` - fetch historical stock prices
- `GET /api/stocks/technical?symbol=&indicator=` - fetch technical indicator data
- `GET /api/news?symbol=&from=&to=` - fetch financial news
- `GET /api/watchlist` - fetch user watchlist
- `POST /api/watchlist` - add item to watchlist
- `PUT /api/watchlist/:id` - update watchlist item
- `DELETE /api/watchlist/:id` - soft-delete watchlist item
- `GET /api/chat/history` - fetch chat history
- `POST /api/chat/query` - send user query to chatbot
