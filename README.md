# laravel 11 Reverb chat
A real-time chat application built with Laravel and Reverb, offering instant messaging, user authentication, and a responsive UI. This project showcases how to integrate Laravel with modern chat features for seamless communication, message history, and a smooth user experience.  Let me know if you'd like to adjust any part of it!


## Documents:

Laravel Document : https://laravel.com/docs/11.x/reverb

Laravel Reverb : https://reverb.laravel.com

## Installation:

1. Clone the repository:
```
git clone https://github.com/hardik-variya/reverb-chat.git
```
2. Navigate to the project directory:
```
cd reverb-chat
```
3. Install dependencies:
```
composer install
npm install # or yarn install
```
4. Copy .env.example & Generate application key:
```
cp .env.example .env
php artisan key:generate
```
5. Configure database connection:

```
Edit .env file according to your database credentials.

DB_DATABASE=reverb_chat
DB_USERNAME=root
DB_PASSWORD=
```

6. Migrate database tables and run seeder
```
php artisan migrate
php artisan db:seed
```
7. Start development server
```
npm run dev:tailwind && npm run build:tailwind
php artisan serve
php artisan reverb:start
```
You can also use this command

```
php artisan serve --host=192.168.*.** --port=8000 

Set output URL in .env -> APP_URL 

APP_URL= http://192.168.*.**:8000
```

## Photos
![Spec Coder](https://i.postimg.cc/3xtp6rtZ/Screenshot-from-2024-11-16-15-43-13.png)
#
![Spec Coder](https://i.postimg.cc/Vvsm3wGj/Screenshot-from-2024-11-16-15-35-51.png)
