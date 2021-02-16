# Práctica de cómo CREAR USUARIOS VIRTUALES VSFTPD

### 1. Instalamos los siguientes paquetes

* ``` apt install apache2-utils```

* ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.1.png)


### 2. Configuramos el archivo /etc/vsftpd.conf de la siguiente forma

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.2.1.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.2.2.png)

### 3. Procedemos a crear una carpeta donde se guardan la lista de usuarios y la lista de usuarios virtuales

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.3.1.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.3.2.png)


### 4. Vamos a /etc/pam.d y configuramos el siguiente archivo de esta forma

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.4.png)

### 5. Creamos el usuario virtual

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.5.png)


### 6. Creamos el siguiente directorio y entramos

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.7.png)

### 7. Creamos un archivo de configuración por cada usuario creado

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.8.png)


### 8. Ahora creamos la ruta donde podrá acceder dicho usuario

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.9.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.10.png)

### 9. Y ahora accedemos con el usuario creado

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/8.11.png)


### 10. Retoques finales
Con la configuración anterior,solo podrán acceder los usuarios virtuales.
Con los retoques que se va a hacer ahora,podrán acceder todo el mundo,tanto anonymous,usuarios virtuales y usuarios del sistema

* Añadimos en ```/etc/vsftpd.conf``` ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/fin1.png)

+ Añadimos en ```/etc/pam.d/vsftpd``` ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/fin2.png)
