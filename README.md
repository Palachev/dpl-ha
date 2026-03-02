# dpl-ha

Deep link лендинг для Happ.

## Использование

Открывайте ссылку в формате:

`https://<ваш-домен>/link/?url_ha=<URL_ПОДПИСКИ>`

Пример:

`https://<ваш-домен>/link/?url_ha=https%3A%2F%2Fpanel.dagdev.ru%2Fsub%2FdGdfNzgwMTM3MjQwNiwxNzcwODk1NTI1h-t-qGEnLG`

## Какой deeplink формируется

Сервис формирует deeplink строго в формате:

`happ://add/<URL_ПОДПИСКИ>`

Пример:

`happ://add/https://panel.dagdev.ru/sub/dGdfNzgwMTM3MjQwNiwxNzcwODk1NTI1h-t-qGEnLG`

## Шаги для пользователя

1. Установить Happ.
2. Открыть вашу ссылку `/link/?url_ha=...`.
3. Если автооткрытие не сработало — нажать кнопку «Открыть подписку в Happ».
