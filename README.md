# C2C Rent Platform

Маркетплейс для аренды вещей между частными лицами.

## Структура

### Backend (микросервисы)
- `user-service` — авторизация, профили
- `catalog-service` — объявления, каталог
- `deal-payment-service` — сделки, ЮKassa
- `communication-service` — чат, отзывы
- `notification-service` — уведомления
- `api-gateway` — единая точка входа

### Frontend
- `frontend` — основное веб-приложение

### Mobile
- `mobile` — нативное Android-приложение
