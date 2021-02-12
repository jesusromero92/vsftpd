# Acceso al servidor FTP: anónimo tiene solo permiso de lectura en su directorio de trabajo. 📄
Vamos a configurar el servidor FTP para que Anonymous tenga solo modo lectura en su directorio de trabajo,no podrá subir nada


### Pasos

### 1. Activamos el usuario Anonymous || /etc/vsftpd.conf
    
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/6.1.1.png)
   
   
### 2. Creamos un archivo en el servidor que luego vamos a poder descargar

   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/6.2.2.png)
   
### 3. Accedemos mediante FTP y comprobamos bajarnos el archivo prueba.txt
   
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/6.2.1.png)
   
   **Como vemos,nos ha dejado descargarlo**
   
   
### 3. Para comprobarlo,intentaremos subir un archivo
   
  ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/6.3.1.png)
   
   
