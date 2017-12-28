# Juan Hernández

## Ejercicios Tema 5

### 1.Instalar los paquetes necesarios para usar KVM. Se pueden seguir estas instrucciones. Ya lo hicimos en el primer tema, pero volver a comprobar si nuestro sistema está preparado para ejecutarlo o hay que conformarse con la paravirtualización.

Ejecutamos kvm-ok y vemos el resultado 

![Ej1](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ejercicio1.png)

### 2. Crear varias máquinas virtuales con algún sistema operativo libre tal como Linux o BSD. Si se quieren distribuciones que ocupen poco espacio con el objetivo principalmente de hacer pruebas se puede usar CoreOS (que sirve como soporte para Docker) GALPon Minino, hecha en Galicia para el mundo, Damn Small Linux, SliTaz (que cabe en 35 megas) y ttylinux (basado en línea de órdenes solo). Hacer un ejercicio equivalente usando otro hipervisor como Xen, VirtualBox o Parallels.

He usado CoreOS:

![2.1](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ejercicio2-1.png)

Y vemos que funciona:

![2.2](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ejercicio2-2.png)

Por último he usado VirtualBox , creando una máquina virtual de Ubuntu.

![ubuntu](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ubuntu.png)

### 5.Crear una máquina virtual ubuntu e instalar en ella alguno de los servicios que estamos usando en el proyecto de la asignatura.

Hecho en mi [proyecto](https://github.com/MagicJHC10/Proyecto-IV) .

### 6.Instalar una máquina virtual con Linux Mint para el hipervisor que tengas instalado.

```bash
$ qemu-img create -f qcow2 mint.img 3G

$ qemu-system-x86_64 -machine accel=kvm -hda coreos.img -cdrom linuxmint-18.3-cinnamon-32bit.iso -m 1G -boot d

```

Y vemos que la maquina funciona correctamente ![virtual](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/virtual.png)
