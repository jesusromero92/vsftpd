# Acceso al servidor FTP: anónimo tiene permiso de escritura en el directorio sugerencias, que es un subdirectorio de su directorio raíz. 📄
## Procedemos a configurar el servidor para que el usuario Anonymous pueda escribir solo en /sugerencias

### Pasos

### 1. Creamos algunos archivos en /sugerencias para luego subirlos

### 2. Le damos los permisos 777 a la carpeta sugerencias
 ``` chmod -R 777 /srv/ftp/sugerencias```

### 3. Configuramos el /etc/vsftpd.conf de la siguiente manera

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.2.1.png)

### 4. Reiniciamos el servicio

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/reinicio.png)

### 5. Comprobamos que podemos subir los archivos

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.6.png)


### 6. Comprobamos subir un archivo a una carpeta que no sea /sugerencias

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.7.png)



