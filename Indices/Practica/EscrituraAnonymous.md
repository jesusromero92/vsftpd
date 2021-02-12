# Acceso al servidor FTP: anónimo tiene permiso de escritura en el directorio sugerencias, que es un subdirectorio de su directorio raíz. 📄
 Procedemos a configurar el servidor para que el usuario Anonymous pueda escribir solo en /sugerencias

### Pasos

### 1. Hacemos los siguientes comandos:

* Cambiamos el dueño de /srv/ftp a ftp(Anonymous)
* Creamos una carpeta dentro que se llame sugerencias
* Le cambiamos el dueño para que sea ftp(Anonymous)
* Y eliminamos el permiso de escritura en /srv/ftp
* Con esto hemos conseguido que Anonymous solo pueda escribir en /sugerencias,es decir,solo pueda bajar archivos

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.2.png)

### 2. Configuramos el /etc/vsftpd.conf de la siguiente manera

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.3.png)

### 4. Comprobamos que podemos subir archivos pero no bajar nada

* Subir
![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.4.png)

* Descargar

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.5.png)

### 5. Y comprobamos que en / no se puede subir nada

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/7.6.png)





