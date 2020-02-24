#INSTALACIÓN

- Eliminar los ficheros
    - 
- Necesitamos instalar
    - `$ sudo apt install make`
- Crear imagenes
    - `$ make docker-build`
- Arrancar contenedores
    - `$ make docker-start`
- Acceder al contenedor
    - `$ make docker-ssh-php`
    - `$ composer install`
- Permisos, solo hacer esto en local
    - `chmod 777 -R var/ generated/ pub/static/ pub/media/ app/etc/` 
- Acceder a magento
    - http://127.0.0.1/setup/#/landing-install
- Step 2: Add a Database
    - Database Server Host: **magento2-docker_db_1**
    - Database Server Username: **magento2**
    - Database Server Password: **magento2** 
    - Database Name: **magento2**
- Magento Admin Address:
    - http://127.0.0.1/admin_73jn3s/
    -
    
