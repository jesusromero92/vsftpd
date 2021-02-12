# Comparativa entre NGINX y Apache ⌨️

Ambos son los dos servidores web más usado,pero ambos presentan una serie de diferencias y son las siguientes:

## Proftpd
ProFTPd es un popular servidor FTP para Linux. ProFTPd es un programa que fue escrito para ser un software poderoso y configurable, por lo que no es necesariamente el servidor de FTP más liviano disponible, pero si el más conocido y el más usado. en servidores.

## Diferencias
Ambos servidores destacan por carácteristicas exclusivas pero ProFTPD empieza a quedarse obsolute aunque sea más fácil de configurar que VSFTPD
Hoy en día se usa mas VSFTPD,incluso viene por defecto en CENT OS

| Proftpd | Vsdtpd |
|-|-|
| Tiene un archivo de configuración principal, que contiene directivas y grupos de directivas que son muy intuitivas si has utilizado el servidor web Apache, ya que se basaron en él para crear Proftpd. | Dispone de configuraciones de IP virtual |
| Dispone de un directorio llamado «.Ftpaccess» que es similar a «.htaccess» de Apache. | Puedes crear usuarios virtuales |
| Es muy fácil configurar múltiples servidores FTP virtuales y servicios FTP anónimos. | Puede funcionar en modo operación independiente o inetd. |
| Dispone de directorios raíz anónimos que no requieren ninguna estructura de directorio, archivos binarios del sistema u otros archivos del sistema. | Las opciones de configuración por parte del usuario son muy avanzadas. |
| No hay comando SITE EXEC,evitando así, los problemas que puede acarrear en seguridad. | Las opciones de configuración por parte del usuario son muy avanzadas. |
| Los directorios y archivos ocultos están basados en permisos de estilo Unix. | Dispone de un acelerador de ancho de banda para que funcionen las cargas y descargas aún mejor. |
| Dispone de modo autónomo que se ejecuta como un usuario sin privilegios para disminuir las posibilidades de ataques. | Puedes establecer límites por IP. |
________
## Seguir leyendo

[Leer Mas](https://www.redeszone.net/tutoriales/servidores/mejores-servidores-ftp-ftpes-linux/)
________
## Entonces,¿Cuál eligo?
Ambos servidores van a funcionar bien.Es ya cuestión de cada uno que elija el que mejor se adapte a sus necesidades.

