# BulletinBoard
 BulletinBoard for skillfactory

### Содержание файла `.env`:
```
DEBUG=1
SECRET_KEY=...
DJANGO_ALLOWED_HOSTS=*

EMAIL_HOST=smtp.yandex.ru
EMAIL_PORT=465
EMAIL_USE_SSL=1
EMAIL_HOST_USER=...
EMAIL_HOST_PASSWORD=...
EMAIL_FROM=...

POSTGRES_DB=bulletinboard
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_HOST=db
POSTGRES_PORT=5432

CELERY_BROKER=redis://redis:6379/0
CELERY_BACKEND=redis://redis:6379/0
```