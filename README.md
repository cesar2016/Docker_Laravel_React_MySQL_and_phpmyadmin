
- La finalidad de este repositorio es, poder levantar con unos pocos comandos de consola, un stack con lo necesario para trabajar con:
# React | Laravel | MySQL | PhpMyadmin | Server Apache

## Intrucciones para levantar el Entorno

# 1 colonar repositorio desde
    URL: https://github.com/cesar2016/Docker_Laravel_React_MySQL_and_phpmyadmin

# 2 desde la raiz ejecutar
    docker-compose up -d     #levanta todos los contenedores
    cd api && cp .env.example .env #habilita las variables de entorno
    docker exec my_back php artisan migrate  #Ejecuta las migraciones de laravel

# 3 Ingresar desde el navegador
    Frontend: http://localhost:3001
    backend: http://localhost:8200

    
    phpmyadmin: http://localhost:8300
        user: admin
        password: admin1234

- El proyecto de backend esta generado con composer en laravel-lumen y se encuentra en /api
- El proyecto de frontend esta generado con node.js y React en /front

I
## AUTOR
- cesars.pro@gmail.com
- Linkedin: https://www.linkedin.com/in/cesar-sanchez-dev/



        





