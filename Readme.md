# NewsPaper Deploy

## Использование

1. Клонируйте репозиторий и перейдите в директорию проекта:
```
   git clone https://github.com/eutusikova/news-paper-deploy.git news-paper-deploy
   cd news-paper-deploy/NewsPaper_Deploy
```
2. Соберите и запустите все контейнеры:
```
   sudo docker compose up --build
```
3. После запуска проверьте работу сервисов:
3.1 HAProxy:
```
   http://localhost/haproxy?stats
```
3.2. Frontend:
```
   http://localhost/
```
3.3 API / Новости:
```
   http://localhost/news/show/1
```

