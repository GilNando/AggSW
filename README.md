simple para respaldar servidores de mysql.
puede respaldar 1 o varias tablas de una db
en el archivo
config.ini

[Database]
Server=IP O NOMOBRE DEL SERVIDOR
User=USUARIO CON SUFICIENTES PRIVILEGIOS
Password=TU PASSWORD
Database=DB,DB2, ETC

[Backup]
DefaultPath=d:\backup\

en servidores.txt
aqui se guarda un historico de los servidores que se van usando

el respaldon lo hace con mysqldump.exe que esta en la misma carpeta que el .exe
sino encuentra archivo busca en rutas conocidas

el checkbox de "respaldar tabla por tabla". es para respaldar tablas y crea carpeta con lñas tablas.
