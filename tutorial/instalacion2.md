# Instalación con Ansible

Lo primero para instalar Icinga con Ansible es utilizar el comando:
```
git clone https://github.com/asir-idp/icinga.git
```
Cuando termine de ejecutarle el git clone, nos meteremos en la siguiente carpeta
```
cd icinga/ansible
```
Dentro de esta, usaremos el siguiente comando que instalará Icinga:
```
./instalar-maestro.sh
```
## Configuración de Icinga mediante Ansible
Una vez instalado iremos al fichero hostname.icingaweb2 y cogeremos el token.

![Imagen1](imagenes/token32.png)

Escribiremos el token en su sitio:

![Imagen2](imagenes/ansible1.png)

En la pestaña de recursos, la llenaremos con lo siguiente:

![Imagen3](imagenes/ansible2.png)

Proseguiremos llenando las siguientes pestañas con la información de las capturas.

![Imagen4](imagenes/ansible3.png)

![Imagen5](imagenes/ansible4.png)

![Imagen6](imagenes/ansible5.png)

Hecho esto, se debería de terminar la configuración de Icinga.

![Imagen7](imagenes/ansiblef.png)

### [Volver a la leyenda](../index.md)
### [Siguiente paso](monitorizacion.md)
