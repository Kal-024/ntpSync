
[![Analytics](https://gabeacon.irvinlim.com/UA-4677001-16/Plantilla-de-repositorio/readme?useReferer)](https://github.com/Kal-024/ntpSync/)

## ntpdate Sync
Script ideal para automatizar la sincronización de la hora en linux

## Detalles 👇


*Esta herramienta la desarrolle una tarde libre xd, con el proposito de de problemas concurrentes al instalar linux*

<h1 align="center"> ntpdateSync.sh</h1>
<p align="center"><img src="https://images.unsplash.com/photo-1594904351111-a072f80b1a71?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=735&q=80"/></p> 

Para poder usar este script correctamente debemos tener instalados los paquetes:
'''
sudo apt-get install ntpdate (Debian/Ubuntu)
sudo yum install ntpdate (CentOS/RHEL)
sudo dnf install ntpdate (Fedora)
'''
 Ahora solo debemos dirigirnos preferiblemente **/usr/bin** y movemos allí el script
 **ntpdate_sync.sh**, ahora procedemos a ejecutarlo "**./ntpdate_sync.sh**" y darle permisos
 de ejecución **chmod +x ntpdate_sync.sh**.
 
 Seguido a eso debemo programar ese nuevo comando para que se inicie cada que encendamos la
 pc, con un **sudo contrab -e**, se no abrira un archivo y seguimos las instrucciones que nos da,
 por si no lo entendio, lo que tiene que hacer es crear una nueva linea y escribir:
 '''
 @remote /ruta/del/script.sh
 '''
 Guardamos los cambios y solo es cuetios de reiniciar la sesion de la maquina para comprobar que todo se ejecuto correctamente
 
 ### Más detalle sobre el comando contrab: ###
 * [https://geekytheory.com/programar-tareas-en-linux-usando-crontab/](https://geekytheory.com/programar-tareas-en-linux-usando-crontab)
 
