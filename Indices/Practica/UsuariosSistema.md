# Acceso al servidor FTP: usuarios del sistema 📄
## En está práctica,vamos a modificar la configuración para que los usuarios del sistema puedan acceder

Voy a crear en el servidor un usuario llamado jesus

### Pasos

### 1. Creamos el directorio de trabajo del usuario y creamos el usuario

   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.2.png)

### 2. Cambiamos el propietario del directorio
    
  ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.3.png)
    

### 3. Configuramos el archivo de configuración de la siguiente forma

   * Deshabilitamos el ipv6 y activamos el listen
    
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.4.png)
   
   * Descomentamos las siguientes lineas
    
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.5.png)
    
   * Quitamos los permisos de escritura
   
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.6.png)

### 4. Comprobamos que podemos acceder

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.5.7.png)


