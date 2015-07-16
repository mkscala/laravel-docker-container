# laravel docker container

  > This is a fork from eboraas/laravel

## New features :
  * Laravel 5 (and not the older one 4)
  * Composer updated
  * sqlite support for PHP
  * packages updated and upgraded

## Installation

#### With docker build
  ```
  git clone https://github.com/sheebypanda/laravel-docker-container.git
  ```
  ```
  cd laravel-docker-container
  ```
  ```
  docker build .
  ```

#### Or with docker pull
```
docker pull sheebypanda/laravel:latest
```


## Usage
  * Serving a fresh Laravel installation :
  ```
  docker run -p 80:80 -p 443:443 -d sheebypanda/laravel
  ```
  and go to [localhost](http://localhost)

  * Serving your own app :
  ```
  docker run -p 80:80 -p 443:443 -v path/to/myapp:/var/www/laravel -d sheebypanda/laravel
  ```
