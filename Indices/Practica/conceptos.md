# Aquí se recoge los conceptos básicos de VSFTPD

### 1.  Ver version de VSFTPD instalado

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.1.1.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.1.2.png)
      
      
### 2.  Servicio asociado --> vsftpd

**Reiniciar servicio** --> ```systemctl restart vsftpd```

**Recargar servicio** --> ```systemctl reload vsftpd```
    
    
    
### 3.  Ficheros de configuración
            
   * Fichero de configuracion de VSFTPD
   
     Se encuentra en /etc y se llama vsftpd.conf **/etc/vsftpd.conf**
       
  ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.4.png)
  
  
### 4. Usuarios Creados en la Configuración

   * Se crea un usuario y un grupo
   
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.2.1.png)
   
   ![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/5.2.1.png)
   
   
### 5. Directivas

   * **local_enable**
            Si está a YES se permite que los usuarios locales de la máquina servidor puedan iniciar
            conexiones FTP desde clientes. Por defecto, está a YES.
            
   * **cmds_allowed**
            Permite establecer una lista con los comandos ftp que va a aceptar el servidor.
            
   * **ftpd_banner**
            Permite establecer un mensaje que se dará a los clientes cuando inicien una conexión
            con el servidor.
            
   * **anonymous_enable**
            Por defecto está a YES estableciendo que los usuarios anónimos (anonymous y ftp)
            pueden iniciar sesiones o conexiones FTP.
            
   * **local_root**
            Indica la carpeta raíz del sitio FTP. Es la carpeta en la que los usuarios tienen las
            carpetas a las que acceden cuando inician conexiones FTP. Por defecto es /home.
            
       [Saber Más](https://ikastaroak.birt.eus/edu/argitalpen/backupa/20200331/1920k/es/ASIR/SRI/SRI03/es_ASIR_SRI03_Contenidos/SRI03_CONT_R22_DIRECTIVAS_vsftpd.pdf)



   
