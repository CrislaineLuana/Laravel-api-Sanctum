<h1 align="center"> 
    <p>RestAPI - Laravel - Products 📑</p>
</h1>

## 📕 About

In this project a **RestAPI** was developed. Making it possible to keep products. For data security, it also has an authorization system, designed with **Sanctum**.


## 🔨 Tools

- [Laravel](https://laravel.com/)
- [Sanctum](https://laravel.com/docs/9.x/sanctum)
- [MySQL](https://www.mysql.com/)
- [Postman](https://www.postman.com/)


## 🤗 How Contribute

```bash
    # Clone the project
    $ git clone https://github.com/CrislaineLuana/Laravel-api-Sanctum.git
```

```bash
    # Enter directory
    $ cd Laravel-api-Sanctum
```

```bash
    # Install dependencies
    $ composer install
```

```bash
    # Copy .env.exemple to .env
    $ php -r "copy('.env.example', '.env');"
```

```bash
    # Generate artisan key
    $ php artisan key:generate
```

```bash
    # Update the database info in .env directory with your connection
```
 <img src="./public/readme/.envBanco.png">


 ```bash
    # Make a migration
    $ php artisan migrate
```

 ```bash
    # Run the project
    $ php artisan serve
```

 ```bash
    # Run the requests on some API platform. In this project I used Postman 
```



## 📃 License 
This project is under the MIT license. See the file [LICENSE](./LICENSE.TXT) for more details.