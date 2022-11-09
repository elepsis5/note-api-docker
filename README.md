<p align="center"><img src="https://cdn.contactcenterworld.com/images/company/readme-1200px-logo.png" width="400"></p>

## About 

В приложении реализована возможность тестирования с использованием
фейковых данных. Для этого необходимо инициализировать создание БД и запуск сидера.
 
Порядок действий:

1. docker-compose up;
2. docker-compose exec web bash;
3. cd note_api.dev/;
4. php artisan migrate --seed;


