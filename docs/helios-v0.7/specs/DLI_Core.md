# DLI Core — Metrics & Decision Rules

## Входные данные
- Spread (Ask–Bid)
- Depth (Liquidity per route)
- Volatility (σ)
- Fees & Gas cost

## Выходные данные
- Балансировка маршрутов
- Алерты дефицита ликвидности
- Обновление Route Ranking

## Логика
1. Получаем метрики с L4 Telemetry
2. Рассчитываем весовые коэффициенты
3. Корректируем маршруты и уведомляем DLI Dashboard
