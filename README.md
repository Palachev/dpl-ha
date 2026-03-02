# dpl-ha

Deep link лендинг для Happ.

## Использование

Открывайте ссылку в формате:

`https://<ваш-домен>/link/?url_ha=<URL_ПОДПИСКИ>`

Пример:

`https://<ваш-домен>/link/?url_ha=https%3A%2F%2Fpanel.dagdev.ru%2Fsub%2F%D0%BA%D0%BB%D1%8E%D1%87`

## Что происходит

1. Страница пробует открыть приложение прямым deeplink:
   - `happ://link?url_ha=<encoded_subscription_url>`
2. Если приложение не открылось, показываются кнопки:
   - повторно открыть `happ://...`
   - открыть web-fallback `https://happ.pro/link?...`
