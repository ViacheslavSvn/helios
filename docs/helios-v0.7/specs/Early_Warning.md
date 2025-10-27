# Early-Warning Module — Risk Triggers

## Цель
Предупреждать об отклонениях в ликвидности до критических уровней.

## Триггеры
- Depth < Threshold_Low
- Spread > Threshold_High
- Volatility ↑ за последние 15 минут

## Уровни оповещений
1. ⚠ Warning
2. ⛔ Critical

## Действия
- Запись в лог
- Отправка уведомления на Dashboard
- Передача данных в DLI Core
