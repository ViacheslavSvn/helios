# Route Ranking v0.2 — Scoring Model

## Метрики
- Spread Weight
- Liquidity Depth
- Stability Factor
- Fee Ratio

## Формула
Rank = α*Depth - β*Spread - γ*Fee + δ*Stability

## Применение
- Обновляется каждые 10 минут
- Используется DLI Core и Reports
