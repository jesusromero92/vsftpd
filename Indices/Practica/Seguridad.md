# Seguridad
## Procedemos a instalar un certificado para que nuestro FTP sea **seguro**

### Pasos

### 1. Instalamos el paquete para generar el certificado

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.1.png)

### 2. Generamos el certificado rellenando los siguientes datos

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.2.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.2.2.png)



### 3. Configuramos /etc/vsftpd de la siguiente manera
Buscamos estas lineas que están al final del archivo y lo modificados para que quede asi
   
![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.3.png)

### 4. Reiniciamos

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/reinicio.png)

### 5. Y nos conectamos desde el cliente de esta forma


![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.4.png)

![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.5.png)

**Abajo se puede observar que aparece el candado de que ha funcionado el certificado y la web es segura**
![](https://github.com/jesusromero92/vsftpd/blob/main/Fotos/9.6.png)
