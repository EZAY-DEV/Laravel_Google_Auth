
## Laravel social Auth (Google)

- composer create-project laravel/laravel laravel_google_auth
- composer require laravel/ui 
- php artisan ui bootstrap --auth
- npm install
- npm run dev 

#### install socialite package
- composer require laravel/socialite
- add Laravel\Socialite\SocialiteServiceProvider::class in providers array in config/app.php file
- add 'Socialite' => Laravel\Socialite\Facades\Socialite::class  in aliases array in config/app.php file

#### create new google app 
- Create Google a project : https://console.developers.google.com/projectcreate

- Create Google credentials : https://console.developers.google.com/apis/credentials

add client_id and secret in .env file  
- GOOGLE_CLIENT_ID =
- GOOGLE_CLIENT_SECRET =

- add driver data in config/service.php file 
