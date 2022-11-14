# Configuración de Vagrant

Para hacer el trabajo más sencillo, crearemos un entorno Vagrant con el cual, añadiendo un script de aprovisionamiento, ahorraremos trabajo a la hora de configurar cada una de las máquinas desde dentro.
![](capturas/captura0.png)

>Los aprovisionamientos usados en cada una de las máquinas son diferentes dependiendo el uso de dicha máquina:
>Servidores Webs Nginx
![](capturas/capturan.png)
>Servidor Mysql
![](capturas/capturam.png)
>Balanceador
![](capturas/capturab.png)





>Primeramente, actualizamos repositorios con sudo apt update y upgrade. Después de actualizar repositorios, instalamos el servidor web que va a tener nuestro balanceador, que en este caso es Nginx.
