# Laravel Movies App

* Movies App designed using Laravel and the TMDb API.

![screenshot](https://user-images.githubusercontent.com/4316355/78681326-98bd1480-78ba-11ea-9cd8-3052397a87a7.png)

## Preview
To see this a live deploy of this project

  * [Movies App](http://movies-app-laravel.herokuapp.com/)



## Installation

1. Clone the repo and `cd` into it
1. `composer install`
1. Rename or copy `.env.example` file to `.env`
1. Set your `TMDB_TOKEN` in your `.env` file. You can get an API key [here](https://www.themoviedb.org/documentation/api). Make sure to use the "API Read Access Token (v4 auth)" from the TMDb dashboard.
1. `php artisan key:generate`
1. `php artisan serve` or use Laravel Valet or Laravel Homestead
1. Visit `localhost:8000` in your browser
