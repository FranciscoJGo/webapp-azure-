# Virtual Machine Azure AZ-900
Web App servicio de Azure para desplegar nuestra applicacion en internet con los beneficos de la nube de Azure [Mas información](https://azure.microsoft.com/es-mx/services/app-service/web/)
Guia para crear una Web App dentro de Azure utilizando sus recursos para configurarla

Antes de iniciar tenemos que ir al [Portal de Azure](https://portal.azure.com/)

## Paso 1
En la pagina Home seleccionamos la opción "Crear un Recurso".
![Menu lateral](/images/image1.png)

## Paso 2
Se muestran distintos servicios y elegimos "Aplicación web"
![Menu lateral](/images/image2.png)

## Paso 3
Apartado: Datos básicos

* Elegimos la suscripción "Azure for students"
* Creamos un nuevo grupo de recursos, el cual funciona como contenedor logico para utilizar los recursos de azure y donde vamos a guardar nuestra aplicación web en la nube. Lo nombramos como "webapp"
* Nombramos a nuestra aplicación web en este caso con el nombre "aplicacion-web"
* En la sección publicar, marcamos la que dice 'Código' ya que utilizaremos el código desde un repositorio de GitHub el cual se obtuvo mediante un fork de la Sherpa Fer.
* La 'pila del entorno en tiempo de ejecución' es con el lenguaje/codigo con el que esta realizada nuestra aplicacion, en este caso pondre: Node 14 LTS.
![Configuración](/images/image3.png)

* Sistema operativo Linux.
* Region Central US.
* En "Plan de App Service" en la opción SKU y tamaño con el Plan "Básico B1"
![Plan de app service](/images/image4.png)

## Apartado: Implementación(Deployment)
* En el apartado de "Configuración de Acciones de Github' elegimos "habilitar", de inmediato nos saldra una ventana emergente, donde nos pedira que autorizemos el acceso o conexión a nuestro perfil de GitHub.
![Cuenta de GitHub](/images/image5.png)
![Acceso Cuenta de GitHub](/images/image6.png)

* La organización ponemos el perfil de nuestro GitHub.
* En repositorio tendremos acceso a todos lo que tenemos en nuestro perfil, seleccionamos 'lab1'.
* La rama/branch es 'master'.
![Repositorio](/images/image7.png)

* Seleccionamos en vista previa del archivo donde nos muestra el archivo con la configuración de flujo de trabajo de Acciones de GitHub.

![Repositorio](/images/image8.png)


## Apartado: Redes(Networking)
* No se modifica algo en esta apartado y se deja con la configuración predeterminada

![Networking](/images/image9.png)

## Apartado: Supervisión(Monitoring)
Como no se utilizara 'Insights' lo dejamos con la configuración predeterminada. Lo pudieramos utilizar pero como es una demostración no es necesario.

![Monitoring](/images/image10.png)

## Apartado: Tags(Etiquetas)
Las etiquetas nos ayudan a identificar de una manera mas clara y agregar una descripcion a nuestros recursos desde quién los usa, el departamento, importancia entre otras que se quieran agregar.

![Tags](/images/image11.png)

## Apartado: Review+Create(revisar y crear)
Se muestra un resumen de nuestra aplicación de su caracteristicas
* Damos click en "crear"
![Revisar y crear](/images/image12.png)

* Podemos ver que se implemento nuestra aplicación.
![Deploy](/images/image13.png)

## Eliminar nuestra web app
* Para eliminar nuestra web app nos dirigimos al grupo de recursos  y seleccionamos  nuestra webapp y la eliminamos para evitar el cobro y futuros cargos a nuestra cuenta de azure.
![Eliminar webapp](/images/image14.png)




Redes:
* GitHub: [Francisco J Gonzalez](https://github.com/FranciscoJGo)

