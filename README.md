Instala y configura vsftpd con MariaDB de manera que el servidor FTP permita inicios de sesión de usuarios almacenados en la base de datos

<b>Problemas conocidos</b><br>
  NO crea la base de datos 'vsftpd', lo cual puede causar un problema de ejecución si no se tienen instaladas las dependencias previamente<br>
  NO crea la tabla 'accounts' para la base de datos 'vsftpd', por tanto, se puede producir el mismo error que al no crear la base de datos

Compatible con Fedora y Debian
