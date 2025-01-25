
Sistema backend de notas. 

Este sistema funciona para crear y ver las notas credas. 


## Instalación del sistema

Tener una base de datos instalada (Mysql) y configurar el archivo .env para que se conecte a ella. 

*Si se ejecuta en un entorno local, las configuraciones deben ser como:*
```
DB_CONNECTION=mysql 
DB_HOST=127.0.0.1 
DB_PORT=3306    
DB_DATABASE=notas   
DB_USERNAME=root    
DB_PASSWORD=    
```

### Instalación de las migraciones
Ejecutar el siguiente comando para rellenar la base de datos con los blueprints definidos en las migraciones
```console
    php artisan migrate
```


### Ejectuar el servidor    
Para la ejecución del sistema se ejecuta el siguiente comando: 
```console
    php artisan serve
```
En la consola se mostrará el endpoint que usará el front con un mensaje 

"Server running on [http://127.0.0.1:8000]."
