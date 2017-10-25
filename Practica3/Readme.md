# *Instalacion de SQL Server 2014 Express*

### Paso 1  
    Instalamos MYSQL Management Studio en un servidor
    en Windows 10   

>Antes descargamos todos los archivos necesarios para que vaya el SQLserver

![imagenes](./IMG/001.png)   

+ Y empezamos la Instalacion

![imagenes](./IMG/002.png)  

![imagenes](./IMG/003.png)  

![imagenes](./IMG/004.png)  

![imagenes](./IMG/005.png)     

### Paso 2

    Ya finalizada la instalacion nos conectamos de forma local a nuestro servidor    

![imagenes](./IMG/006.png)  

+  Le damos a conectar y nos conectamos de forma local

![imagenes](./IMG/007.png)  

> pd: despues cambie el nombre que pone ahi de "DESKTOP.." por "PABLO-PC" para que sea mas facil de usar  

### Paso 3  
> Antes de nada bajamos el Firewall tanto en el cliente como en el servidor   

    A continuacion hacemos una configuracion del SQL server ,para ello nos iremos a inicio y
     escribimos "SQL server configuration manager"   
+ Activamos el Server Browser para que podeamos especificarle a que mquina tenemos que conectarnos  

![imagenes](./IMG/008.png)   

+ Activamos TCP/IP   

![imagenes](./IMG/009.png)   

+ Y tambien lo activamos en el cliente  

![imagenes](./IMG/011.png)   

### Paso 4  

+ Instalamos el Framework para que pueda funcionar en el cliente   

![imagenes](./IMG/012.png)

+ Instalamos el MYsql server 2014 en el cliente  

![imagenes](./IMG/014.png)  

![imagenes](./IMG/013.png)

> cuando este instalado , en el servidor vamos a PABLO-PC  con la sesion activada  y abrimos la pestaña de  "Seguridad/inicio de sesio/ sa" y ca,biamos la contraseña de "sa"   

### Paso 5  

+ Abrimos el cliente ,ponemos la ip del servidor "172.18.17.30" luego en "Authentication" ponemos "SQL server Authentication" , en Login ponemos "sa" y en Password la contraseña que pusimos previamente  

> Y finalmente nos conectamos

![imagenes](./IMG/016.png)  
