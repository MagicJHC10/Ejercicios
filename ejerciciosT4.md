# Juan Hernández

## Ejercicios Tema 4

### 1.Instala LXC en tu versión de Linux favorita. Normalmente la versión en desarrollo, disponible tanto en GitHub como en el sitio web está bastante más avanzada; para evitar problemas sobre todo con las herramientas que vamos a ver más adelante, conviene que te instales la última versión y si es posible una igual o mayor a la 1.0.

Instalamos LXC con:

```bash
$ sudo apt-get install lxc

```
Tras escoger la version mas actual con:

```bash
$ sudo add-apt-repository ppa:ubuntu-lxc/lxc-stable

```

### 2.Crear y ejecutar un contenedor basado en tu distribución y otro basado en otra distribución, tal como Fedora. Nota En general, crear un contenedor basado en tu distribución y otro basado en otra que no sea la tuya.

Para crearlos simplemente hacemos:

```bash
$  sudo lxc-create -t fedora -n ContenedorFedora

$  sudo lxc-create -t ubuntu -n ContenedorUbuntu

```

Y para ejecutarlos:

```bash
$  sudo lxc-start -n ContenedorFedora

$  sudo lxc-start -n ContenedorUbuntu

```


### 3.Instalar docker.

Hecho en mi [mi proyecto](https://github.com/MagicJHC10/Proyecto-IV)

### 4.Instalar a partir de docker una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS.

Hecho en mi [mi proyecto](https://github.com/MagicJHC10/Proyecto-IV)

### 7.Crear un Dockerfile para el servicio web que se ha venido desarrollando en el proyecto de la asignatura.

Hecho en mi [mi proyecto](https://github.com/MagicJHC10/Proyecto-IV)

### 8.Desplegar un contenedor en alguno de estos servicios, de prueba gratuita o gratuitos.

Hecho en mi [mi proyecto](https://github.com/MagicJHC10/Proyecto-IV)
