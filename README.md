<p align="center"><img src="https://raw.githubusercontent.com/dewanakl/Kamu/main/public/kamu.png" width="200" alt="kamu"></p>

<p align="center">
<a href="https://php.net"><img src="https://img.shields.io/packagist/dependency-v/kamu/framework/php.svg?color=birghtgreen" alt="PHP Programming Language"></a>
<a href="https://packagist.org/packages/kamu/framework"><img src="https://img.shields.io/packagist/dt/kamu/framework" alt="Total Downloads"></a>
<a href="https://cie.my.id"><img src="https://cie.my.id/undangan-api?label=views&color=brightgreen" alt="views"></a>
<a href="https://shields.io"><img src="https://img.shields.io/github/repo-size/dewanakl/undangan-api?color=brightgreen" alt="Repo size"></a>
<a href="https://shields.io"><img src="https://img.shields.io/github/license/dewanakl/undangan-api?color=brightgreen" alt="License"></a>
</p>

## About Kamu

"Kamu" merupakan PHP framework yang sangat simpel, memberikan pengalaman seolah-olah berada di localhost meskipun dalam mode production. Dibantu dengan "Saya" konsol yang membantu pengembangan aplikasi secara efisien.

## Deployment on vercel

- Install package

    ```bash
    composer install
    ```

- Create .env file

    ```bash
    cp .env.example .env
    ```

- Execute migration database

    ```bash
    php saya migrasi --gen
    ```

- Create key application

    ```bash
    php saya key
    ```

- Push on your github.
- Create new project in vercel.
- Import from your repository.
- Change environment variables in your project on vercel.
- Add this :
  - DB_HOST (your host cloud dbms)
  - DB_PASS (your password cloud dbms)
  - DB_USER (your username cloud dbms)
  - DB_NAME (your name of database cloud dbms)
  - DB_PORT (your port cloud dbms)
  - DB_DRIV (type cloud dbms [ex. mysql or pgsql])
  - JWT_KEY [ex. 123]
  - HTTPS [true]
  - DEBUG [false]
  - LOG [false]
  - APP_KEY [copy from your local env]
- Click deployments tab in vercel project.
- Click the most recent deploy.
- Click dot three and redeploy.
- Done.

## Get Started Project

- Create a project with composer

    ```bash
    composer create-project kamu/kamu coba-app
    ```

- Move the folder

    ```bash
    cd coba-app
    ```

- Run in development server

    ```bash
    php saya coba
    ```
## License

Kamu framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
