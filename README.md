# dpl-ha

Статическая страница для GitHub Pages, которая формирует deeplink в Happ.

## Рабочий формат ссылки

Можно открывать и корень, и `/link/`:

- `https://<ваш-домен>/?url_ha=<URL_ПОДПИСКИ>`
- `https://<ваш-домен>/link/?url_ha=<URL_ПОДПИСКИ>`

Пример:

`https://<ваш-домен>/?url_ha=https%3A%2F%2Fpanel.dagdev.ru%2Fsub%2FdGdfNzgwMTM3MjQwNiwxNzcwODk1NTI1h-t-qGEnLG`

## Что делает страница

- Показывает кнопку: **«Добавить подписку»**
- По нажатию открывает:
  - `happ://add/<URL_ПОДПИСКИ>`
- Если Happ не установлен — есть кнопка установки.
